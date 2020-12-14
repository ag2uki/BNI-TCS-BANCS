Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>BNIDIRECT</systemId>
            <content xsi:type="bo:KliringOutwardv2Req">
               <accountNum>7778018</accountNum>
               <nominalPenarikan>355000</nominalPenarikan>
               <nominalDikirim>350000</nominalDikirim>
               <pesan1Pengirim>Kliring Out via SOA BNIDIRECT</pesan1Pengirim>
               <pesan2Pengirim>Kliring Out via SOA BNIDIRECT</pesan2Pengirim>
               <namaPenerima>Mr.Albus Wulfric Brian</namaPenerima>
               <alamat1Penerima>Hogwarts School</alamat1Penerima>
               <alamat2Penerima>Diagon Alley</alamat2Penerima>
               <nomorTelponPenerima>987654321</nomorTelponPenerima>
               <kodePosPenerima>12345</kodePosPenerima>
               <idPenerima>654321654321</idPenerima>
               <tipeIdPenerima>0001</tipeIdPenerima>
               <namaPengirim>Mr. Tom Marvolo</namaPengirim>
               <alamatPengirim>Knockturn Alley</alamatPengirim>
               <nomorTelponPengirim>021987654321</nomorTelponPengirim>
               <tipeResidensiPengirim>0</tipeResidensiPengirim>
               <tipeResidensiPenerima>0</tipeResidensiPenerima>
               <sandiBankPenerima>0010016</sandiBankPenerima>
               <accountPenerima>8881234567898563215212532685000002</accountPenerima>
               <jenisPenerima>1</jenisPenerima>
               <intermediaryBranch>760</intermediaryBranch>
               <biaya>5000</biaya>
               <bankPenerimaAkhir>BRINIDJA</bankPenerimaAkhir>
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
               <coreJournal>300188</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 1055                    **            003098900100001055645000000     0  I  0 000000  0000000000777801800000000000000000+00000000355000000+ 00000000                                                       8881234567898563215212532685000002IDR00000000350000000+IDR00000000350000000+00000000000000000+00000000000000000+02Kliring Out via SOA BNIDIRECT                     Kliring Out via SOA BNIDIRECT                                                             Mr.Albus Wulfric Brian                                                          Hogwarts School                         Diagon Alley                            987654321           12345   654321654321            0001                          Mr. Tom Marvolo                                                                 Knockturn Alley                         021987654321        00                                                                                              076000000000005000000+0                                        BRINIDJA50                                                  1]

[ 0162    0078            0000    000000003098900100001060408300158000040320200 000000  080000 O.K.                                                                     ]
```