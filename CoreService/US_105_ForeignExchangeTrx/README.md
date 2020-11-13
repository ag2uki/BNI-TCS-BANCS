Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <customHeader>
               <branch>265</branch>
               <terminal>037</terminal>
               <teller>24446</teller>
               <systemJournal/>
            </customHeader>
            <systemId>FEM</systemId>
            <content xsi:type="bo:ForeignExchangeTrxReq">
               <buyAmount>15</buyAmount>
               <buyCurrency>USD</buyCurrency>
               <sellCurrency>IDR</sellCurrency>
               <transactionAmount>198975</transactionAmount>
               <promoCode>ZZ</promoCode>
               <beneficiaryIdType>3</beneficiaryIdType>
               <senderDetails>KT12345</senderDetails>
               <baseCcyAmount>198975</baseCcyAmount>
               <commission/>
               <change/>
               <rateType>05</rateType>
               <fundType>DS</fundType>
               <narration>KUCING GARONG BELANG TIGA</narration>
               <bookingNumber/>
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
               <coreJournal>064377</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>064377           RAK PERANTARA CCY IDR</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```