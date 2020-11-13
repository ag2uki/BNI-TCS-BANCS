Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>IREM</systemId>
            <content xsi:type="bo:CreateCIFReq">
               <cifNum/>
               <customerType>01</customerType>
               <relManager/>
               <title>02</title>
               <firstName>Juan</firstName>
               <lastName>Daniel</lastName>
               <gelar/>
               <companyName/>
               <legalEntity/>
               <adrress1>Jalan Mawar Melati</adrress1>
               <address2>003009Sentosa</address2>
               <address3>Cengkareng Barat</address3>
               <address4>Cengkareng         /Jakarta Barat</address4>
               <zipCode>11730</zipCode>
               <countryCode/>
               <homePhone1>0021</homePhone1>
               <homePhone2>745454545</homePhone2>
               <noFax1/>
               <noFax2/>
               <officePhone1/>
               <officePhone2/>
               <handPhone1>0812323232</handPhone1>
               <handPhone2>0812323232</handPhone2>
               <nationality>ID</nationality>
               <occupant/>
               <languageCode/>
               <idNumber>331234766887878577</idNumber>
               <buildDate/>
               <publisherCity>Jakarta Barat</publisherCity>
               <idType>0001</idType>
               <jobCode>01</jobCode>
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
               <dateOfBirth>26111980</dateOfBirth>
               <gender>M</gender>
               <isMaried>L</isMaried>
               <motherName>Dina Maryati</motherName>
               <income>6</income>
               <frekuensi>M</frekuensi>
               <religion>2</religion>
               <education>07</education>
               <email>juan.daniel@gmail.com</email>
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
               <coreJournal>790492</coreJournal>
            </header>
            <content xsi:type="bo:CreateCIFRes">
               <message>O.K. 003        915055711-2 0990 001 00555</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```