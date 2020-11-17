Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body>
		<q0:transaction>
			<request>
				<systemId>IBANK</systemId>
				<content xsi:type="bo:AccountDetailsReq">
					<accountNum>0114462537</accountNum>
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
            <content xsi:type="bo:AccountDetailsRes">
               <accountProductType>DEP</accountProductType>
               <d_nomorRekening>11446253-7</d_nomorRekening>
               <d_currency>IDR</d_currency>
               <d_namaProduk>BNI TAPLUS</d_namaProduk>
               <d_cabangPembuka>0100</d_cabangPembuka>
               <d_kodeUser>..0.0.............1.</d_kodeUser>
               <d_statusRekening>BUKA</d_statusRekening>
               <d_jenisInvestasi>0000</d_jenisInvestasi>
               <d_kodeArea>0000</d_kodeArea>
               <d_kodeAgen/>
               <d_indNotifikasi>0</d_indNotifikasi>
               <d_indSurat>1</d_indSurat>
               <d_namaRekening/>
               <d_namaNasabah>Bpk JONOMADE MADEMADEMADEMADE IMAMADE</d_namaNasabah>
               <d_alamatNasabah_1>BENDI VII NO 14</d_alamatNasabah_1>
               <d_nominalBunga_1>0,00</d_nominalBunga_1>
               <d_alamatNasabah_2/>
               <d_nominalBunga_2>0,00</d_nominalBunga_2>
               <d_alamatNasabah_3>kebayoran</d_alamatNasabah_3>
               <d_nominalBunga_3>0,00</d_nominalBunga_3>
               <d_alamatNasabah_4>Kebayoran Baru</d_alamatNasabah_4>
               <d_kodePos>12120</d_kodePos>
               <d_nominalBunga_4>0,00</d_nominalBunga_4>
               <d_tglBukaRekening>31052010</d_tglBukaRekening>
               <d_tktBungaKredit>3,0000</d_tktBungaKredit>
               <d_tktBungaDebet>0,0000</d_tktBungaDebet>
               <d_nominalBunga_5>0,00</d_nominalBunga_5>
               <d_saldoAkhir>121.402.214.328,00</d_saldoAkhir>
               <d_tglJthTempoOverdraft>99/99/9999</d_tglJthTempoOverdraft>
               <d_nominalBlokir>0,00</d_nominalBlokir>
               <d_limitOverdraft>0</d_limitOverdraft>
               <d_danaBelumEfektif>0,00</d_danaBelumEfektif>
               <d_tambahanBunga>10105274,80516</d_tambahanBunga>
               <d_tglTrkhrKreditBunga>31052010</d_tglTrkhrKreditBunga>
               <d_bungaSaatTutupRek>0,00</d_bungaSaatTutupRek>
               <d_proyeksiBunga>10105274,80516</d_proyeksiBunga>
               <d_tglKreditBungaYad>31052010</d_tglKreditBungaYad>
               <d_pajakSaatTutupRek>0,00</d_pajakSaatTutupRek>
               <d_bungaTersedia>10144386,06341</d_bungaTersedia>
               <d_tglTrkhrUbahDetail>31052010</d_tglTrkhrUbahDetail>
               <d_relationshipManager/>
               <d_kodeBM_CSM/>
               <d_rateSesuai>0,0000</d_rateSesuai>
               <d_tglTrkhrUbahJenisRek>99999999</d_tglTrkhrUbahJenisRek>
               <d_nilaiBungaOverdraft>,00000</d_nilaiBungaOverdraft>
               <d_saldoEfektif>121.402.214.328,00</d_saldoEfektif>
               <d_profitTersedia>0</d_profitTersedia>
               <d_profitAkrual>0</d_profitAkrual>
               <d_numTeller>14937</d_numTeller>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0099                    **            003099600100001069440000000     0  I  0 000000  00000000114462537]

[  1042    0958            0000    000000003099600100001032001000000000040320400 000000  03          11446253-7IDRBNI TAPLUS                    0100..0.0.............1.BUKA00000000    01                                                            Bpk JONOMADE MADEMADEMADEMADE IMAMADE                       BENDI VII NO 14                                       0,00                                                       0,00 kebayoran                                             0,00 Kebayoran Baru                          12120                 0,00 31052010   3,0000 0,0000              0,00 121.402.214.328,00                    99/99/9999  1.699.453.381,00-              0,00              0              0,00     10105274,80516 31052010                0,00     10105274,80516 31052010                0,00     10144386,06341 31052010  00000                                                       00                     0                        0,000099999999              ,00000 121.402.214.328,00 SETOR 0                  0                  14937     ]
```