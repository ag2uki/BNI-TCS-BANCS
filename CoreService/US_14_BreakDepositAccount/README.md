Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:BreakDepositAccountReq">
               <depositAccNumber>114599786</depositAccNumber>
               <fromCurrency>IDR</fromCurrency>
               <balance>0</balance>
               <accNumber>0114462537</accNumber>
               <toCurrency>IDR</toCurrency>
               <flagPenalty>T</flagPenalty>
               <promoNo/>
               <description>pencairan rekening 00000000115397632</description>
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
               <coreJournal>463325</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>EUR 00008714005000000+ IDR 00000000590000000+ IDR 00000000590000000+</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0936                    **            003099600100001003045000000     0  I  0 000000  0000000011459978600000000000000000+                              00000000114462537    00                                            0000000000T         IDR00000000000000000+IDR00000000000000000+00000000000000000+00000000000000000+00     00000000000000000+00000000000000000+00000000000000000+                                                                                                                                                                                                                                                                                                                            pencairan rekening 00000000115397632                                                                                                                                                                                                                   ]

[ 0162    0078            0000    000000003099600100001003045463325000040320200 000000  080000 O.K. EUR 00008714005000000+ IDR 00000000590000000+ IDR 00000000590000000+]
```