Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>KIOSK</systemId>
            <content xsi:type="bo:GLTransferReq">
               <fromAccount>115453258</fromAccount>
               <debitAmount>10000</debitAmount>
               <toAccount>760360289402727</toAccount>
               <currencyFromAccount>IDR</currencyFromAccount>
               <creditAmount>10000</creditAmount>
               <currencyToAccount>IDR</currencyToAccount>
               <kursType>02</kursType>
               <narasi>Testing Transfer SMARTKIOS 1556265909849</narasi>
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
               <coreJournal>571643</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>O.K.</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```