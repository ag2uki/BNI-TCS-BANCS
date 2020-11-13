Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body>
		<q0:transaction>
			<request>
				<systemId>KAS_VALAS</systemId>
				<customHeader>
					<branch>259</branch>
					<terminal>763</terminal>
					<teller>15763</teller>
					<overrideFlag/>
					<tandemFlag/>
					<supervisorId/>
				</customHeader>
				<content xsi:type="bo:GLTransferGLReq">
					<fromAccount>0028840100002001</fromAccount>
					<amount1>160</amount1>
					<toAccount>0758840100009001</toAccount>
					<currency>USD</currency>
					<exchangeAmount>0</exchangeAmount>
					<exchangeCurrency>USD</exchangeCurrency>
					<baseAmount>5896</baseAmount>
					<commission>0</commission>
					<changeAmount>0</changeAmount>
					<rateType>5</rateType>
					<currVersion>00</currVersion>
					<narasi>Test Fany GL Transfer 20045</narasi>
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
               <coreJournal>556778</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```