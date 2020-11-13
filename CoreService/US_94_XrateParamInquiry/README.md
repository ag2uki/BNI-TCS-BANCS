Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo"  	xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema"	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body> 
		<q0:transaction>
			<request>
				<systemId>XRATE</systemId>
				<content xsi:type="bo:XRateParamInquiryReq">
					<code>SGD</code>
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
					<coreJournal>063115</coreJournal> 
				</header>
				<content xsi:type="bo:XRateParamInquiryRes">
					<fungsi>E</fungsi> 
					<institusi>3</institusi> 
					<code>SGD</code> 
					<tanggal>2010-05-31</tanggal> 
					<waktu>18462155</waktu> 
					<satuanKurs>1</satuanKurs> 
					<kursValutaLain>1.0000</kursValutaLain> 
					<midRate>6568.0000</midRate> 
					<initUpdate>N</initUpdate> 
					<rateType_1>1</rateType_1> 
					<rateDesc_1>BANK NOTES</rateDesc_1> 
					<rateVariant_1>%</rateVariant_1> 
					<rateMaxVariant_1>90.000</rateMaxVariant_1> 
					<rateBuy_1>6403.0000</rateBuy_1> 
					<rateSell_1>8500.0000</rateSell_1> 
					<rateTierFlag_1>N</rateTierFlag_1> 
					<rateType_2>2</rateType_2> 
					<rateDesc_2>REGULAR</rateDesc_2> 
					<rateVariant_2>%</rateVariant_2> 
					<rateMaxVariant_2>10.000</rateMaxVariant_2> 
					<rateBuy_2>6490.0000</rateBuy_2> 
					<rateSell_2>6643.0000</rateSell_2> 
					<rateTierFlag_2>N</rateTierFlag_2> 
					<rateType_3>3</rateType_3> 
					<rateDesc_3>NONREGULAR</rateDesc_3> 
					<rateVariant_3>%</rateVariant_3> 
					<rateMaxVariant_3>10.000</rateMaxVariant_3> 
					<rateBuy_3>6490.0000</rateBuy_3> 
					<rateSell_3>6643.0000</rateSell_3> 
					<rateTierFlag_3>N</rateTierFlag_3> 
					<rateType_4>4</rateType_4> 
					<rateDesc_4>MID TRS</rateDesc_4> 
					<rateVariant_4>A</rateVariant_4> 
					<rateMaxVariant_4>0</rateMaxVariant_4> 
					<rateBuy_4>6568.0000</rateBuy_4> 
					<rateSell_4>6568.0000</rateSell_4> 
					<rateTierFlag_4>N</rateTierFlag_4> 
					<rateType_5>5</rateType_5> 
					<rateDesc_5>TRS BN</rateDesc_5> 
					<rateVariant_5>%</rateVariant_5> 
					<rateMaxVariant_5>10.000</rateMaxVariant_5> 
					<rateBuy_5>6493.0000</rateBuy_5> 
					<rateSell_5>6643.0000</rateSell_5> 
					<rateTierFlag_5>N</rateTierFlag_5> 
					<versionFrom>D9VR</versionFrom> 
					<versionFileFrom>D9VR</versionFileFrom> 
					<indikatorSatuan>M</indikatorSatuan> 
				</content>
			</response>
		</core:transactionResponse>
	</soapenv:Body>
</soapenv:Envelope>
```