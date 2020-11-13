Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
	<soapenv:Body>
		<q0:transaction>
			<request>
				<systemId>SPCH2H</systemId>
				<customHeader>
					<branch>0997</branch>
					<terminal>002</terminal>
					<teller>00004</teller>
					<overrideFlag>4</overrideFlag>
					<supervisorId/>
				</customHeader>
				<content xsi:type="bo:AtmBillPaymentReq" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
					<accountNum>116901551</accountNum>
					<amount>3000000</amount>
					<billerCode>0026</billerCode>
					<regionCode>8065</regionCode>
					<naration/>
					<invoiceNum>12345678901234567834</invoiceNum>
					<atmTrxDate>04072020</atmTrxDate>
					<atmTrxTime>172346</atmTrxTime>
					<atmRefference>8486</atmRefference>
					<atmCardNum>6010047180002756</atmCardNum>
					<atmMerchant>BANK NEGARA INDONESIA JAKARTA DKIID</atmMerchant>
					<atmTerminal>S1CGEDEBGT</atmTerminal>
					<atmAddress>SUNTER 0259005</atmAddress>
					<billCustomerName>EQVUUS FAECIENTES</billCustomerName>
					<billInvoiceNum1>INVNUM1</billInvoiceNum1>
					<billAmount1>0</billAmount1>
					<billInvoiceNum2>INVNUM2</billInvoiceNum2>
					<billAmount2>0</billAmount2>
					<billInvoiceNum3>INVNUM3</billInvoiceNum3>
					<billAmount3>0</billAmount3>
					<flag/>
					<amount1>0.000</amount1>
					<amount2>0.000</amount2>
					<amount3>0.000</amount3>
					<amount4>0.000</amount4>
					<amount5>0.000</amount5>
					<billId>12345678901234567834</billId>
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
					<coreJournal>156207</coreJournal>
				</header>
				<content xsi:type="bo:AtmBillPaymentRes">
					<message>R00000100300000000156568703D2020080616442066000000091373374780082754559541633025+82754559541633025+</message>
				</content>
			</response>
		</core:transactionResponse>
	</soapenv:Body>
</soapenv:Envelope>
```