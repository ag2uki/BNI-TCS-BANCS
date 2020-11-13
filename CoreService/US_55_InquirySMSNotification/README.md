Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>DOCOTEL</systemId>
            <content xsi:type="bo:InquirySMSNotificationReq">
               <action>E</action>
               <cifNumber>9144782363</cifNumber>
               <accountNumber>115471119</accountNumber>
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
               <coreJournal>460200</coreJournal>
            </header>
            <content xsi:type="bo:InquirySMSNotificationRes">
               <cifNumber>9144782363</cifNumber>
               <accountNumber>115471119</accountNumber>
               <phoneNumber>9</phoneNumber>
               <debitTreshold>100000.000</debitTreshold>
               <checkDebit>ON</checkDebit>
               <creditTreshold>20000.000</creditTreshold>
               <checkCredit>ON</checkCredit>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```