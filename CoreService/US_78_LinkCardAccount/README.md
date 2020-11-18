Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>KIOSK</systemId>
            <content xsi:type="bo:LinkCardAccountReq">
               <cardNum>5264222590517835</cardNum>
               <cardDescription>Virtual MCI Silver - KANIA</cardDescription>
               <cardName1>FAJAR  NURCAHYO</cardName1>
               <cardName2/>
               <cifNum>9100751913</cifNum>
               <name>FAJAR  NURCAHYO</name>
               <address1>JALAN EBONY NO. 99</address1>
               <address2>9999KOMPLEK BUDIMAN SENTOSA</address2>
               <address3>Tanah Sareal</address3>
               <address4>Tanah Sereal       /Bogor</address4>
               <postCode>16161</postCode>
               <related1>00000000</related1>
               <acctRel1/>
               <related2>00000000</related2>
               <acctRel2/>
               <related3>00000000</related3>
               <acctRel3/>
               <seqAddRel>00000001</seqAddRel>
               <acctAddRel>00000000114479721</acctAddRel>
               <acctAddRelDesc>SAVINGS ACCOUNT</acctAddRelDesc>
               <confirmFlag>Y</confirmFlag>
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
               <coreJournal>396610</coreJournal>
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
[ 0613                    **            003099600100001037601000000     0  I  0 000000  00005264222590517835Virtual MCI Silver - KANIA    FAJAR  NURCAHYO                                                       00000009100751913   FAJAR  NURCAHYO                         JALAN EBONY NO. 99                      9999KOMPLEK BUDIMAN SENTOSA             Tanah Sareal                            Tanah Sereal       /Bogor               16161     00000000                      00000000                      00000000                                                    00000001  00000000114479721   SAVINGS ACCOUNT               Y]

[ 0162    0078            0000    000000003099600100001037601396610000040320200 000000  080000 O.K.                                                                     ]
```