Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
	<soapenv:Body>
		<q0:transaction>
			<request>
				<systemId>SPCH2H</systemId>
				<customHeader>
					<branch>025900</branch>
					<terminal>385</terminal>
					<teller>50432</teller>
					<overrideFlag/>
					<supervisorId/>
					<systemJournal/>
				</customHeader>
				<content xsi:type="bo:BillPaymentReq" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
					<billerCode>0026</billerCode>
					<regionCode>8065</regionCode>
					<billerName>Universitas Terbuka</billerName>
					<cardNum>20080650432181942900</cardNum>
					<cardName>EQVUUS FAECIENTES</cardName>
					<paymentMethod>2</paymentMethod>
					<accountNum>115469111</accountNum>
					<trxAmount>3000000</trxAmount>
					<feeAmount>2500</feeAmount>
					<naration/>
					<invoiceNum>20080650432181942901</invoiceNum>
					<billId>20080650432181942901</billId>
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
					<coreJournal>156192</coreJournal>
				</header>
				<content xsi:type="bo:OKMessage">
					<message/>
				</content>
			</response>
		</core:transactionResponse>
	</soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0391 ** 003025938550432095043000000 0 0 000000 00268065Universitas Terbuka 200806504321819429EQVUUS FAECIENTES 200000000115469111000003000000000000002500 20080650432 20080650432181942901 ]

[ 0162 0078 0000 000385003025938550432095043156192000040320200 000000 080000 O.K. ]
```