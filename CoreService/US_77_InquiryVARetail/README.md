Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>API</systemId>
            <content xsi:type="bo:InquiryVARetailReq">
               <virtualAccountType>987</virtualAccountType>
               <companyCode>00114479721</companyCode>
               <virtualAccountNum>9870011447972100</virtualAccountNum>
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
               <coreJournal>396591</coreJournal>
            </header>
            <content xsi:type="bo:InquiryVARetailRes">
               <virtualAccountType>987</virtualAccountType>
               <companyCode>114479721</companyCode>
               <virtualAccountNum>9870011447972100</virtualAccountNum>
               <accountNum>114479721</accountNum>
               <companyName>FAJAR NURCAHYO</companyName>
               <accountStatus>1</accountStatus>
               <virtualAccountName>NYOPEDIA</virtualAccountName>
               <virtualAccountStatus>1</virtualAccountStatus>
               <virtualAccountTrxType>7</virtualAccountTrxType>
               <billAmount>1000000000+</billAmount>
               <handphoneNumber>081212345678</handphoneNumber>
               <chargesAmount>+</chargesAmount>
               <var1Amount>+</var1Amount>
               <var2Amount>+</var2Amount>
               <date1>99999999</date1>
               <exptime>00000000</exptime>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```