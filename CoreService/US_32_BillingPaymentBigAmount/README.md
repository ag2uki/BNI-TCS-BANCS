Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>MHP</systemId>
            <content xsi:type="bo:BillingPaymentBigAmountReq">
               <billerCode>0061</billerCode>
               <regionCode>0002</regionCode> <!--IDR:0001, USD:0002-->
               <billerName>MPN G2 IDR</billerName>
               <cardNum>11041000000371024</cardNum>
               <cardName>IMIGRASI</cardName>
               <paymentMethod>2</paymentMethod>
               <accountNum>5550324</accountNum>
               <trxAmount>70000</trxAmount>
               <feeAmount>0</feeAmount>
               <naration>NARASI</naration>
               <invoiceNum>INV12345678</invoiceNum>
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
               <coreJournal>236574</coreJournal>
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
[ 0366                    **            003099299901001095050000000     0     0 000000  00610002MPN G2 IDR          11041000000371024 IMIGRASI            2000000000055503240000000007000000000000000000000000NARASI                                            INV12345678                    0000000000000000000000000000000000000000000000000000000000000000000000000000000000000]

[ 0162    0078            0000    000090003023309001001095050236574000040320200 000000  080000 O.K.                                                                     ]
```