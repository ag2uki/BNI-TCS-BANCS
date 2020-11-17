Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>H2HSERVICE</systemId>
            <content xsi:type="bo:CreateVirtualAccountReq">
               <accountNum>114458054</accountNum>
               <accountStatus>1</accountStatus>
               <companyCode>300</companyCode>
               <companyName>PT DOCOTEL</companyName>
               <virtualAccountName>MEOWMEOWMEOW</virtualAccountName>
               <virtualAccountStatus>1</virtualAccountStatus>
               <virtualAccountNum>8300012345678908</virtualAccountNum>
               <virtualAccountType>8</virtualAccountType>
               <virtualAccountTrxType>9</virtualAccountTrxType>
               <billAmount>10</billAmount>
               <exptime>16053000</exptime>
               <date1>12042019</date1>
               <chargesAmount/>
               <var1Amount/>
               <var2Amount/>
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
               <coreJournal>396444</coreJournal>
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
[ 0364                    **            003098700300002031993000000     0  I  0 000000  C        008003000830001234567890800000000114458054PT DOCOTEL                              1MEOWMEOWMEOW                                                                    1900000000000010000+                    00000000000000000+00000000000000000+00000000000000000+1204201916053000]

[ 0162    0078            0000    000000003098700300002031993396444000040320200 000000  080000 O.K.                                                                     ]
```