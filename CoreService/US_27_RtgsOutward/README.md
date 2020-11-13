Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>GLOBS</systemId>
            <content xsi:type="bo:RtgsOutwardReq">
               <accountNum>114479721</accountNum>
               <nominalPenarikan>125030000</nominalPenarikan>
               <nominalDikirim>125000000</nominalDikirim>
               <pesan1Pengirim>rtgs via soa pesan 1</pesan1Pengirim>
               <pesan2Pengirim>rtgs via soa pesan 2</pesan2Pengirim>
               <pesan3Pengirim>rtgs via soa pesan 3</pesan3Pengirim>
               <namaPenerima>Ibu Ella</namaPenerima>
               <alamat1Penerima>Jalan sukacita</alamat1Penerima>
               <alamat2Penerima>Jakarta</alamat2Penerima>
               <nomorTelponPenerima>987654321</nomorTelponPenerima>
               <kodePosPenerima>321654</kodePosPenerima>
               <idPenerima>EL12232323233</idPenerima>
               <tipeIdPenerima>tes</tipeIdPenerima>
               <nama1Pengirim>Ibu Elli</nama1Pengirim>
               <nama2Pengirim>pengirim 2</nama2Pengirim>
               <tipeResidensiPengirim>01</tipeResidensiPengirim>
               <tipeResidensiPenerima>01</tipeResidensiPenerima>
               <sandiBankPenerima>CENAIDJA</sandiBankPenerima>
               <accountPenerima>5589456793678497684736487384763893</accountPenerima>               
               <intermediaryBranch>760</intermediaryBranch>
               <biaya>30000</biaya>
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
               <coreJournal>233961</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```