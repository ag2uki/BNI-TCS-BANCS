Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SYARIAH</systemId>
            <content xsi:type="bo:InitLinkCardAccountReq">
               <accountNum>317210964</accountNum>
               <cardNum>5371762590015009</cardNum>
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
               <coreJournal>022635</coreJournal>
            </header>
            <content xsi:type="bo:InitLinkCardAccountRes">
               <cardNum>5371762590015009</cardNum>
               <cardDescription>BNI CARD GOLD</cardDescription>
               <cardName1>RESYA ISTINA</cardName1>
               <cardName2/>
               <cifNum>9344095963</cifNum>
               <name>RESYA ISTINA</name>
               <address1>KP. PD KOPI</address1>
               <address2>010 012</address2>
               <address3>KOTA SURAKARTA SELATAN</address3>
               <Address4>PONDOK KOPI</Address4>
               <postCode>15221</postCode>
               <related1>00000000</related1>
               <acctRel1/>
               <related2>00000000</related2>
               <acctRel2/>
               <related3>00000000</related3>
               <acctRel3/>
               <seqAddRel>00000001</seqAddRel>
               <acctAddRel>00000000317210964</acctAddRel>
               <acctAddRelDesc>SAVINGS ACCOUNT</acctAddRelDesc>
               <confirmFlag>Y</confirmFlag>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```