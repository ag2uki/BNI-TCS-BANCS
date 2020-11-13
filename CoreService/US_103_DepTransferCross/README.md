Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body>
		<q0:transaction>
			<request>
				<systemId>NEWMOBILE</systemId>
				<content xsi:type="bo:DepTransferCrossReq">
					<fromAccount>112233440</fromAccount>
					<currency>USD</currency>
					<debitAmount>1</debitAmount>
					<toAccount>113020167</toAccount>
					<amount>13485</amount>
					<creditCurr>IDR</creditCurr>
					<rateType>02</rateType>
					<baseAmount>13485</baseAmount>
					<narative>TRF Deposit-Deposit USD-IDR</narative>
					<narativeExt>TRF Dep-Dep Cross Currency</narativeExt>
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
				<header xmlns:ns0="bons">
					<coreJournal>900070</coreJournal>
				</header>
				<content xsi:type="bo:OKMessage" xmlns:ns0="bons">
					<message>Sdri NAMA1 NAMA2</message>
				</content>
			</response>
		</core:transactionResponse>
	</soapenv:Body>
</soapenv:Envelope>
```