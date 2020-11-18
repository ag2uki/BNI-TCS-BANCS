Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo"  	xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema"	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body> 
		<q0:transaction>
			<request>
				<systemId>NEWIBANK-CORE</systemId>
				<content xsi:type="bo:CifDetailsReq">
					<cifNum>9144751232</cifNum>
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
            <content xsi:type="bo:CifDetailsRes">
               <cifNum>9144751232</cifNum>
               <customerType>01</customerType>
               <relManager/>
               <salutation>02</salutation>
               <firstName>SHERLOCK</firstName>
               <lastName>HOLMES</lastName>
               <title>SIR</title>
               <companyName/>
               <lawFirm/>
               <jalan>BAKER STREET</jalan>
               <rt/>
               <rw/>
               <perumahan/>
               <kelurahan>Kebun Bunga</kelurahan>
               <kecamatan>Kalijati</kecamatan>
               <postCode>41271</postCode>
               <countryCode/>
               <homePhoneNum1/>
               <homePhoneNum2/>
               <faxNum1/>
               <faxNum2/>
               <officePhoneNum1/>
               <officePhoneNum2/>
               <nationality>ID</nationality>
               <occupancy/>
               <languageCode>04</languageCode>
               <idNum/>
               <idReleasedDate/>
               <idReleasedFrom/>
               <idType>0000</idType>
               <domesticRisk>00</domesticRisk>
               <borderRisk/>
               <vipCode/>
               <status>000</status>
               <segmentCode>3100</segmentCode>
               <hasNPWP>1</hasNPWP>
               <openingBranch>00259</openingBranch>
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
               <ivrFlag>0</ivrFlag>
               <idExpiryDate>0000-00-00</idExpiryDate>
               <cellPhoneNum1/>
               <cellPhoneNum2/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0101                    **            003099600100001067050000000     0  I  0 000000  0000000914475123201]

[ 0738    0654            0000    000000003099600100001067000000000000040320600 000000  0300000009144751232010000002SHERLOCK                                HOLMES                        SIR                                                                                       BAKER STREET                                                                    Kebun Bunga                             Kalijati                                41271                                                     ID 04                                                              000000  00003100N100259NNNNN9990       9000                                         09999                                        0102N0                                                ]
```