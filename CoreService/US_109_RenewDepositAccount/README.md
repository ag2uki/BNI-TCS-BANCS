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
				<systemId>NEWIBANK-CORE</systemId>
				<content xsi:type="bo:RenewDepositAccountReq">
					<accountNum>115340539</accountNum>
					<cif>9100130270</cif>
					<idNum>456.5656.565.1454</idNum>
					<idType>1</idType>
					<customerName>Sdri NAMA1 NAMA2</customerName>
					<address1>JALAN</address1>
					<address2 />
					<npwp>N</npwp>
					<address3>DESA</address3>
					<nationality>ID</nationality>
					<address4 />
					<postCode>13530</postCode>
					<accountType>2800</accountType>
					<subCategory>1</subCategory>
					<interestPaymentType>R</interestPaymentType>
					<accountAff/>
					<profilBebasDenda/>
					<language>4</language>
					<freqRekKoran>N</freqRekKoran>
					<prosesKonsolidasiRekKoran />
					<dateIndicator />
					<mailId>1</mailId>
					<noteIndicator>0</noteIndicator>
					<notifCustomer/>
					<intVariabel>0</intVariabel>
					<freqInt />
					<siklus />
					<day />
					<agentCode/>
					<investType/>
					<address5/>
					<indGroup/>
					<accntNumber5 />
					<idApplikasi/>
					<DefaultString19/>
					<DefaultString20/>
					<DefInteger7/>
					<DefInteger13/>
					<DefaultString21 />
					<Unsigned08>0</Unsigned08>
					<idGroupTier />
					<resikoDomestik>20</resikoDomestik>
					<resikoLintas />
					<accCrossBorder>ZZ</accCrossBorder>
					<indJaminan>B</indJaminan>
					<lmtJangkaWkt>ZZ</lmtJangkaWkt>
					<DefaultString18 />
					<kdGL>0259IDR00002100113101</kdGL>
					<tglBukaRek />
					<jmlCopy />
					<indProses>0</indProses>
					<indEkstrakRek />
					<rateSesuai>0</rateSesuai>
					<klausaValas>0</klausaValas>
					<valuta />
					<indPerubahanBungaRekKoran>Y</indPerubahanBungaRekKoran>
					<indHerTaksasi />
					<BrokerNo1 />
					<DefInteger8 />
					<tpr>0</tpr>
					<CertNo1 />
					<NoIns />
					<Insurance />
					<OpenAcctResason>0002</OpenAcctResason>
					<otherOpenAcctResason />
					<SrcOfFrund>0005</SrcOfFrund>
					<SrcOfFrund1>tessas</SrcOfFrund1>
					<ProjDep />
					<ProjWdl />
					<AcctRatio>0</AcctRatio>
					<BICNo/>
					<BICLimit>0</BICLimit>
					<InsuTerm>24</InsuTerm>
					<AutoClose>Y</AutoClose>
					<AutoPremium/>
					<MthPay>4000000.000</MthPay>
					<AddCover>20</AddCover>
					<AffiAcctNo>113020167</AffiAcctNo>
					<InsuAcctNo>1122337</InsuAcctNo>
					<PrincArrears>0</PrincArrears>
					<PremArrears>0</PremArrears>
				</content>
			</request>
		</q0:transaction>
	</soapenv:Body>
</soapenv:Envelope>
```

Sample SOAP Response
```
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/"
xmlns:xsd="http://www.w3.org/2001/XMLSchema"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xmlns:dpss0="bons">
	<soapenv:Header />
	<soapenv:Body>
		<core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo"
			xmlns:core="http://service.bni.co.id/core">
			<response>
				<header>
					<coreJournal>640406</coreJournal>
				</header>
				<content xsi:type="bo:OKMessage">
					<message />
				</content>
			</response>
		</core:transactionResponse>
	</soapenv:Body>
</soapenv:Envelope>
```