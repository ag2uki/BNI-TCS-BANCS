Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SYARIAH</systemId>
            <content xsi:type="bo:CreateCIFReq">
               <cifNum/>
               <customerType>01</customerType>
               <relManager/>
               <title>01</title>
               <firstName>Kapten</firstName>
               <lastName>Johanson</lastName>
               <gelar/>
               <companyName/>
               <legalEntity/>
               <adrress1>Jalan Kembang Mawar</adrress1>
               <address2>003009Sentosa</address2>
               <address3>Tanjung Duren Utara</address3>
               <address4>Grogol /Jakarta Barat</address4>
               <zipCode>11470</zipCode>
               <countryCode/>
               <homePhone1>0281</homePhone1>
               <homePhone2>12329853</homePhone2>
               <noFax1/>
               <noFax2/>
               <officePhone1/>
               <officePhone2/>
               <handPhone1>0856</handPhone1>
               <handPhone2>085674831294569</handPhone2>
               <nationality>ID</nationality>
               <occupant/>
               <languageCode/>
               <idNumber>331234766337812300</idNumber>
               <buildDate/>
               <publisherCity>Jakarta Barat</publisherCity>
               <idType>0001</idType>
               <jobCode>02</jobCode>
               <BorderRisk1/>
               <vipCode/>
               <status/>
               <BISegmentCode>3100</BISegmentCode>
               <lockerHolder/>
               <optNPWP>1</optNPWP>
               <branchOpening/>
               <optCustomer/>
               <optIdCustomer/>
               <optIndustry/>
               <optCountry/>
               <optSector/>
               <sectorCode/>
               <countryOfRisk/>
               <affiliationCode/>
               <BIOwnerCode>9000</BIOwnerCode>
               <companyGroup>9999</companyGroup>
               <middleName/>
               <locationCode>0102</locationCode>
               <bebasPph>Y</bebasPph>
               <IVRFlag/>
               <idDueDate>26102016</idDueDate>
               <placeOfBirth>Semarang</placeOfBirth>
               <dateOfBirth>26111956</dateOfBirth>
               <gender>M</gender>
               <isMaried>L</isMaried>
               <motherName>Ratu Johanson</motherName>
               <income>6</income>
               <frekuensi>M</frekuensi>
               <religion>2</religion>
               <education>07</education>
               <email>kapten.johanson@gmail.com</email>
               <NPWPNum/>
               <SIUPNum/>
               <SIUPDueDate/>
               <TDPNum/>
               <TDPDueDate/>
               <kitasNum/>
               <kitasDueDate/>
               <BNISegmentCode/>
               <RMCode/>
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
               <coreJournal>298660</coreJournal>
            </header>
            <content xsi:type="bo:CreateCIFRes">
               <message>O.K. 003       1000000896-9 0992 999 01001</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[0967                    **            003099299901001063001000000     0  I  0 000000  00000000000000000010000001Kapten                                  Johanson                                                                                                                Jalan Kembang Mawar                     003009Sentosa                           Tanjung Duren Utara                     Grogol /Jakarta Barat                   11470     028112329853                                    ID 00331234766337812300              Jakarta Barat                 000102  00003100 100000                9000 9999                                        0102Y 26102016Semarang                      26111956MLRatu Johanson                           000000000000006M207kapten.johanson@gmail.com                         0000000000000000                                                                                                           0856085674831294569                     ]

[0121    0037            0000    000000003099299901001063001298660000040320000 000000  03003 000000010000008969 0992 999 010010000 O.K. 003       1000000896-9 0992 999 01001                               ]
```