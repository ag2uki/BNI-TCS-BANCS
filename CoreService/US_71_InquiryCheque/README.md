Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body>
		<q0:transaction>
			<request>
				<systemId>NEWIBANK-CORE</systemId>
				<content xsi:type="bo:InquiryChequeReq">
					<accountNo>316035436</accountNo>
					<chequePrefix/>
					<chequeFirstNo/>
					<status/>
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
               <coreJournal>116305</coreJournal>
            </header>
            <content xsi:type="NS_BO:CompiledInquiryChequeRes" xmlns:NS_BO="http://service.bni.co.id/core/bo">
               <chequeInfo>
                  <chequeNo>BA200001</chequeNo>
                  <numberofCheques>00010</numberofCheques>
                  <status>I</status>
                  <availableCheque>00010</availableCheque>
                  <bookType>1010</bookType>
                  <branchCode>0001</branchCode>
                  <issuedDate>01112014</issuedDate>
               </chequeInfo>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```