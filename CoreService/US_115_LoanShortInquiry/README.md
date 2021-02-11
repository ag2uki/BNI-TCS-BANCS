Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" 
xmlns:bo="http://service.bni.co.id/core/bo" 
xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" 
xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>FSCM</systemId>
            <content xsi:type="bo:LoanShortInquiryReq">
               <accountNum>114537297</accountNum>
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
            <content xsi:type="bo:LoanShortInquiryRes">
               <accountNum>11453729-7</accountNum>
               <currency>IDR</currency>
               <status>SEBAGIAN</status>
               <noCab>0265</noCab>
               <jenisRekening>BNI INSTAN KMK EFF IDR</jenisRekening>
               <accountTypeCode>1950</accountTypeCode>
               <accountSubcatCode>0701</accountSubcatCode>
               <jkWkt>012</jkWkt>
               <unitPengelola>1040</unitPengelola>
               <refDischarge/>
               <remRepay>012</remRepay>
               <namaRekening/>
               <namaNasabah>Bpk FAJAR NURCAHYO</namaNasabah>
               <kodeKlasifikasiGL>0265IDR00001400053101</kodeKlasifikasiGL>
               <aplikasi>100.000.000,00</aplikasi>
               <saldo>88.710.471,00</saldo>
               <apprvd>100.000.000,00</apprvd>
               <advd>0,00</advd>
               <commi>0,00</commi>
               <unearn>0,00</unearn>
               <earn>0,00</earn>
               <angsrn>0,00</angsrn>
               <tgkOrDispbl>11.289.529,00-</tgkOrDispbl>
               <npb>88.710.471,00</npb>
               <bngAkum>,00000</bngAkum>
               <excsAkum>,00000</excsAkum>
               <ciac>,00000</ciac>
               <bngHrn>34498,51650</bngHrn>
               <excsHrn>,00000</excsHrn>
               <ciin>156,79901</ciin>
               <addLoan>0</addLoan>
               <tktSukuBng>014,0000</tktSukuBng>
               <noBunga>0,00</noBunga>
               <lstArrDte>9999-99-99</lstArrDte>
               <insu>0,00</insu>
               <repaymentRate>14,0000</repaymentRate>
               <arin>0,00</arin>
               <tglPersetujuan>2010-05-31</tglPersetujuan>
               <tglTransFinansialAkhir>2010-05-31</tglTransFinansialAkhir>
               <tglMaintainAkhir>2010-05-31</tglMaintainAkhir>
               <tglAdvTerakhir>2010-05-31</tglAdvTerakhir>
               <tglMulaiJthTmp>2010-05-31</tglMulaiJthTmp>
               <jenisRepayment>00000</jenisRepayment>
               <tglTundaJthTmp>9999-99-99</tglTundaJthTmp>
               <tundaJthTmp>0,00</tundaJthTmp>
               <badDebtIndic>00</badDebtIndic>
               <intax>0,00</intax>
               <dwnBayar>0,00</dwnBayar>
               <theo>100.000.000,00</theo>
               <bungaPrepayStrt>0000-00-00</bungaPrepayStrt>
               <bungaPrepayExp>0000-00-00</bungaPrepayExp>
               <iPAmt>0000000000000000</iPAmt>
               <frekRekKoran>M</frekRekKoran>
               <siklus>00</siklus>
               <minCEVLinked>00</minCEVLinked>
               <indktrRedraw/>
               <dndAkum>,00000</dndAkum>
               <dndHrn>,00000</dndHrn>
               <noBooking/>
               <optPolicyDate>9999-99-99</optPolicyDate>
               <optPolicy>N</optPolicy>
               <tanggalJatuhTempo>2011-05-30</tanggalJatuhTempo>
               <bankShare/>
               <sisaGP>000</sisaGP>
               <minReqCevLinked/>
               <perbhnJenisRek>9999-99-99</perbhnJenisRek>
               <redraw>0,00</redraw>
               <rekArr>,00000</rekArr>
               <dasarPerhitungan>M</dasarPerhitungan>
               <payday/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0100                    **            003098900100099010400000000     0  I  0 000000  000000001145372971]

[ 1067    0983            0000    000000003098900100099032100000000000040320600 000000  03          11453729-7IDRSEBAGIAN          0265BNI INSTAN KMK EFF IDR        195007010121040    012                                                            Bpk FAJAR NURCAHYO                                          0265IDR00001400053101        100.000.000,00      88.710.471,00     100.000.000,00               0,00               0,00               0,00               0,00               0,00      11.289.529,00-     88.710.471,00             ,00000             ,00000             ,00000        34498,51650             ,00000          156,79901 0014,0000              0,00 99999999              0,00 14,0000              0,00 310520103105201031052010310520103105201000000 99999999              0,00 00              0,00               0,00     100.000.000,00 00000000000000000000000000000000M0000             ,00000             ,00000        99999999N30052011                   000                          00000000000000000+0027000000099999999              0,00             ,00000 M]
```