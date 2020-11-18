Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SMS</systemId>
            <content xsi:type="bo:GLSetoranTunaiReq">
               <accountNum>259360209001351</accountNum>
               <trxAmount>100</trxAmount>
               <additionalInformation/>
               <promoNum>ZZ</promoNum>
               <currency>IDR</currency>
               <amountExchangeRate>0</amountExchangeRate>
               <currencyExchangeRate/>
               <baseAmount>0</baseAmount>
               <kursType>0</kursType>
               <narasi>testing setoran tunai</narasi>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>
```

Sample SOAP Response
```
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header>
               <coreJournal>590190</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>O.K.</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[0935                    **            003099200100001020010000000     0  I  0 000000  0025936020900135100000000000100000+                                                                                ZZ                                  IDR00000000000000000+   00000000000000000+00000000000000000000000000000000000000                                                                                                                                                                                                                                                                                                                                                                                       testing setoran tunai                                                                                                                                                                                                                                  ]

[ 0162    0078            0000    00    003099200100001020010590190000040320200 000000  080000 O.K.                                                                     ]
```