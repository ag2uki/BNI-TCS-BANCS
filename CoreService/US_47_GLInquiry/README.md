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

Bancs Format
```
[ 0100 ** 003099600900001020400000000 0 I 0 000000 007883605525010011]

[ 0623 0539 0000 000000003099600900001032013000000000040320600 000000 0300788360552501001BBN.PENDIDIKAN & PELATIHAN 0030788IDR 129.498.000,00-55250101 01 0,00 0,00 0,00 0,00 129.498.000,00- 0,00 0,00 0,00 0,00 0,00 0,00 0,00 ACTUAL 0,00 0,00 0,00 00000000000000000M 0 0,00 0,00 003131/05/20100788IDR0000552501 00/00/0000 ]
```