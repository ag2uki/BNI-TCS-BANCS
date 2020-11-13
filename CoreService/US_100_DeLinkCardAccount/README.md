Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>VCN</systemId>
            <content xsi:type="bo:DeLinkCardAccountReq">
              <cardNum>5269210600000038</cardNum>
               <cardDescription>BNI Debit Galeri Lafayette</cardDescription>
               <nameInCard1>Test-2 BNI 6</nameInCard1>
               <nameInCard2/>
               <cifNum>9284943401</cifNum>
               <name>ARILLULSYAH IBRAHIM FAJAR 12 34</name>
               <address1>BEKASI</address1>
               <address2/>
               <address3>bekasi</address3>
               <address4>Abang</address4>
               <postCode>80852</postCode>
               <account1>00000001</account1>
               <accountNum1>00000000315613669</accountNum1>
               <account2>00000000</account2>
               <accountNum2/>
               <account3>00000000</account3>
               <accountNum3/>
               <deLinkCardAccount>00000000315613669</deLinkCardAccount>
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
               <coreJournal>024294</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>O.K.</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```