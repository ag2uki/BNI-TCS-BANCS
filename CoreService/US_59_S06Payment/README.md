Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo"  	xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" 	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body> 
		<q0:transaction>
			<request>
				<systemId>CASHPICKUP</systemId>
				<content xsi:type="bo:S06PaymentReq">
					<refferenceNum>S06ITR2000387720</refferenceNum>
					<counterAdvis>ITR000287</counterAdvis>
					<remmAmount>10000.000</remmAmount>
					<remmAmountCurrency>IDR</remmAmountCurrency>
					<trxCharges>4.000</trxCharges>
					<refundCharge>0</refundCharge>
					<creditAmount>7222730</creditAmount>
					<creditAmountCurrency>IDR</creditAmountCurrency>
					<baseAmount>7222730</baseAmount>
					<creditAccountNum>317100155</creditAccountNum>
					<rateType>3</rateType>
					<debitRate>8945</debitRate>
					<creditRate>1</creditRate>
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
               <coreJournal>021509</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```