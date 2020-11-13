Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>KIOSK</systemId>
            <content xsi:type="bo:InitDeLinkCardAccountReq">
               <cardNum>5326682590000395</cardNum>
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
               <coreJournal>237823</coreJournal>
            </header>
            <content xsi:type="bo:InitDeLinkCardAccountRes">
               <cardNum>5326682590000395</cardNum>
               <cardDescription>BNI EMERALD CARD IDR</cardDescription>
               <nameInCard1>SHERLOCK  HOLMES</nameInCard1>
               <nameInCard2/>
               <cifNum>9144751232</cifNum>
               <name>SHERLOCK  HOLMES</name>
               <address1>BAKER STREET</address1>
               <address2/>
               <address3>Kebun Bunga</address3>
               <address4>Kalijati</address4>
               <postCode>41271</postCode>
               <account1>00000001</account1>
               <accountNum1>00000000115409515</accountNum1>
               <account2>00000000</account2>
               <accountNum2/>
               <account3>00000000</account3>
               <accountNum3/>
               <deLinkCardAccount>00000000000000000</deLinkCardAccount>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```