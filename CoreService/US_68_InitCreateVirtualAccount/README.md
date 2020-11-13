Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SMS</systemId>
            <content xsi:type="bo:InitCreateVirtualAccountReq">
               <virtualAccountType>8</virtualAccountType>
               <companyCode>5</companyCode>
               <virtualAccountNum>8005000000000013</virtualAccountNum>
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
               <coreJournal>585889</coreJournal>
            </header>
            <content xsi:type="bo:InitCreateVirtualAccountRes">
               <virtualAccountType>8</virtualAccountType>
               <companyCode>5</companyCode>
               <accountNum>8005000000000013</accountNum>
               <virtualAccountNum>115453258</virtualAccountNum>
               <companyName>PT ABC</companyName>
               <accountStatus>1</accountStatus>
               <virtualAccountName>SARI ANGGRAINI - 1</virtualAccountName>
               <virtualAccountStatus>1</virtualAccountStatus>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```