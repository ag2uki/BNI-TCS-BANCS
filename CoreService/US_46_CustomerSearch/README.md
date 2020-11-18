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

Bancs Format
```
[24/09/20 11:42:38,521] ICONSConne INFO 438fc53977634d22b8904bfaa550f9ff Data sent to ICONS : [ 0110 ** 003098700100001060465000000 0 I 0 000000 1231231231235234 0001]

[ 0564 0480 0000 000000003098700100001060465251781000040320000 000000 03 01 1000000001-7 MICHAEL RONALDO 14081969 M S 0002 10000001-8 DEP 10000002-9 DEP 10000003-0 DEP 10000004-1 DEP 10000005-2 DEP 10000006-3 DEP 10000007-4 DEP 11480168-3 DEP 11480215-5 DEP 11480216-6 DEP 1148039-2 DEP TGLHR ( ) SEX ( ) MARITAL ( ) PEK ( ) Create ]
```