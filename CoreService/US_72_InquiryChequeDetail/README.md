Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:InquiryChequeDetailReq">
               <accountNo>316035436</accountNo>
               <chequePrefix>BA</chequePrefix>
               <chequeNo>200001</chequeNo>
               <status>CI</status>
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
               <coreJournal>116300</coreJournal>
            </header>
            <content xsi:type="bo:InquiryChequeDetailRes">
               <chequePrefix>BA</chequePrefix>
               <chequeNo>BA200001</chequeNo>
               <chequeFirstNo>BA200001</chequeFirstNo>
               <transactionDate>2014-11-01</transactionDate>
               <transactionTime>10:00:30</transactionTime>
               <status>CI</status>
               <amount/>
               <tellerID>00001</tellerID>
               <branchCode>0001</branchCode>
               <tranCode>052217</tranCode>
               <journalNumber>116300</journalNumber>
               <reason>00</reason>
               <description>PENERBITAN BILYET GIRO</description>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```