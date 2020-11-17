Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SYARIAH</systemId>
            <content xsi:type="bo:DepositTransferReversalReq">
               <fromAccount>9870011691389501</fromAccount>
               <toAccount>114479721</toAccount>
               <amount>1</amount>
               <charge>0</charge>
               <currency>IDR</currency>
               <narative>aaaa</narative>
               <narativeExt/>
               <journalNum>904473</journalNum>
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
               <coreJournal>396477</coreJournal>
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
[ 1021                    **            003099299901001001145000000     0  I  0 000000  09870011691389501                  00000000000001000+            00000000114479721    0000                                                              IDR00000000000001000+IDR00000000000001000+00000000000000000+00000000000000000+02    904473                                                                                                                                                                                                                                                                                                                                                                             aaaa                                                                                                                                                                                                                                                                                                                      00000000000000000+]

[  0162    0078            0000    000000003099299901001001145396477000040320200 000000  080000 O.K.                 Bpk FAJAR NURCAHYO                                  ]
```