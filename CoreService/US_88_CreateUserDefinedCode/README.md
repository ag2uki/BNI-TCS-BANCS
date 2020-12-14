Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>AGREGATOR</systemId>
            <content xsi:type="bo:CreateUserDefinedCodeReq">
               <accntNumber1>9100216433</accntNumber1>
               <defaultString>qazwsx</defaultString>
               <userCode2122/>
               <teroris>T</teroris>
               <defaultString3a/>
               <defaultString3b/>
               <defaultString4a/>
               <defaultString4b/>
               <defaultString4c/>
               <defaultString5a/>
               <defaultString5b/>
               <defaultString6a/>
               <defaultString6b/>
               <defaultString6c/>
               <hubdgBank/>
               <badanHukum/>
               <riskLevel/>
               <jenisOpr/>
               <tawarProduk>1</tawarProduk>
               <shareDataPri>1</shareDataPri>
               <defaultString7h/>
               <defaultString7i>T</defaultString7i>
               <defaultString7j/>
               <defaultString8a>11</defaultString8a>
               <defaultString8b>04</defaultString8b>
               <defaultString8c/>
               <defaultString8d>00</defaultString8d>
               <defaultString8e>0</defaultString8e>
               <defaultString9a/>
               <defaultString9b/>
               <defaultString9c/>
               <defaultString9d/>
               <defaultString9e/>
               <defaultString10a/>
               <defaultString10b/>
               <defaultString10c/>
               <defaultString10d/>
               <defaultString10e/>
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
               <coreJournal>585875</coreJournal>
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
[ 0199                    **            003099200100001067044000000     0  I  0 000000  00000009100216433qazwsx                T                                          11 T 1104  000                     ]

[ 0162    0078            0000    000000003099200100001067044289984000040320200 000000  080000 O.K.                                                                     ]
```