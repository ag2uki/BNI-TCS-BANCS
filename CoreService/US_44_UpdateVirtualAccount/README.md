Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>API</systemId>
            <content xsi:type="bo:UpdateVirtualAccountReq">
               <virtualAccountType>8</virtualAccountType>
               <companyCode>5</companyCode>
               <virtualAccountNum>8005000000000013</virtualAccountNum>
               <accountNum>115453258</accountNum>
               <companyName>PT ABC</companyName>
               <accountStatus>1</accountStatus>
               <virtualAccountName>SARI ANGGRAINI - 1</virtualAccountName>
               <virtualAccountStatus>1</virtualAccountStatus>
               <billAmount>100</billAmount>
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
               <coreJournal>584155</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0364                    **            003098600100001031993000000     0  I  0 000000  A        008000050800500000000001300000000115453258PT ABC                                  1SARI ANGGRAINI - 1                                                              1000000000000100000+                    00000000000000000+00000000000000000+00000000000000000+                ]

[ 0162    0078            0000    000000003098600100001031993584155000040320200 000000  080000 O.K.                                                                     ]
```