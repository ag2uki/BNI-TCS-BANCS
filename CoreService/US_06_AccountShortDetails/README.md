Sample SOAP Request
```
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