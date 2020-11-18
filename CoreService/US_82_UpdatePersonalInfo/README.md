Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:UpdatePersonalInfoReq">
               <cifNum>9144772525</cifNum>
               <name>Sdri DIAN AMALIA PONGDATU</name>
               <nameAlias>PONGDATU</nameAlias>
               <berdasarPPH/>
               <cabangPbyrPajak/>
               <agama>2</agama>
               <lingkupPerusahaan/>
               <email1>dian.pongdatu@mail.com</email1>
               <email2/>
               <kreditur/>
               <kdPendidikan/>
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
               <Channel11/>
               <Channel12/>
               <Channel13/>
               <Channel14/>
               <Channel15/>
               <Channel16/>
               <Channel17/>
               <Channel18/>
               <Channel19/>
               <Channel20/>
               <freq/>
               <siklus/>
               <hari/>
               <Mom_Maiden_Name>MAMA</Mom_Maiden_Name>
               <cdHobby/>
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
               <coreJournal>240182</coreJournal>
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
[ 0397                    **            003099600100001067108000000     0  I  0 000000  00000009144772525Sdri DIAN AMALIA PONGDATU                                   PONGDATU                      0000000002 dian.pongdatu@mail.com                                                                              0000000000000000000000000000000000000000000000000 0000 MAMA                                    00]

[ 0162    0078            0000    000000003099600100001067108240182000040320200 000000  080000 O.K.                                                                     ]
```