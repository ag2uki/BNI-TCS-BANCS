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
    	<accountNum>114537297</accountNum>
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
					<l_accountNum>00000000114537297</l_accountNum>
					<l_currency>IDR</l_currency>
					<l_status>SEBAGIAN</l_status>
					<l_product>BNI INSTAN KMK EFF IDR</l_product>
					<l_homeBranch>0265</l_homeBranch>
					<l_cifNum>00000009100751913</l_cifNum>
					<l_name>Bpk FAJAR NURCAHYO</l_name>
					<l_nameRek/>
					<l_currentBalance>88.655.471,00</l_currentBalance>
					<l_availableBalance>88.655.471,00</l_availableBalance>
					<l_openDate>2010-05-31</l_openDate>
					<l_address1>JALAN EBONY NO. 99</l_address1>
					<l_address2>9999. KOMPLEK BUDIMAN SENTOSA</l_address2>
					<l_address3>Tanah Sareal</l_address3>
					<l_address4>Tanah Sereal</l_address4>
					<l_postCode>16161</l_postCode>
					<l_homePhone>02518369696</l_homePhone>
					<l_mobilePhone>085648078731</l_mobilePhone>
					<l_address1AA>JALAN EBONY NO. 99</l_address1AA>
					<l_address2AA>9999. KOMPLEK BUDIMAN SENTOSA</l_address2AA>
					<l_address3AA>Tanah Sareal</l_address3AA>
					<l_address4AA>Tanah Sereal</l_address4AA>
					<l_postCodeAA>16161</l_postCodeAA>
					<l_homePhoneAA>02518369696</l_homePhoneAA>
					<l_mobilePhoneAA>085648078731</l_mobilePhoneAA>
					<accountProductType>LON</accountProductType>
					<l_accType>1950</l_accType>
					<l_subCat>0701</l_subCat>
					<l_interestRate>14,0000</l_interestRate>
					<l_term>012</l_term>
					<l_affiliateAccount>00000000000000000</l_affiliateAccount>
					<l_maturityDate>2011-05-30</l_maturityDate>
					<l_approvedDate>2010-05-31</l_approvedDate>
					<l_approved>100.000.000,00</l_approved>
					<l_advanced>0,00</l_advanced>
					<l_installmentAmount>0,00</l_installmentAmount>
					<l_overdueAmount>-11.344.529,00</l_overdueAmount>
					<l_balance>-11.344.529,00</l_balance>
					<l_principalOverdue>00000</l_principalOverdue>
					<l_remRepayment>012</l_remRepayment>
					<l_nextInstallmentDueDate>00</l_nextInstallmentDueDate>
				</content>
			</response>
		</core:transactionResponse>
	</soapenv:Body>
</soapenv:Envelope>
```

```
[ 0100                    **
         003099600100001069400000000     0  I  0 000000  000000001145372978]

[ 0914    0830            0000    000000003099600100001010400000000000040320600 000000  0300000000114537297IDRSEBAGIAN          BNI INSTAN KMK EFF IDR        026500000009100751913Bpk FAJAR NURCAHYO

                       88.655.471,00      88.655.471,00 31052010JALAN EBONY NO. 99                      9999. KOMPLEK BUDIMAN SENTOSA           Tanah Sareal                            Tanah Sereal
  16161   02518369696 085648078731JALAN EBONY NO. 99
9999. KOMPLEK BUDIMAN SENTOSA           Tanah Sareal
      Tanah Sereal                            16161   02518369696 085648078731B1950070114,0000012000000000000000003005201131052010    100.000.000,00
               0,00               0,00      11.344.529,00-     11.344.529,00-00000              01200085648078731        ]
```