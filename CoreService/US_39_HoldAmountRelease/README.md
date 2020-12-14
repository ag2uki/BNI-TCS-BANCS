Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWTASPEN</systemId>
            <content xsi:type="bo:HoldAmountReleaseReq">
               <accountNum>114479721</accountNum>
               <amount>1981300</amount>
               <journalNum>396505</journalNum>
               <setDate>31052010</setDate>
               <reasonBlock>11</reasonBlock>
               <detail>kucingmeong</detail>
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
               <coreJournal>396507</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>Nama :    FAJAR</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0180                    **            003099909900099009095000000     0  I  0 000000  0000000011447972100000001981300000+kucingmeong                        3105201039650511            ]

[ 0162    0078            0000    000000003099909900099009095396507000040320200 000000  080000 O.K.          Nama :    FAJAR                                            ]
```