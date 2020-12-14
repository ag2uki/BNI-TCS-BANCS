Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:GetPersonalInfoReq">
               <cifNum>9007944334</cifNum>
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
            <content xsi:type="bo:GetPersonalInfoRes">
               <cifNum>9007944334</cifNum>
               <name>Ibu 9007944334 9007944334 9007944334</name>
               <nameAlias/>
               <berdasarPPH>1</berdasarPPH>
               <cabangPbyrPajak/>
               <agama>1</agama>
               <lingkupPerusahaan/>
               <email1>aluyah222.teguh@yahoo.com</email1>
               <email2>aluyah.teguh2@yahoo.com</email2>
               <kreditur/>
               <kdPendidikan>3</kdPendidikan>
               <Channel1/>
               <Channel2/>
               <Channel3/>
               <Channel4/>
               <Channel5/>
               <Channel6/>
               <Channel7/>
               <Channel8/>
               <Channel9/>
               <Channel10/>
               <Channel11>1</Channel11>
               <Channel12>5</Channel12>
               <Channel13/>
               <Channel14/>
               <Channel15/>
               <Channel16/>
               <Channel17/>
               <Channel18/>
               <Channel19/>
               <Channel20/>
               <freq>M</freq>
               <siklus/>
               <hari/>
               <Mom_Maiden_Name>ALUYAH</Mom_Maiden_Name>
               <cdHobby/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0101                    **            003099600100001067050000000     0  I  0 000000  0000000900794433409]

[ 0402    0318            0000    000000003099600100001067108000000000040320600 000000  0300000009007944334Ibu 9007944334 9007944334 9007944334                                                      1000000001 aluyah222.teguh@yahoo.com                         aluyah.teguh2@yahoo.com                           0000000030000000000000000000001050000000000000000M0000 ALUYAH                                  00   ]
```