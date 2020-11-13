Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SYARIAH</systemId>
            <content xsi:type="bo:ActivationCardReq">
               <cardNum>5264222430474288</cardNum>
               <cardDescription>BNI CARD SILVER</cardDescription>
               <cifNum>9100170224</cifNum>
               <accountName>Bpk ROBERT NARO ROBERT NARO</accountName>
               <address1>JL SETIABUDI 5 NO 7 KTP UBAH</address1>
               <address2>12 34 RUMAH ORCHID</address2>
               <address3>setiabudi raya</address3>
               <address4>SADANANYA</address4>
               <postCode>46256</postCode>
               <cardName1>Bpk ROBERT NARO ROBERT NAR</cardName1>
               <cardName2/>
               <issueCard>06052019</issueCard>
               <expiredCard>30042024</expiredCard>
               <confirmFlag>Y</confirmFlag>
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
               <coreJournal>365342</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>O.K.</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```