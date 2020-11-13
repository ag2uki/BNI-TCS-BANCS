Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>API</systemId>
            <content xsi:type="bo:CreateVARetailReq">
               <virtualAccountType>987</virtualAccountType>
               <companyCode>00114479721</companyCode>
               <virtualAccountNum>9870011447972199</virtualAccountNum>
               <accountNum>00000000114479721</accountNum>
               <companyName>FAJAR NURCAHYO</companyName>
               <accountStatus>1</accountStatus>
               <virtualAccountName>NYOPEDIA</virtualAccountName>
               <virtualAccountStatus>1</virtualAccountStatus>
               <virtualAccountTrxType>7</virtualAccountTrxType>
               <billAmount>1000000</billAmount>
               <handphoneNumber>081212345678</handphoneNumber>
               <chargesAmount>0</chargesAmount>
               <var1Amount>0</var1Amount>
               <var2Amount>0</var2Amount>
               <date1/>
               <exptime/>
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
               <coreJournal>396436</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```