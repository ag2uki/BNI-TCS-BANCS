# 69400

Transaction code 69400 is known as `AccountShortInquiry` and `AccountShortDetails`

1. AccountShortInquiry
Sample SOAP Request:
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
Sample SOAP Response:
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

Bancs format message:
```
[ 0100                    **
         003099600100001069400000000     0  I  0 000000  000000001152104198]
		 
[ 1067    0983            0000    000000003099600100001000400000000000040320600 000000  0300000000115210419IDRBUKA              BNI TAPLUS                    025900000009100131831Sdr ARIEL PETERCORN

                       38.823.880,00      38.823.880,00 31052010JL. PEUYEUM  BANDUNG NO. 666                                                    Kenyot                                  BOJONG
  10320                           JL. PEUYEUM  BANDUNG NO. 666
                                        Kenyot
      BOJONG                                  10320
    D20000001              0,00               0,00               0,00  2,0000


                          00                        ]
```

2. AccountShortDetails
Sample SOAP Request :
```xml
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:AccountShortDetailsReq">
               <accountNum>116913895</accountNum>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>
```

Sample SOAP Response :
```xml
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header>
               <coreJournal>000000</coreJournal>
            </header>
            <content xsi:type="bo:AccountShortDetailsRes">
               <accountProductType>DEP</accountProductType>
               <d_accountNum>116913895</d_accountNum>
               <d_accountCurrency>IDR</d_accountCurrency>
               <d_status>BUKA</d_status>
               <d_branchNum>0718</d_branchNum>
               <d_accountType>EMERALD SAVING</d_accountType>
               <d_accountTypeCode>2301</d_accountTypeCode>
               <d_accountSubcatCode>0001</d_accountSubcatCode>
               <d_metodeHitungBunga>DDCV</d_metodeHitungBunga>
               <d_tingkatSukuBunga>0,0000</d_tingkatSukuBunga>
               <d_accountName>Bpk MUHAMAD JUHARDI</d_accountName>
               <d_customerName>Bpk SATRIA SAMBRAMA</d_customerName>
               <d_homePhoneNum>021 11218292</d_homePhoneNum>
               <d_officePhoneNum/>
               <d_tanggalPembukaan>31/05/2010</d_tanggalPembukaan>
               <d_tanggalMaintainTerakhir>31/05/2010</d_tanggalMaintainTerakhir>
               <d_tanggalTransaksiFinansial>31/05/2010</d_tanggalTransaksiFinansial>
               <d_tanggalBungaSebelumnya>01/03/2016</d_tanggalBungaSebelumnya>
               <d_tanggalBungaBerikutnya>31/03/2016</d_tanggalBungaBerikutnya>
               <d_tanggalKadaluarsaVisa/>
               <d_saldoAkhir>1.075.280.828,00</d_saldoAkhir>
               <d_danaBelumEfektif>0,00</d_danaBelumEfektif>
               <d_nominalBelumDicetak>1.075.280.828,00</d_nominalBelumDicetak>
               <d_bungaPerProvitHariIni>,00000</d_bungaPerProvitHariIni>
               <d_saldoBuku>0,00</d_saldoBuku>
               <d_nominalTanpaBunga>,00000</d_nominalTanpaBunga>
               <d_saldoAkibatInflasi>0</d_saldoAkibatInflasi>
               <d_adjBungaSebelumnya>,00000</d_adjBungaSebelumnya>
               <d_orderBukuCek/>
               <d_term/>
               <d_bungaSampaiHariIni>0,00</d_bungaSampaiHariIni>
               <d_tanggalOverlimitTerakhir>99/99/9999</d_tanggalOverlimitTerakhir>
               <d_pphPendudukSampaiHariIni>0</d_pphPendudukSampaiHariIni>
               <d_pphNonPendudukSampaiHariIni>0</d_pphNonPendudukSampaiHariIni>
               <d_bungaTunaiTersedia/>
               <d_visaPembelian/>
               <d_bicNum></d_bicNum>
               <d_frekuensiRekeningKoran>M</d_frekuensiRekeningKoran>
               <d_siklusRekeingKoran/>
               <d_hariRekeningKoran/>
               <d_alasanBukaRekening>0007</d_alasanBukaRekening>
               <d_alasanBukaRekening2/>
               <d_sumberDana>0001</d_sumberDana>
               <d_sumberDana2/>
               <d_perkiraanNominalSetoran>22.0</d_perkiraanNominalSetoran>
               <d_perkiraanNominalPenarikan>00.000,00</d_perkiraanNominalPenarikan>
               <d_tanggalProsesBukaRekening>31/05/2010</d_tanggalProsesBukaRekening>
               <d_kodeKlafikasiGl>0718IDR00002100113100</d_kodeKlafikasiGl>
               <d_perubahanTerakhirRekeninIni>99/99/9999</d_perubahanTerakhirRekeninIni>
               <d_nominalBungaOverdraft>,00000</d_nominalBungaOverdraft>
               <d_tprRate>000000</d_tprRate>
               <d_nomorSertifikat/>
               <d_provitAvailable>0</d_provitAvailable>
               <d_userIdPembukaRekening/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format Message :
```
[ 0100                    **            003099600100001069400000000     0  I  0 000000  00000000116913895 ]

[ 1063    0979            0000    000000003099600100001032000000000000040320600 000000  0300000000116913895   IDRBUKA              0718EMERALD SAVING                23010001DDCV               0,0000Bpk MUHAMAD JUHARDI                                         Bpk SATRIA SAMBRAMA                                         021 11218292            31/05/201031/05/201031/05/201001/03/201631/03/2016            1.075.280.828,00               0,00   1.075.280.828,00             ,00000               0,00             ,00000 0                              ,00000                         0,00 99/99/99990                  0                                                                                                                                                                                       M00000007                    0001                                   22.000.000,00               0,00     0031/05/20100718IDR00002100113100    99/99/9999            ,00000 0000107528082800000000625280828000       000000          0                  00000000000000000000019437]
```