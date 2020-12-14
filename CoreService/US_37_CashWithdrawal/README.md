Sample SOAP Request
```
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transaction xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <request>
            <systemId>BULOG</systemId>
            <content xsi:type="bo:CashWithdrawalReq">
               <accountNum>114485135</accountNum>
               <amount>10</amount>
               <promoCode>AR</promoCode>
               <currency>IDR</currency>
               <narative>A_201602_198911020510_20_AAK</narative>
            </content>
         </request>
      </core:transaction>
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
               <coreJournal>640329</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>O.K.       NAMA:     Bpk DUMBO OLAF 3</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0967                    **            003099299901001001060000000     0  I  0 000000  00000000114485135                  00000000000010000+                AR                                                                                IDR00000000000000000+   00000000000000000+00000000000000000+00000000000000000+00                                                                                                                                                                                                                                                                                                                                                                                       A_201602_198911020510_20_AAK                                                                                                                                                                                                                                                           ]

[ 0162    0078            0000    000000003099299901001001060640329000040320200 000000  080000 O.K.       NAMA:     Bpk DUMBO OLAF 3                                    ]
```