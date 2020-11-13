Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body>
		<q0:transaction>
			<request>
				<systemId>NEWIBANK</systemId>
				<content xsi:type="bo:SweepAccountReq">
					<sweepType>0</sweepType>
					<accountPartnerNum>00000000114444620</accountPartnerNum>
					<startDate>25012018</startDate>
					<endDate>26012018</endDate>
					<cycle/>
					<balanceSpecifiedAmount>0</balanceSpecifiedAmount>
					<balanceResultsAmount>0</balanceResultsAmount>
					<maxLimitAmount>0</maxLimitAmount>
					<accumulationLimitAmount>0</accumulationLimitAmount>
					<priority>0</priority>
					<individualCurrentAccNum>00000000114444619</individualCurrentAccNum>
				</content>
			</request>
		</q0:transaction>
	</soapenv:Body>
</soapenv:Envelope>
```

Sample SOAP Response
```
<?xml version="1.0" encoding="UTF-8"?>
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:dpss0="bons" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/">
	<soapenv:Body>
		<core:transactionResponse xmlns:core="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo">
			<response>
				<header>
					<coreJournal>631666</coreJournal>
				</header>
				<content xsi:type="bo:OKMessage">
					<message/>
				</content>
			</response>
		</core:transactionResponse>
	</soapenv:Body>
</soapenv:Envelope>
```