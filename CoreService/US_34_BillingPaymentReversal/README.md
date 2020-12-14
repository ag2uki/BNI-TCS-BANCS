Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>PLNPAYMENT</systemId>
            <customHeader>
               <branch>265</branch>
               <terminal>1</terminal>
               <teller>25952</teller>
            </customHeader>
            <content xsi:type="bo:BillingPaymentReversalReq">
               <billerCode>0125</billerCode>
               <regionCode>1008</regionCode>
               <billerName>BPJS_KETENAGAKERJAAN</billerName>
               <cardNum>150416599021</cardNum>
               <paymentMethod>2</paymentMethod>
               <accountNum>116913862</accountNum>
               <trxAmount>6600000.000</trxAmount>
               <naration>Test FANY816090000489KUCINGKUNCUNGBELANG10</naration>
               <invoiceNum>INV12345678</invoiceNum>
               <journalNum>396301</journalNum>
               <sign>1</sign>
               <refNo/>
               <flag>Y</flag>
               <amount1>1000000.000</amount1>
               <amount2>1000000.000</amount2>
               <amount3>1000000.000</amount3>
               <amount4>1000000.000</amount4>
               <amount5>1600000.000</amount5>
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
               <coreJournal>396365</coreJournal>
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
[ 0352                    **            003006321030011095046000000     0     0 000000  01251008BPJS_KETENAGAKERJAAN150416599021                          200000000116913862000006600000000000000000000000Test FANY816090000489KUCINGKUNCUNGBELANG10        INV123456783963011            Y000001000000000000001000000000000001000000000000001000000000000001600000000]

[ 0162    0078            0000    000210003006321030011095046396365000040320200 000000  080000 O.K.                                                                     ]
```