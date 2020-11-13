Sample SOAP Request
```
<soapenv:Envelope xmlns:bo="http://service.bni.co.id/core/bo" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://service.bni.co.id/core" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transaction>
         <request>
           <systemId>BNIDIRECT</systemId>
           <content xsi:type="bo:DepositOverdraftLimitUpdateReq">
             <accountNumber>115362643</accountNumber>
             <overDraftLimit1>25000000000</overDraftLimit1>
             <effectiveDate1>2013-05-31</effectiveDate1>
             <dueDate1>2014-06-03</dueDate1>
           </content>
         </request>
      </core:transaction>
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
            <header xmlns:ns0="bons">
               <coreJournal>278172</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage" xmlns:ns0="bons"/>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```