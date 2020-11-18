Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>API</systemId>
            <content xsi:type="bo:UpdateVARetailReq">
               <virtualAccountType>987</virtualAccountType>
               <companyCode>22222222220</companyCode>
               <virtualAccountNum>9872222222222001</virtualAccountNum>
               <virtualAccountName>Toped</virtualAccountName>
               <virtualAccountStatus>1</virtualAccountStatus>
               <billAmount>1000</billAmount >
               <var1Amount>2000</var1Amount>
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
               <coreJournal>240227</coreJournal>
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
[ 0370                    **            003098600100001031993000000     0  I  0 000000  A        987222222222200987222222222200100000000000000000                                         Toped                                                                           1000000000001000000+                    00000000000000000+00000000002000000+00000000000000000+                  ]

[ 0162    0078            0000    000000003098600100001031993240227000040320200 000000  080000 O.K.                                                                     ]
```