Sample SOAP Request
```
<soapenv:Envelope xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:q0="http://service.bni.co.id/core">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWTASPEN</systemId>
            <content xsi:type="bo:HoldAmountReq">
               <accountNum>114479721</accountNum>
               <amount>1981300</amount>
               <reasonBlock>11</reasonBlock>
            	<detail>kucingkuncung123</detail>
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
               <coreJournal>396505</coreJournal>
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
[ 0165                    **            003099909900099009093000000     0  I  0 000000  0000000011447972100000001981300000+kucingkuncung123           11                   ]

[ 0162    0078            0000    000000003099909900099009093396505000040320200 000000  080000 O.K.          Nama :    FAJAR                                           ]
```