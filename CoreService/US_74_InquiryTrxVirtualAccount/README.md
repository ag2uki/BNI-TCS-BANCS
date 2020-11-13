Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SOA</systemId>
            <content xsi:type="bo:InquiryTrxVirtualAccountReq">
               <virtualAccountNum>9880024408522120</virtualAccountNum>
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
               <coreJournal>571813</coreJournal>
            </header>
            <content xsi:type="bo:CompiledInquiryTrxVirtualAccountRes">
               <virtualAccountNum>09880024408522120</virtualAccountNum>
               <companyName>Pegadaian 988</companyName>
               <status>1</status>
               <companyAccountNum>00000000000000883</companyAccountNum>
               <virtualAccountType>007</virtualAccountType>
               <companyCode>00244</companyCode>
               <txnType></txnType>
               <currentPage>0001</currentPage>
               <fromDate>00000000</fromDate>
               <toDate>00000000</toDate>
               <journalNum>000000</journalNum>
               <virtualAccountName>Pegadaian 120</virtualAccountName>
               <virtualAccountStatus>1</virtualAccountStatus>
               <virtualAccountBalance>0.00</virtualAccountBalance>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```