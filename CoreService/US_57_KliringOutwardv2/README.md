Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SYARIAH</systemId>
            <customHeader>
               <teller>00001</teller>
               <branch>0259</branch>
               <overrideFlag>I</overrideFlag>
            </customHeader>
            <content xsi:type="bo:KliringOutwardReq">
               <accountNum>116943547</accountNum>
               <nominalPenarikan>355000</nominalPenarikan>
               <nominalDikirim>350000</nominalDikirim>
               <pesan1Pengirim>kliring out via soa 1</pesan1Pengirim>
               <pesan2Pengirim>kliring out via soa 2</pesan2Pengirim>
               <namaPenerima>penerima</namaPenerima>
               <alamat1Penerima>alamat 1 penerima</alamat1Penerima>
               <alamat2Penerima>alamat 2 penerima</alamat2Penerima>
               <nomorTelponPenerima>987654321</nomorTelponPenerima>
               <kodePosPenerima>12345</kodePosPenerima>
               <idPenerima>654321654321</idPenerima>
               <tipeIdPenerima>0001</tipeIdPenerima>
               <namaPengirim>nama pengirim</namaPengirim>
               <alamatPengirim>alamat pengirim</alamatPengirim>
               <nomorTelponPengirim>021987654321</nomorTelponPengirim>
               <tipeResidensiPengirim>0</tipeResidensiPengirim>
               <tipeResidensiPenerima>0</tipeResidensiPenerima>
               <sandiBankPenerima>0010016</sandiBankPenerima>
               <accountPenerima>888123456789</accountPenerima>
               <intermediaryBranch>760</intermediaryBranch>
               <biaya>5000</biaya>
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
               <coreJournal>565578</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>T25924ADA1AF594A565578</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 1055 ** 003099600100001055645000000 0 I 0 000000 0000000011681727300000000000000000+00000000105000000+ 00000000 121132135 IDR00000000100000000+IDR00000000100000000+00000000000000000+00000000000000000+02 KEVANDIO BAYU HARVEYANTO 0000 Kim Caca 1 Macica 01 076000000000005000000+0 BBBAIDJA50 1]

[ 0162 0078 0000 000000003099600100001055645256083000040320200 000000 080000 O.K. T99624AD9ECE3453256083 ]
```