# 69400

Transaction code 69400 is known as `AccountShortInquiry`

SOAP request sample:
```xml
<soapenv:Envelope
	xmlns:q0="http://service.bni.co.id/core"
	xmlns:bo="http://service.bni.co.id/core/bo"  
	xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
	xmlns:xsd="http://www.w3.org/2001/XMLSchema"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body> 
<q0:transaction>
  <request>
    <systemId>IBANK</systemId>
  <content xsi:type="bo:AccountShortInquiryReq">
    	<accountNum>00000000115210419</accountNum>
    	<options>8</options>
  </content>
  </request>
</q0:transaction>
</soapenv:Body>
</soapenv:Envelope>
```
SOAP Response:
```xml
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
	<soapenv:Header/>
	<soapenv:Body>
		<core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
			<response>
				<header/>
				<content xsi:type="bo:AccountShortInquiryRes">
					<d_accountNum>00000000115210419</d_accountNum>
					<d_currency>IDR</d_currency>
					<d_status>BUKA</d_status>
					<d_product>BNI TAPLUS</d_product>
					<d_homeBranch>0259</d_homeBranch>
					<d_cifNum>00000009100131831</d_cifNum>
					<d_name>Sdr ARIEL PETERCORN</d_name>
					<d_nameRek/>
					<d_currentBalance>38.823.880,00</d_currentBalance>
					<d_availableBalance>38.823.880,00</d_availableBalance>
					<d_openDate>2010-05-31</d_openDate>
					<d_address1>JL. PEUYEUM  BANDUNG NO. 666</d_address1>
					<d_address2/>
					<d_address3>Kenyot</d_address3>
					<d_address4>BOJONG</d_address4>
					<d_postCode>10320</d_postCode>
					<d_homePhone/>
					<d_mobilePhone/>
					<d_address1AA>JL. PEUYEUM  BANDUNG NO. 666</d_address1AA>
					<d_address2AA/>
					<d_address3AA>Kenyot</d_address3AA>
					<d_address4AA>BOJONG</d_address4AA>
					<d_postCodeAA>10320</d_postCodeAA>
					<d_homePhoneAA/>
					<d_mobilePhoneAA/>
					<accountProductType>DEP</accountProductType>
					<d_accType>2000</d_accType>
					<d_subCat>0001</d_subCat>
					<d_availableInterest>0,00</d_availableInterest>
					<d_lienBalance>0,00</d_lienBalance>
					<d_unclearBalance>0,00</d_unclearBalance>
					<d_interestRate>2,0000</d_interestRate>
				</content>
			</response>
		</core:transactionResponse>
	</soapenv:Body>
</soapenv:Envelope>
```