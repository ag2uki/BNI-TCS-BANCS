Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo"  	xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema"	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body> 
		<q0:transaction>
			<request>
				<systemId>NEWIBANK-CORE</systemId>
				<content xsi:type="bo:DepositDetailsReq">
					<accountNum>555010</accountNum>
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
               <coreJournal>000000</coreJournal>
            </header>
            <content xsi:type="bo:DepositDetailsRes">
               <accountNum>555010</accountNum>
               <cifNum>9100130666</cifNum>
               <idNumber>1234567890</idNumber>
               <idType>1</idType>
               <customerName>Ibu MAHATMA  DANDI</customerName>
               <address1>PAMULANG 1</address1>
               <address2>1  1  PAMULANG SUITE</address2>
               <hasNPWP>N</hasNPWP>
               <address3>Pamulang</address3>
               <citizenCountryCode>ID</citizenCountryCode>
               <address4>PAMULANG MERDEKA</address4>
               <postCode>15417</postCode>
               <accountTypeCode>2000</accountTypeCode>
               <accountSubcatCode>1</accountSubcatCode>
               <interestPaymentMethodCode>R</interestPaymentMethodCode>
               <affiliatedAccountNum></affiliatedAccountNum>
               <profilBebasBiaya></profilBebasBiaya>
               <frekuensiRekeningKoran>N</frekuensiRekeningKoran>
               <konsolidasiRekeningKoran/>
               <calenderCode/>
               <indikatorSuratMenyurat>1</indikatorSuratMenyurat>
               <indikatorPemberitahuan>0</indikatorPemberitahuan>
               <pemberitahunanKeNasabah></pemberitahunanKeNasabah>
               <rateBungaVariabel>0</rateBungaVariabel>
               <frekuensiBunga/>
               <siklusRekeningKoran/>
               <tanggalHariRekeningKoran/>
               <jenisInvestasi></jenisInvestasi>
               <nomorFasilitas/>
               <kreditRating></kreditRating>
               <jangkaWaktu></jangkaWaktu>
               <termBasis/>
               <nominalDeposito>0</nominalDeposito>
               <jenisTierRate/>
               <domesticRiskCode>16</domesticRiskCode>
               <crossBorderRiskCode>ZZ</crossBorderRiskCode>
               <borderRiskCode>ZZ</borderRiskCode>
               <indikatorSekuriti>B</indikatorSekuriti>
               <limitJangkaWaktu>ZZ</limitJangkaWaktu>
               <vostroIdBank/>
               <glClasificationCode>0718IDR00002100113100</glClasificationCode>
               <jumlahCopyRekeningKoran/>
               <indikatorProsesPemberitahuan>0</indikatorProsesPemberitahuan>
               <indikatorEkstraksiRekening/>
               <rateSesuai>0</rateSesuai>
               <indikatorPerubahanRekeningKoran>Y</indikatorPerubahanRekeningKoran>
               <indikatorTaksasi/>
               <alasanBukaRekening>0006</alasanBukaRekening>
               <alasanBukaRekeningLainnya/>
               <sumberDana>0001</sumberDana>
               <sumberDanaLainnya/>
               <projectedDepositPerMonth>10000000</projectedDepositPerMonth>
               <projectedWithdrawalPerMonth>9000000</projectedWithdrawalPerMonth>
               <accountRatio>0</accountRatio>
               <bicNum></bicNum>
               <bicLimit>0</bicLimit>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```