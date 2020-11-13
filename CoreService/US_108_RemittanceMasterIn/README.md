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
				<systemId>GLOBS</systemId>
				<content xsi:type="bo:RemittanceMasterInReq">
					<transactionCode>PMT</transactionCode>
					<refferenceNum>S06ITR0001270517</refferenceNum>
					<counterAdvis>JPU002943</counterAdvis>
					<transactionType>CRD</transactionType>
					<transactionDate>${today}</transactionDate>
					<transactionCurrency>IDR</transactionCurrency>
					<senderBank>JPU</senderBank>
					<toBank/>
					<bicCover>BNINPIN1XXX</bicCover>
					<bicKIR>BNINPIN1XXX</bicKIR>
					<correspondentReff>084565413</correspondentReff>
					<beneficiaryName>Made</beneficiaryName>
					<beneficiaryAddress1/>
					<beneficiaryAddress2/>
					<beneficiaryAddress3>54494</beneficiaryAddress3>
					<senderName>Rimbawa</senderName>
					<senderAddress1/>
					<senderAddress2/>
					<news1>54</news1>
					<news2/>
					<detailCharge>OUR</detailCharge>
					<remittanceAmount>770000.00</remittanceAmount>
					<chargeAmount>45000</chargeAmount>
					<refundChargeAmount>11200</refundChargeAmount>
					<coverAccount>${taplus1}</coverAccount>
					<amdCharges>70</amdCharges>
					<xtrCharges>60</xtrCharges>
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
					<coreJournal>623342</coreJournal>
				</header>
				<content xsi:type="bo:RemittanceMasterInRes">
					<responseResult>0</responseResult>
					<journalNumber>623342</journalNumber>
					<responseDateTime>3105201011:15:28</responseDateTime>
					<errorCode>0000</errorCode>
					<errorDesc>TRX ALREADY EXIST</errorDesc>
					<stp>GGL</stp>
					<nonstpDesc/>
					<account>000000000000000</account>
					<accountName/>
					<homeBranch>000</homeBranch>
					<currency/>
					<remitAmount>0</remitAmount>
				</content>
			</response>
		</core:transactionResponse>
	</soapenv:Body>
</soapenv:Envelope>
```