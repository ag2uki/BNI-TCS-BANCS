Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWMOBILE</systemId>
            <customHeader>
               <branch>760</branch>
               <terminal>001</terminal>
               <teller>14977</teller>
               <overrideFlag>I</overrideFlag>
               <supervisorId/>
            </customHeader>
            <content xsi:type="bo:HoldAmountBerjangkaReq">
               <accountNum>1120192039</accountNum>
               <amount>15000</amount>
               <reasonBlock>13</reasonBlock>
               <setDate>10022021</setDate>
               <detail/>
               <detail2/>
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
               <coreJournal>317444</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>Nama : SHINJI</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0180                    **            003076000114977009093000000     0  I  0 000000  0000000112019203900000000015000000+10022021                   13                                  ]

[ 0162    0078            0000    000000003076000114977009093317444000040320200 000000  080000 O.K.          Nama :    SHINJI                                           ]
```