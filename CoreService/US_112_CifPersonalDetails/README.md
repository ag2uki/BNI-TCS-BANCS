Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>API</systemId>
            <content xsi:type="bo:CifPersonalDetailsReq">
               <cifNum>9100749959</cifNum>
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
               <coreJournal>000000</coreJournal>
            </header>
            <content xsi:type="bo:CifPersonalDetailsRes">
               <cifNum>9100749959</cifNum>
               <customerName>Bpk JUAN DANIEL</customerName>
               <birthDate>26111980</birthDate>
               <gender>M</gender>
               <marriageStatus>L</marriageStatus>
               <dependents>00</dependents>
               <nationality>ID</nationality>
               <employer/>
               <startWorkDate>00000000</startWorkDate>
               <workAddress1/>
               <occupationInfo/>
               <occupationCode>1</occupationCode>
               <birthPlace>Semarang</birthPlace>
               <workAddress2/>
               <postalCode/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0101                    **            003098600100001067050000000     0  I  0 000000  0000000910074995905]

[ 1002    0918            0000    000000003098600100001067101000000000040320600 000000  0300000009100749959Bpk JUAN DANIEL                                             26111980ML00ID                                                            00000000                                                            0001Semarang                                                            000000000000000                                                                                                                                                                                                                                                                                                                                                                                           00000000                                                                                                                                                                                                                                 ]
```