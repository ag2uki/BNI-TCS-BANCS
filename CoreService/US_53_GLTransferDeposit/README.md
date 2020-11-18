Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>PERSEKOT</systemId>
            <customHeader>
               <branch>259</branch>
               <terminal>763</terminal>
               <teller>15763</teller>
               <overrideFlag/>
               <tandemFlag/>
               <supervisorId/>
            </customHeader>
            <content xsi:type="bo:GLTransferDepositReq">
               <nonGLAccountNum>115476582</nonGLAccountNum>
               <glAmount>25500</glAmount>
               <glAcccountNum>0259360200001004</glAcccountNum>
               <extNarration>Ext Narration</extNarration>
               <glCurrency>IDR</glCurrency>
               <nonGlAmount>25500</nonGlAmount>
               <nonGlCurrency>IDR</nonGlCurrency>
               <baseAmount>25500</baseAmount>
               <exchangeRateType>02</exchangeRateType>
               <narration>Narration</narration>
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
               <coreJournal>571668</coreJournal>
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
[ 0939 ** 003025976315763021051000000 0 0 000000 00000000115476582 00000000025500000+ 00000000 00259360200001004 Ext Narration IDR00000000025500000+IDR00000000025500000+00000000000000000+00000000000000000+02 00 00 Narration00000000000000000000000000000000000000000 ]

[ 0162 0078 0000 000763003025976315763021051288127000040320200 000000 080000 O.K. ]
```