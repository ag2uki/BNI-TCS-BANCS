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

Bancs Format
```
[ 1031 ** 003099100100001001045900070 0 I 0 000000 00000000112233440 00000000000001000+ 00000000113020167 000000 USD00000000013485000+IDR00000000013485000+00000000000000000+00000000000000000+02 TRF Deposit-Deposit USD-IDR TRF Dep-Dep Cross Currency 00000000000000000+0000000000]

[ 0162 0078 0000 000000003099100100001001045900070000040320200 000000 080000 O.K. Sdri NAMA1 NAMA2 ]
```