Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:KliringOutwardReq">
               <accountNum>1231</accountNum>
               <nominalPenarikan>355000</nominalPenarikan>
               <nominalDikirim>350000</nominalDikirim>
               <biaya>5000</biaya>
               <pesan1Pengirim>pembayaran cicilan</pesan1Pengirim>
               <pesan2Pengirim></pesan2Pengirim>
               <namaPenerima>Dian Amalia</namaPenerima>
               <alamat1Penerima>Jl. Mawar no 10</alamat1Penerima>
               <alamat2Penerima></alamat2Penerima>
               <nomorTelponPenerima></nomorTelponPenerima>
               <kodePosPenerima></kodePosPenerima>
               <idPenerima></idPenerima>
               <tipeIdPenerima>0001</tipeIdPenerima>
               <namaPengirim>Diana</namaPengirim>
               <alamatPengirim>Jl. Melati no 10</alamatPengirim>
               <nomorTelponPengirim></nomorTelponPengirim>
               <tipeResidensiPengirim>0</tipeResidensiPengirim>
               <tipeResidensiPenerima>0</tipeResidensiPenerima>
               <sandiBankPenerima>0010016</sandiBankPenerima>
               <accountPenerima>888123456789</accountPenerima>
               <intermediaryBranch>760</intermediaryBranch>
               <sandiTransaksi>50</sandiTransaksi>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>
```

Sample SOAP Response
```
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header>
               <coreJournal>237777</coreJournal>
            </header>
            <content xsi:type="bo:KliringOutwardRes">
               <message>00000000350000000+IDR996001055310520100000 O.K.</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 1004                    **            003099600100001055645000000     0  I  0 000000  0000000000000123100000000000000000+00000000355000000+ 00000000                                                       888123456789                      IDR00000000350000000+IDR00000000350000000+00000000000000000+00000000000000000+02pembayaran cicilan                                                                                                                          Dian Amalia                                                                     Jl. Mawar no 10                                                                                                                     0001                          Diana                                                                           Jl. Melati no 10                                            00                                                                 0010016                      076000000000005000000+0                                                50]

[ 0131    0047            0000    000000003099600100001060408237777000040320400 000000  0300323777700000000350000000+IDR996001055310520100000 O.K.                                                                     ]
```