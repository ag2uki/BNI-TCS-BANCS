Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>ATM</systemId>
            <content xsi:type="bo:InquiryUserDefinedCodeV2Req">
               <accountNum>116892513</accountNum>
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
               <coreJournal>237484</coreJournal>
            </header>
            <content xsi:type="bo:InquiryUserDefinedCodeV2Res">
               <accntNumber1>9154879169</accntNumber1>
               <defaultString/>
               <userCode2122/>
               <teroris/>
               <defaultString3a/>
               <defaultString3b/>
               <defaultString4a/>
               <defaultString4b/>
               <defaultString4c/>
               <defaultString5a/>
               <defaultString5b/>
               <defaultString6a/>
               <defaultString6b/>
               <defaultString6c/>
               <hubdgBank/>
               <badanHukum/>
               <riskLevel/>
               <jenisOpr/>
               <tawarProduk/>
               <shareDataPri/>
               <defaultString7h/>
               <defaultString7i/>
               <defaultString7j/>
               <defaultString8a/>
               <defaultString8b/>
               <defaultString8c/>
               <defaultString8d/>
               <defaultString8e/>
               <defaultString9a/>
               <defaultString9b/>
               <defaultString9c/>
               <defaultString9d/>
               <defaultString9e/>
               <defaultString10a/>
               <defaultString10b/>
               <defaultString10c/>
               <defaultString10d/>
               <defaultString10e/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```