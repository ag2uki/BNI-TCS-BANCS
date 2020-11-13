Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>IBOC</systemId>
            <content xsi:type="bo:GLInquiryReq">
               <accountNum>766333200101001</accountNum>
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
               <coreJournal>000000</coreJournal>
            </header>
            <content xsi:type="bo:GLInquiryRes">
               <accountNum>766333200101001</accountNum>
               <accountName>KU YAKIR EUR</accountName>
               <branchNum>766</branchNum>
               <currency>EUR</currency>
               <balance>258.886,24</balance>
               <accountType>2001</accountType>
               <accountSubCat>107</accountSubCat>
               <status>1</status>
               <ledgerValue>ACTUAL</ledgerValue>
               <glcc>0766EUR0000200101</glcc>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```