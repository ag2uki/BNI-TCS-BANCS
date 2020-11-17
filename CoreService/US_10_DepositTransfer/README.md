Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>API</systemId>
            <content xsi:type="bo:DepositTransferReq">
               <fromAccount>9870011691389501</fromAccount>
               <toAccount>114479721</toAccount>
               <amount>1</amount>
               <charge>0</charge>
               <currency>IDR</currency>
               <narative>aaaa</narative>
               <narativeExt/>
               <promoCode/>
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
            <header xmlns:ns0="bons">
               <coreJournal>904473</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage" xmlns:ns0="bons">
               <message>Bpk FAJAR NURCAHYO</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 1021                    **            003098600100001001045904473     0  I  0 000000  09870011691389501                  00000000000001000+            00000000114479721  000000                                                              IDR00000000000001000+IDR00000000000001000+00000000000000000+00000000000000000+02                                                                                                                                                                                                                                                                                                                                                                                       aaaa                                                                                                                                                                                                                                                                                                                      00000000000000000+]

[  0162    0078            0000    000000003098600100001001045904473000040320200 000000  080000 O.K.                 Bpk FAJAR NURCAHYO                                  ]
```