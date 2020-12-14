Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>BNIDIRECT</systemId>
            <content xsi:type="bo:TaxFileNumReq">
               <cifNum>9100191653</cifNum>
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
               <coreJournal>567152</coreJournal>
            </header>
            <content xsi:type="bo:TaxFileNumRes">
               <cifNum>9100191653</cifNum>
               <customerName>Bpk ALI ZAMZAM</customerName>
               <accountNum/>
               <investorTypeCode>I</investorTypeCode>
               <taxFileNum>0000000000000000</taxFileNum>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[  0179                    **            003098900100001060050000000     0  I  0 000000  00000009100191653                                                            00000000000000000   ]

[ 0214    0130            0000    000000003098900100001060051281082000040320600 000000  0300000009100191653Bpk ALI ZAMZAM                                              00000000000000000   123456789123456 I0000000000000000]
```