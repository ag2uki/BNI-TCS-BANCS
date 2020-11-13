Sample SOAP Request
```
<soapenv:Envelope
	xmlns:q0="http://service.bni.co.id/core"
	xmlns:bo="http://service.bni.co.id/core/bo"  
	xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
	xmlns:xsd="http://www.w3.org/2001/XMLSchema"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body> 
		<q0:transaction>
			<request>
				<systemId>SMS</systemId>
				<content xsi:type="bo:CustomerSearchReq">
					<firstName>MADE</firstName>
					<startFromRecordNum>0</startFromRecordNum>
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
					<coreJournal>000000</coreJournal>
				</header>
				<content xsi:type="bo:CompiledCustomerSearchRes" xmlns:b0="http://service.bni.co.id/core/bo">
					<customerInfo>
						<fullName>Bpk MADE RIMBAWA PURNATAPA</fullName>
						<cifNum>9100201641</cifNum>
						<addressType>TETAP</addressType>
						<address>JL GANDARIA SELATAN BLOK ABC NO 44 0224</address>
					</customerInfo>
					<lastRecordNum>1</lastRecordNum>
				</content>
			</response>
		</core:transactionResponse>
	</soapenv:Body>
</soapenv:Envelope>
```