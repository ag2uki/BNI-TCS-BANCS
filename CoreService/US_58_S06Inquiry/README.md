Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body>
		<q0:transaction>
			<request>
				<systemId>CASHPICKUP</systemId>
				<content xsi:type="bo:S06InquiryReq">
					<refferenceNum>S06ITR2000387720</refferenceNum>
					<counterAdvis>ITR000287</counterAdvis>
					<status>1</status>
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
               <coreJournal>021459</coreJournal>
            </header>
            <content xsi:type="bo:S06InquiryRes">
               <refferenceNum>S06ITR2000387720</refferenceNum>
               <counterAdvis>ITR000287</counterAdvis>
               <trxDate>2015-11-01</trxDate>
               <trxStatus>1</trxStatus>
               <remmAmount>10000.000</remmAmount>
               <remmAmountCurrency>IDR</remmAmountCurrency>
               <trxCharges>4.000</trxCharges>
               <refundCharge>0</refundCharge>
               <rateType>03</rateType>
               <beneficiaryAccount>317123718</beneficiaryAccount>
               <beneficiaryName>DEKOETJING LTD.</beneficiaryName>
               <beneficiaryAddress/>
               <senderName>1/OEKO-INSTITUT. INSTITUT FUER</senderName>
               <senderAddress>1/ANGEWANDTE OEKOLOGIE E.V. 2/MERZHAUSER STR. 173 3/DE/79100 FREIBURG IM BREISGAU</senderAddress>
               <accountNum>317123718</accountNum>
               <accountName>Bpk NADEP123 NATENG123 NABEL123</accountName>
               <accountCurrency>IDR</accountCurrency>
               <nonSTPReason>BEN NAME UNMATCH</nonSTPReason>
               <naration>INVOICE 01/30/2019</naration>
               <senderBank>LANDESBANK BADEN-WuRTTEMBERG</senderBank>
               <coveringBank>DEUTDEFFXXX</coveringBank>
               <coverRefference>190301AZ00026181</coverRefference>
               <coverAccount>317100155</coverAccount>
               <branchNum>0259</branchNum>
               <debitAccountNum>317100155</debitAccountNum>
               <creditAccountNum>317123718</creditAccountNum>
               <chargeType>SHA</chargeType>
               <amdCharges>0</amdCharges>
               <xtrCharges>0</xtrCharges>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```