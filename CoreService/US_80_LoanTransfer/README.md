Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>BNIDIRECT</systemId>
            <content xsi:type="bo:LoanTransferReq">
               <fromAccount>0114445023</fromAccount>
               <fromCurrency>IDR</fromCurrency>
               <fromAmount>15000</fromAmount>
               <toAccount>0115471119</toAccount>
               <toCurrency>IDR</toCurrency>
               <toAmount>15000</toAmount>
               <promoNumber/>
               <narative>TEST Transfer Loan via SOA</narative>
               <baseAmount>500000</baseAmount>
               <rateType>02</rateType>
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
               <coreJournal>237834</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>N SANTOSA                               BEND ABIDI</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[  0739                    **            003098900100001011055000000     0  I  0 000000  0000000011444502300000000015000000+101                           00000000115471119                                                                      IDR00000000015000000+IDR00000000500000000+00000000000000000+00000000000000000+02                                                                                                                                                                                                                                                                                                                                                                                       TEST Transfer Loan via SOA                        ]

[  0162    0078            0000    000000003098900100001011055237834000040320200 000000  080000 O.K.       N SANTOSA                               BEND ABIDI            ]
```