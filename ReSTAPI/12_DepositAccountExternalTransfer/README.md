WSDL Filename : WSDLInterBankPayment.wsdl

`1. Inquiry`

Sample SOAP Request:
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/switcher_v2/atmbersama"
xmlns:q1="http://service.bni.co.id/atmbersama" 
xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" 
xmlns:xsd="http://www.w3.org/2001/XMLSchema"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q1:inquiryTransaction>
         <request xsi:type="q0:RequestInquiryInterBank">
            <clientId>NEWMOBILE</clientId>
            <provider>ATMBERSAMA</provider>
            <reffNum>20200131143943000809</reffNum>
            <content xsi:type="q0:InquiryInterBankReq">
               <destinationBankCode>014</destinationBankCode>
               <destinationAccountNum>3333333333</destinationAccountNum>
               <accountNum>115210419</accountNum>
               <userChannelId>6283897771333</userChannelId>
               <customerReffNum>11111</customerReffNum>
               <amount>200000</amount>
            </content>
         </request>
      </q1:inquiryTransaction>
   </soapenv:Body>
</soapenv:Envelope>
```

Sample SOAP Response:
```
<soapenv:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Header/>
   <soapenv:Body>
      <at:inquiryTransactionResponse xmlns:at="http://service.bni.co.id/atmbersama">
         <response>
            <clientId>NEWMOBILE</clientId>
            <reffNum>20200131143943000809</reffNum>
            <provider>ATMBERSAMA</provider>
            <content>
               <destinationAccountNum>3333333333</destinationAccountNum>
               <destinationAccountName>Bpk KEN AROK</destinationAccountName>
               <destinationBankName>BCA</destinationBankName>
               <retrievalReffNum>100000000097</retrievalReffNum>
               <accountName/>
               <responseCode>00</responseCode>
            </content>
         </response>
      </at:inquiryTransactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

`2. Payment`

Sample SOAP Request:
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/atmbersama" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <clientId>NEWMOBILE</clientId>
            <provider>ATMBERSAMA</provider>
            <reffNum>20200131143943000809</reffNum>
            <content>
               <destinationBankCode>014</destinationBankCode>
               <destinationAccountNum>3333333333</destinationAccountNum>
               <accountNum>115210419</accountNum>
               <amount>200000</amount>
               <userChannelId>6283897771333</userChannelId>
               <customerReffNum>11111</customerReffNum>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>
```

Sample SOAP Response:
```
<soapenv:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Header/>
   <soapenv:Body>
      <at:transactionResponse xmlns:at="http://service.bni.co.id/atmbersama">
         <response>
            <clientId>NEWIBANK</clientId>
            <reffNum>202002031528024422</reffNum>
            <provider>ATMBERSAMA</provider>
            <content>
               <destinationAccountNum>123456</destinationAccountNum>
               <destinationAccountName>NICKO DWI</destinationAccountName>
               <customerReffNum/>
               <destinationBankName>ARTOS</destinationBankName>
               <retrievalReffNum>100000000280</retrievalReffNum>
               <accountName>BPK I  NABEL K</accountName>
               <responseCode>00</responseCode>
            </content>
         </response>
      </at:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```