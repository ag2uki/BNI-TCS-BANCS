# 067050

Transaction code 067050 is being used by 2 services
- GetPersonalInfo
- CifDetails

## GetPersonalInfo

`GetPersonalInfo` is 067050 with option set to `09`. The response is `067108.xml`

request :
```xml
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:GetPersonalInfoReq">
               <cifNum>9021096442</cifNum>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>
```

response :
```xml
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header>
               <coreJournal>000000</coreJournal>
            </header>
            <content xsi:type="bo:GetPersonalInfoRes">
               <cifNum>9021096442</cifNum>
               <name>Sdri ING NGARSO SUNG TULODHO JER BASUKI MOWO BEYO</name>
               <nameAlias>LULUK HARINI</nameAlias>
               <berdasarPPH/>
               <cabangPbyrPajak/>
               <agama>1</agama>
               <lingkupPerusahaan/>
               <email1/>
               <email2/>
               <kreditur/>
               <kdPendidikan>5</kdPendidikan>
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
               <Mom_Maiden_Name>SUPARTIANA</Mom_Maiden_Name>
               <cdHobby/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

```
[ 0101                    **
           003099600100001067050000000     0  I  0 000000  0000000910085331409]

[ 0402    0318            0000
000000003099600100001067108000000000040320600 000000  0300000009100853314Bpk RICK ALFREDO SANCHEZ                                    SANCHEZ
               0000000001 fajarsyairillah51@gmail.com
                                                    0000000060000000000000000000000000000000000000000 0000 JAKARTA                                 00   ]
```

## CifDetails

CifDetails is 67050 with option set to `01`. The response is `067000.xml`

SOAP request sample:
```xml
<soapenv:Envelope
	xmlns:q0="http://service.bni.co.id/core"
	xmlns:bo="http://service.bni.co.id/core/bo"  
	xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
	xmlns:xsd="http://www.w3.org/2001/XMLSchema"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body> 
<q0:transaction>
  <request>
    <systemId>NEWIBANK-CORE</systemId>
  <content xsi:type="bo:CifDetailsReq">
    <cifNum>9100130666</cifNum>
  </content>
  </request>
</q0:transaction>
</soapenv:Body>
</soapenv:Envelope>
```

SOAP response sample:
```xml
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
	<soapenv:Header/>
	<soapenv:Body>
		<core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
			<response>
				<header>
					<coreJournal>000000</coreJournal>
				</header>
				<content xsi:type="bo:CifDetailsRes">
					<cifNum>9100130666</cifNum>
					<customerType>01</customerType>
					<relManager/>
					<salutation>02</salutation>
					<firstName>MAHATMA</firstName>
					<lastName>DANDI</lastName>
					<title/>
					<companyName/>
					<lawFirm/>
					<jalan>PAMULANG 1</jalan>
					<rt>1</rt>
					<rw>1</rw>
					<perumahan>PAMULANG SUITE</perumahan>
					<kelurahan>Pamulang</kelurahan>
					<kecamatan>PAMULANG MERDEKA</kecamatan>
					<postCode>15417</postCode>
					<countryCode>ID</countryCode>
					<homePhoneNum1>021</homePhoneNum1>
					<homePhoneNum2>123456</homePhoneNum2>
					<faxNum1/>
					<faxNum2/>
					<officePhoneNum1/>
					<officePhoneNum2/>
					<nationality>ID</nationality>
					<occupancy/>
					<languageCode>04</languageCode>
					<idNum>1234567890</idNum>
					<idReleasedDate>24052009</idReleasedDate>
					<idReleasedFrom>Jakarta</idReleasedFrom>
					<idType>0001</idType>
					<domesticRisk>16</domesticRisk>
					<borderRisk/>
					<vipCode/>
					<status>000</status>
					<segmentCode>3100</segmentCode>
					<hasNPWP/>
					<openingBranch>00718</openingBranch>
					<yesNo1>N</yesNo1>
					<yesNo2>N</yesNo2>
					<yesNo3>N</yesNo3>
					<yesNo4>N</yesNo4>
					<yesNo5>N</yesNo5>
					<bisnisRiskCode>9990</bisnisRiskCode>
					<countryOfRiskCode/>
					<countryOfRiskCode2/>
					<centralBankOwnershipCode>9000</centralBankOwnershipCode>
					<corporateGroupCode>9999</corporateGroupCode>
					<middleName/>
					<locationCode>0102</locationCode>
					<bebasPPH>N</bebasPPH>
					<ivrFlag/>
					<idExpiryDate>2013-05-24</idExpiryDate>
					<cellPhoneNum1/>
					<cellPhoneNum2/>
				</content>
			</response>
		</core:transactionResponse>
	</soapenv:Body>
</soapenv:Envelope>
```

Bancs Format message:
```
[ 0101                    **            003099600100001067050000000     0  I  0 000000  0000000910013066601]

[ 0738    0654            0000    000000003099600100001067000000000000040320600 000000  0300000009100130666010000002MAHATMA
                           DANDI
                                                                         PAMULANG 1                              1  1  PAMULANG SUITE
     Pamulang                                PAMULANG MERDEKA
           15417   ID021 123456                                      ID 041234567890              24052009Jakarta                       000116  000031000000718NNNNN9990       9000                                         09999                                        0102N 24052013
                       ]
```