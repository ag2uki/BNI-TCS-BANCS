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