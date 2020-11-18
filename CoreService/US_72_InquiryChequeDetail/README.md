Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:InquiryChequeDetailReq">
               <accountNo>00000000115469575</accountNo>
               <chequePrefix>CA</chequePrefix>
               <chequeNo>151511</chequeNo>
               <status>CP</status>
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
               <coreJournal>237470</coreJournal>
            </header>
            <content xsi:type="bo:InquiryChequeDetailRes">
               <chequePrefix>CA</chequePrefix>
               <chequeNo>CA151511</chequeNo>
               <chequeFirstNo>CA151511</chequeFirstNo>
               <transactionDate>2010-05-31</transactionDate>
               <transactionTime>14:53:14</transactionTime>
               <status>CP</status>
               <amount>1000000</amount>
               <tellerID>00001</tellerID>
               <branchCode>0259</branchCode>
               <tranCode>052217</tranCode>
               <journalNumber>237470</journalNumber>
               <reason>00</reason>
               <description>TEST 51071</description>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0109                    **            003099600100001052217000000     0  I  0 000000  00000000115469575CA151511CP]

[ 0192    0108            0000    000000003099600100001052217237470000040320000 000000  03CA151511CA1515113105201014:53:14CP00000001000000000+025900TEST 51071                                        0000 O.K.                                                                     ]
```