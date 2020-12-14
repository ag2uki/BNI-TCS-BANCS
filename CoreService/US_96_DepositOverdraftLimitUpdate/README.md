Sample SOAP Request
```
<soapenv:Envelope xmlns:bo="http://service.bni.co.id/core/bo" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://service.bni.co.id/core" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transaction>
         <request>
           <systemId>BNIDIRECT</systemId>
           <content xsi:type="bo:DepositOverdraftLimitUpdateReq">
             <accountNumber>115362643</accountNumber>
             <overDraftLimit1>25000000000</overDraftLimit1>
             <effectiveDate1>2013-05-31</effectiveDate1>
             <dueDate1>2014-06-03</dueDate1>
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
            <header xmlns:ns0="bons">
               <coreJournal>278172</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage" xmlns:ns0="bons"/>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0440                    **            003098900100001007010000000     0  I  0 000000  0000000011536264301  00000025000000023000+S3105201303062014000000000000000000000000000000000+ 0000000000000000000000000000000000000000000000000+ 0000000000000000000000000000000000000000000000000+ 0000000000000000000000000000000000000000000000+ 000000+ 9999999999R00000000000000000R00000000000000000I0250000+0000000000000000000000 00000000000000000+   6000101]

[ 0162    0078            0000    000000003098900100001007010288228000040320200 000000  080000 O.K.                                                                     ]
```