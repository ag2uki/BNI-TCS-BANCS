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
[ 0100                    **            003076600100777020400000000     0  I  0 000000  007663332001010011]

[ 0623    0539            0000    000000003076600100777032013000000000040320600 000000  0300766333200101001KU YAKIR EUR                                                          0030766EUR        258.886,24 20010107   01        584.405,91-        723.238,53-        448.417,50       2.151.830,20       1.951.172,58-      2.597.973,88       2.228.145,18-        132.219,63         188.681,48-        276.680,52         791.194,54-      1.118.602,73 ACTUAL              0,00               0,00               0,00 00000000000000000D 0               0,00               0,00 000029/07/20050766EUR0000200101            00/00/0000       ]
```