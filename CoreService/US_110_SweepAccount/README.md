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
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header>
               <coreJournal>325346</coreJournal>
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
[ 0254                    **            003099600100001060422000000     0  I  0 000000                   000000000114444620   2501201826012018 00000000000000000+00000000000000000+00000000000000000+00000000000000000+00000000000000000+0         00000000114444619]

[ 0162    0078            0000    000000003099600100001060422325346000040320200 000000  080000 O.K.                                                                     ]
```