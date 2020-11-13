Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>RAISECALL</systemId>
            <content xsi:type="bo:AccountShortInquiryReq">
               <accountNum>114479721</accountNum>
               <options>8</options>
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
            <header/>
            <content xsi:type="bo:AccountShortInquiryRes">
               <d_accountNum>00000000114479721</d_accountNum>
               <d_currency>IDR</d_currency>
               <d_status>BUKA</d_status>
               <d_product>EMERALD SAVING</d_product>
               <d_homeBranch>0063</d_homeBranch>
               <d_cifNum>00000009100751913</d_cifNum>
               <d_name>Bpk FAJAR NURCAHYO</d_name>
               <d_nameRek/>
               <d_currentBalance>5.445.025.007,00</d_currentBalance>
               <d_availableBalance>5.439.081.107,00</d_availableBalance>
               <d_openDate>2010-05-31</d_openDate>
               <d_address1>JALAN EBONY NO. 99</d_address1>
               <d_address2>9999KOMPLEK BUDIMAN SENTOSA</d_address2>
               <d_address3>Tanah Sareal</d_address3>
               <d_address4>Tanah Sereal       /Bogor</d_address4>
               <d_postCode>16161</d_postCode>
               <d_homePhone>02518369696</d_homePhone>
               <d_mobilePhone>08111696969</d_mobilePhone>
               <d_address1AA>JALAN EBONY NO. 99</d_address1AA>
               <d_address2AA>9999KOMPLEK BUDIMAN SENTOSA</d_address2AA>
               <d_address3AA>Tanah Sareal</d_address3AA>
               <d_address4AA>Tanah Sereal       /Bogor</d_address4AA>
               <d_postCodeAA>16161</d_postCodeAA>
               <d_homePhoneAA>02518369696</d_homePhoneAA>
               <d_mobilePhoneAA>08111696969</d_mobilePhoneAA>
               <accountProductType>DEP</accountProductType>
               <d_accType>2301</d_accType>
               <d_subCat>0001</d_subCat>
               <d_availableInterest>0,00</d_availableInterest>
               <d_lienBalance>5.943.900,00</d_lienBalance>
               <d_unclearBalance>0,00</d_unclearBalance>
               <d_interestRate>0,0000</d_interestRate>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```