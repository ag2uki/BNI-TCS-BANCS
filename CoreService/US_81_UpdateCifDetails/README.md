Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body>
		<q0:transaction>
			<request>
				<systemId>NEWIBANK-CORE</systemId>
				<content xsi:type="bo:UpdateCifDetailsReq">
					<cifNum>9100130666</cifNum>
					<customerType>01</customerType>
					<relManager />
					<salutation>02</salutation>
					<firstName>MAHATMA</firstName>
					<lastName>DANDI</lastName>
					<title />
					<companyName />
					<lawFirm />
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
					<faxNum1 />
					<faxNum2 />
					<officePhoneNum1 />
					<officePhoneNum2 />
					<cellPhoneNum1 />
					<cellPhoneNum2 />
					<nationality>ID</nationality>
					<occupancy />
					<languageCode>04</languageCode>
					<idNum>1234567890</idNum>
					<idReleasedDate>24052009</idReleasedDate>
					<idReleasedFrom>Jakarta</idReleasedFrom>
					<idType>0001</idType>
					<domesticRisk>16</domesticRisk>
					<borderRisk />
					<vipCode />
					<status>000</status>
					<segmentCode>3100</segmentCode>
					<hasNPWP />
					<openingBranch>00718</openingBranch>
					<yesNo1>N</yesNo1>
					<yesNo2>N</yesNo2>
					<yesNo3>N</yesNo3>
					<yesNo4>N</yesNo4>
					<yesNo5>N</yesNo5>
					<bisnisRiskCode>9990</bisnisRiskCode>
					<countryOfRiskCode />
					<countryOfRiskCode2 />
					<centralBankOwnershipCode>9000</centralBankOwnershipCode>
					<corporateGroupCode>9999</corporateGroupCode>
					<middleName />
					<locationCode>0102</locationCode>
					<bebasPPH>N</bebasPPH>
					<ivrFlag />
					<idExpiryDate>2013-05-24</idExpiryDate>
				</content>
			</request>
		</q0:transaction>
	</soapenv:Body>
</soapenv:Envelope>
```

Sample SOAP Response
```
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
	<soapenv:Header />
	<soapenv:Body>
		<core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
			<response>
				<header>
					<coreJournal>686092</coreJournal>
				</header>
				<content xsi:type="bo:OKMessage">
					<message />
				</content>
			</response>
		</core:transactionResponse>
	</soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0695 ** 003099600100001067000000000 0 I 0 000000 00000009100130666010000002MAHATMA DANDI PAMULANG 1 1 1 PAMULANG SUITE Pamulang PAMULANG MERDEKA 15417 ID021 123456 ID 041234567890 24052009Jakarta 000116 000031000000718NNNNN9990 9000 9999 0102N 24052013 ]

[ 0162 0078 0000 000000003099600100001067000288145000040320200 000000 080000 O.K. ]
```