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
				<content xsi:type="bo:GLReversalTarikTunaiReq">
					<accountNum>259360209001351</accountNum>
					<amount>100</amount>	
					<promoNum>ZZ</promoNum>
					<currency>IDR</currency>
					<exchangeAmount>0</exchangeAmount>
					<exchangeCurrency>IDR</exchangeCurrency>
					<baseAmount>0</baseAmount>
					<commission>0</commission>
					<changeAmount>0</changeAmount>
					<rateType/>
					<currVersion/>
					<journalNum>550113</journalNum>
					<segmentCode/>
					<narasi>testing  reversal 20160</narasi>
					<bookingNum/>
				</content>
			</request>
		</q0:transaction>
	</soapenv:Body>
</soapenv:Envelope>
```

Sample SOAP Response
```
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
    <soapenv:Header />
    <soapenv:Body>
        <core:transactionResponse xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
            <response>
                <header>
                    <coreJournal>550114</coreJournal>
                </header>
                <content xsi:type="bo:OKMessage">
                    <message></message>
                </content>
            </response>
        </core:transactionResponse>
    </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0935                    **            003099200100001020160000000     0  I  0 000000  0025936020900135100000000000100000+                                                                                ZZ                                  IDR00000000000000000+IDR00000000000000000+00000000000000000+00000000000000000+00    550113                                                                                                                                                                                                                                                                                                                                                                             testing  reversal 20160                                                                                                                                                                                                                                ]

[ 0162    0078            0000    00    003099200100001020160550114000040320200 000000  080000 O.K.                                                                     ]
```