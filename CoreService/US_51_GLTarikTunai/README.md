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
				<systemId>KAS</systemId>
				<customHeader>
					<branch>0996</branch>
					<terminal>001</terminal>
					<teller>00001</teller>
					<overrideFlag>I</overrideFlag>
					<tandemFlag/>
					<supervisorId/>
				</customHeader>
				<content xsi:type="bo:GLTarikTunaiReq">
					<accountNum>259360209001351</accountNum>
					<amount>150</amount>	
					<promoNum>ZZ</promoNum>
					<currency>IDR</currency>
					<exchangeAmount>0</exchangeAmount>
					<exchangeCurrency>IDR</exchangeCurrency>
					<baseAmount>0</baseAmount>
					<commission>0</commission>
					<changeAmount>0</changeAmount>
					<rateType/>
					<currVersion/>
					<segmentCode/>
					<narasi>testing 20060 lagi</narasi>
					<bookingNum/>
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
               <coreJournal>093941</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```