Sample SOAP Request
```
<NS1:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:NS1="http://schemas.xmlsoap.org/soap/envelope/">
	<NS1:Body>
		<q0:transaction>
			<request>
				<systemId>XRATE</systemId>
				<customHeader>
					<branch>0766</branch>
					<terminal>028</terminal>
					<teller>00777</teller>
					<overrideFlag>I</overrideFlag>
					<tandemFlag/>
				</customHeader>
				<content xsi:type="bo:XRateParamUpdateReq">
					<code>SGD</code>
					<tanggal>2010-05-31</tanggal>
					<waktu>09545214</waktu>
					<satuanKurs>1</satuanKurs>
					<kursValutaLain>1.0000</kursValutaLain>
					<midRate>95</midRate>
					<rateType_1>1</rateType_1>
					<rateDesc_1>BANK NOTES</rateDesc_1>
					<rateVariant_1>%</rateVariant_1>
					<rateMaxVariant_1>90.000</rateMaxVariant_1>
					<rateBuy_1>100</rateBuy_1>
					<rateSell_1>90</rateSell_1>
					<rateTierFlag_1>N</rateTierFlag_1>
					<rateType_2>2</rateType_2>
					<rateDesc_2>REGULAR</rateDesc_2>
					<rateVariant_2>%</rateVariant_2>
					<rateMaxVariant_2>10.000</rateMaxVariant_2>
					<rateBuy_2>120</rateBuy_2>
					<rateSell_2>130</rateSell_2>
					<rateTierFlag_2>N</rateTierFlag_2>
					<rateType_3>3</rateType_3>
					<rateDesc_3>NONREGULAR</rateDesc_3>
					<rateVariant_3>%</rateVariant_3>
					<rateMaxVariant_3>10.000</rateMaxVariant_3>
					<rateBuy_3>120</rateBuy_3>
					<rateSell_3>130</rateSell_3>
					<rateTierFlag_3>N</rateTierFlag_3>
					<rateType_4>4</rateType_4>
					<rateDesc_4>MID TRS</rateDesc_4>
					<rateVariant_4>A</rateVariant_4>
					<rateMaxVariant_4>0</rateMaxVariant_4>
					<rateBuy_4>120</rateBuy_4>
					<rateSell_4>130</rateSell_4>
					<rateTierFlag_4>N</rateTierFlag_4>
					<rateType_5>5</rateType_5>
					<rateDesc_5>TRS BN</rateDesc_5>
					<rateVariant_5>%</rateVariant_5>
					<rateMaxVariant_5>10.000</rateMaxVariant_5>
					<rateBuy_5>120</rateBuy_5>
					<rateSell_5>130</rateSell_5>
					<rateTierFlag_5>N</rateTierFlag_5>
					<indikatorSatuan>M</indikatorSatuan>
					<versionFrom>DA1T</versionFrom>
					<versionFileFrom>DA1T</versionFileFrom>
				</content>
			</request>
		</q0:transaction>
	</NS1:Body>
</NS1:Envelope>
```

Sample SOAP Response
```
<soapenv:Envelope xmlns:dpss0="bons" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
	<soapenv:Header/>
	<soapenv:Body>
		<core:transactionResponse xmlns:core="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo">
			<response>
				<header>
					<coreJournal>051639</coreJournal>
				</header>
				<content xsi:type="bo:OKMessage">
					<message/>
				</content>
			</response>
		</core:transactionResponse>
	</soapenv:Body>
</soapenv:Envelope>
```