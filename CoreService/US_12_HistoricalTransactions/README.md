Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body>
		<q0:transaction>
			<request>
				<systemId>BNIDIRECT</systemId>
				<content xsi:type="bo:HistoricalTransactionsReq">
					<accountNum>116913895</accountNum>
					<fromDate>2010/05/31</fromDate>
					<toDate>2010/05/31</toDate>
					<pageNum>13</pageNum>
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
               <coreJournal>325499</coreJournal>
            </header>
            <content xsi:type="bo:CompiledHistoricalTransactionsRes">
               <accountNum>116913895</accountNum>
               <accountName>Bpk MUHAMAD JUHARDI</accountName>
               <productName>EMERALD SAVING</productName>
               <address1>JL. SETIABUDI</address1>
               <address2>35</address2>
               <address3>Setiabudi</address3>
               <address4>Setia Budi         /Jakarta Selatan</address4>
               <postCode>12910</postCode>
               <accountCurrency>IDR</accountCurrency>
               <fromDate>2010-05-31</fromDate>
               <toDate>2010-05-31</toDate>
               <longHistoricals>
                  <sequenceNum>001301</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>558063</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>2500.00</amount>
                  <balance>465099173.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000014 558062</narative02>
                  <narative03>AUTODEBET        901390018</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>10:11:49</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001302</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>558063</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>65000.00</amount>
                  <balance>465096673.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000014 558062</narative02>
                  <narative03>AUTODEBET        901390018</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>10:11:49</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001303</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0021014576982</narative>
                  <branchNum>997</branchNum>
                  <tracer>558062</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>465031673.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000014</narative02>
                  <narative03>AUTODEBET        901390018</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>10:11:46</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001304</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>AUTODEBET BILL PAYMENT (TLKM JAKTIM ) NO :00210145</narative>
                  <branchNum>997</branchNum>
                  <tracer>558062</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>65000.00</amount>
                  <balance>465034173.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000014</narative02>
                  <narative03>AUTODEBET        901390018</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>10:11:46</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001305</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER DARI</description>
                  <narative></narative>
                  <branchNum>265</branchNum>
                  <tracer>550021</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>6.00</amount>
                  <balance>465099173.00</balance>
                  <tofrAccount>00000000116913862</tofrAccount>
                  <narative36>Sdr NUR'AINI</narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:20:33</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001306</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>REND 005034</narative>
                  <branchNum>997</branchNum>
                  <tracer>793270</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>10000.00</amount>
                  <balance>465099167.00</balance>
                  <tofrAccount>00000000116905919</tofrAccount>
                  <narative36>ARIES  FIRDANSYAH</narative36>
                  <narative02>KARTU 1946900600000083 MINIHP 000100012000014ANC OL, JAKARTRE</narative02>
                  <narative03>12001402         36</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>18:24:30</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001307</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>REND 005034</narative>
                  <branchNum>997</branchNum>
                  <tracer>755558</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>10000.00</amount>
                  <balance>465109167.00</balance>
                  <tofrAccount>00000000116905919</tofrAccount>
                  <narative36>ARIES  FIRDANSYAH</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001411         100105</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>17:49:08</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001308</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>REND 005034</narative>
                  <branchNum>997</branchNum>
                  <tracer>754521</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>10000.00</amount>
                  <balance>465119167.00</balance>
                  <tofrAccount>00000000116910555</tofrAccount>
                  <narative36>Sdr STEVEN RAMA  SI RAMAI RAMAI</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001401         200079</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>11:47:21</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001309</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>REND 005034</narative>
                  <branchNum>997</branchNum>
                  <tracer>714519</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>100.00</amount>
                  <balance>465129167.00</balance>
                  <tofrAccount>00000000116905919</tofrAccount>
                  <narative36>ARIES  FIRDANSYAH</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001411         100034</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:18:32</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001310</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>REND 005034</narative>
                  <branchNum>997</branchNum>
                  <tracer>713949</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1500.00</amount>
                  <balance>465129267.00</balance>
                  <tofrAccount>00000000116905919</tofrAccount>
                  <narative36>ARIES  FIRDANSYAH</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001411         100011</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>08:56:55</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001311</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>REND 005034</narative>
                  <branchNum>997</branchNum>
                  <tracer>713946</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000.00</amount>
                  <balance>465130767.00</balance>
                  <tofrAccount>00000000116905919</tofrAccount>
                  <narative36>ARIES  FIRDANSYAH</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001411         100008</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>08:50:08</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001312</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>REND 005034</narative>
                  <branchNum>997</branchNum>
                  <tracer>713313</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>125000.00</amount>
                  <balance>465131767.00</balance>
                  <tofrAccount>00000000116905919</tofrAccount>
                  <narative36>ARIES  FIRDANSYAH</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001411         100087</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>11:55:17</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001313</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>REND 005034</narative>
                  <branchNum>997</branchNum>
                  <tracer>713287</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>150000.00</amount>
                  <balance>465256767.00</balance>
                  <tofrAccount>00000000116905919</tofrAccount>
                  <narative36>ARIES  FIRDANSYAH</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001411         100083</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>11:36:47</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001314</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER DARI</description>
                  <narative></narative>
                  <branchNum>243</branchNum>
                  <tracer>713277</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>5000000.00</amount>
                  <balance>465406767.00</balance>
                  <tofrAccount>00000000201120138</tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>11:26:27</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001315</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>REND 005034</narative>
                  <branchNum>997</branchNum>
                  <tracer>712745</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>150000.00</amount>
                  <balance>460406767.00</balance>
                  <tofrAccount>00000000116905919</tofrAccount>
                  <narative36>ARIES  FIRDANSYAH</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001411         100076</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>19:20:01</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001316</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>REND 005034</narative>
                  <branchNum>997</branchNum>
                  <tracer>712601</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>100000.00</amount>
                  <balance>460556767.00</balance>
                  <tofrAccount>00000000116905919</tofrAccount>
                  <narative36>ARIES  FIRDANSYAH</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001411         100045</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:12:47</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001317</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BANT2060001</narative>
                  <branchNum>997</branchNum>
                  <tracer>712600</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>30000.00</amount>
                  <balance>460656767.00</balance>
                  <tofrAccount>00000000116905919</tofrAccount>
                  <narative36>ARIES  FIRDANSYAH</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001416         101461</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:11:10</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001318</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BANT2500000</narative>
                  <branchNum>997</branchNum>
                  <tracer>712595</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>30000.00</amount>
                  <balance>460686767.00</balance>
                  <tofrAccount>00000000005000460</tofrAccount>
                  <narative36>Sdri  TEST AMALIA</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001416         101459</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:05:24</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001319</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BANT2066666</narative>
                  <branchNum>997</branchNum>
                  <tracer>712592</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>30000.00</amount>
                  <balance>460716767.00</balance>
                  <tofrAccount>00000000005000460</tofrAccount>
                  <narative36>Sdri  TEST AMALIA</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001416         101457</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:01:04</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001320</sequenceNum>
                  <date>2010-05-31</date>
                  <description>SETOR TUNAI</description>
                  <narative>khhdrth</narative>
                  <branchNum>259</branchNum>
                  <tracer>712591</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>10746767.00</amount>
                  <balance>460746767.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:59:18</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001321</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative></narative>
                  <branchNum>259</branchNum>
                  <tracer>712537</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>900000000.00</amount>
                  <balance>450000000.00</balance>
                  <tofrAccount>00000000201120138</tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:52:28</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001322</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative></narative>
                  <branchNum>259</branchNum>
                  <tracer>712533</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2000000000.00</amount>
                  <balance>1350000000.00</balance>
                  <tofrAccount>00000000201120138</tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:51:42</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001323</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative></narative>
                  <branchNum>259</branchNum>
                  <tracer>712532</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>5000000000.00</amount>
                  <balance>3350000000.00</balance>
                  <tofrAccount>00000000201120138</tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:50:45</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001324</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative></narative>
                  <branchNum>259</branchNum>
                  <tracer>712531</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>30000000000.00</amount>
                  <balance>8350000000.00</balance>
                  <tofrAccount>00000000201120138</tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:50:34</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001325</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>KURANGIN SALDO</narative>
                  <branchNum>259</branchNum>
                  <tracer>712528</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>400930148.00</amount>
                  <balance>38350000000.00</balance>
                  <tofrAccount>00000000201120138</tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:49:33</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001326</sequenceNum>
                  <date>2010-05-31</date>
                  <description>BY KU KE SIMPANAN</description>
                  <narative></narative>
                  <branchNum>259</branchNum>
                  <tracer>712519</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>4000000.00</amount>
                  <balance>38750930148.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>00:00:00</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001327</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative></narative>
                  <branchNum>259</branchNum>
                  <tracer>712519</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>4300000000.00</amount>
                  <balance>38754930148.00</balance>
                  <tofrAccount>00000000116929146</tofrAccount>
                  <narative36>Sdri ABHIRAMA  BOSSEGALABOS</narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:45:15</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001328</sequenceNum>
                  <date>2010-05-31</date>
                  <description>BY KU KE SIMPANAN</description>
                  <narative></narative>
                  <branchNum>259</branchNum>
                  <tracer>712518</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>100000000000.00</amount>
                  <balance>43054930148.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>00:00:00</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001329</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative></narative>
                  <branchNum>259</branchNum>
                  <tracer>712518</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>350000000000.00</amount>
                  <balance>143054930148.00</balance>
                  <tofrAccount>00000000116929146</tofrAccount>
                  <narative36>Sdri ABHIRAMA  BOSSEGALABOS</narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:44:15</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001330</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TARIK TUNAI</description>
                  <narative></narative>
                  <branchNum>259</branchNum>
                  <tracer>712515</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>200000000.00</amount>
                  <balance>493054930148.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:43:09</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001331</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TARIK TUNAI</description>
                  <narative></narative>
                  <branchNum>259</branchNum>
                  <tracer>712514</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>100000000.00</amount>
                  <balance>493254930148.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:43:03</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001332</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MBAHMU</narative>
                  <branchNum>259</branchNum>
                  <tracer>712508</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>470000000.00</amount>
                  <balance>493354930148.00</balance>
                  <tofrAccount>00000000116940002</tofrAccount>
                  <narative36>Sdri ABHIRAMA  BOSSEGALABOS</narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:40:53</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001333</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BANT2060001</narative>
                  <branchNum>997</branchNum>
                  <tracer>712504</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>30000.00</amount>
                  <balance>493824930148.00</balance>
                  <tofrAccount>00000000005000460</tofrAccount>
                  <narative36>Sdri  TEST AMALIA</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001416         101455</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:37:25</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001334</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BANT2060000</narative>
                  <branchNum>997</branchNum>
                  <tracer>712493</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>30000.00</amount>
                  <balance>493824960148.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 5371762590000118                       ANC OL, JAKART</narative02>
                  <narative03>12001416         101453</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:34:41</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001335</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BANT2060000</narative>
                  <branchNum>997</branchNum>
                  <tracer>712487</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>30000.00</amount>
                  <balance>493824930148.00</balance>
                  <tofrAccount>00000000005000460</tofrAccount>
                  <narative36>Sdri  TEST AMALIA</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001416         101453</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:30:18</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001336</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BANT2060000</narative>
                  <branchNum>997</branchNum>
                  <tracer>712481</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>30000.00</amount>
                  <balance>493824960148.00</balance>
                  <tofrAccount>00000000005000460</tofrAccount>
                  <narative36>Sdri  TEST AMALIA</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001416         101451</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:25:29</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001337</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BANT2060001</narative>
                  <branchNum>997</branchNum>
                  <tracer>712477</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>30000.00</amount>
                  <balance>493824990148.00</balance>
                  <tofrAccount>00000000005000460</tofrAccount>
                  <narative36>Sdri  TEST AMALIA</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001416         101449</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:24:36</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001338</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BANT2060001</narative>
                  <branchNum>997</branchNum>
                  <tracer>712455</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>30000.00</amount>
                  <balance>493825020148.00</balance>
                  <tofrAccount>00000000005000460</tofrAccount>
                  <narative36>Sdri  TEST AMALIA</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001416         101445</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:16:38</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001339</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BANT2060001</narative>
                  <branchNum>997</branchNum>
                  <tracer>712425</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>30000.00</amount>
                  <balance>493825050148.00</balance>
                  <tofrAccount>00000000005000460</tofrAccount>
                  <narative36>Sdri  TEST AMALIA</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001416         101441</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>13:56:20</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001340</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BANT2010005</narative>
                  <branchNum>997</branchNum>
                  <tracer>712414</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>30000.00</amount>
                  <balance>493825080148.00</balance>
                  <tofrAccount>00000000005000460</tofrAccount>
                  <narative36>Sdri  TEST AMALIA</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001416         101439</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>13:50:45</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001341</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BANT2500000</narative>
                  <branchNum>997</branchNum>
                  <tracer>712402</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>30000.00</amount>
                  <balance>493825110148.00</balance>
                  <tofrAccount>00000000005000460</tofrAccount>
                  <narative36>Sdri  TEST AMALIA</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001416         101433</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>13:43:15</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001342</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>SUBS1250000</narative>
                  <branchNum>997</branchNum>
                  <tracer>712400</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>4000.00</amount>
                  <balance>493825140148.00</balance>
                  <tofrAccount>00000000115334831</tofrAccount>
                  <narative36>Bpk   BAMBANG</narative36>
                  <narative02>KARTU 5371762590000118 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001416         101431</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>13:41:21</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001343</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>REND 005034</narative>
                  <branchNum>997</branchNum>
                  <tracer>712363</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000.00</amount>
                  <balance>493825136148.00</balance>
                  <tofrAccount>00000000116905919</tofrAccount>
                  <narative36>ARIES  FIRDANSYAH</narative36>
                  <narative02>KARTU 6010043330000013 MINIHP 000100012000014ANC OL, JAKART</narative02>
                  <narative03>12001411         100035</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>13:34:54</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001344</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>E-COLLECTION8201234562013102</narative>
                  <branchNum>259</branchNum>
                  <tracer>630275</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>150700.00</amount>
                  <balance>493825137148.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>13:34:55</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001345</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>E-COLLECTION8201234562013102</narative>
                  <branchNum>259</branchNum>
                  <tracer>626716</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>150700.00</amount>
                  <balance>493825287848.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>13:41:53</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001346</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0021998877441</narative>
                  <branchNum>997</branchNum>
                  <tracer>583034</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493825438548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000014</narative02>
                  <narative03>AUTODEBET        902070085</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>20:07:40</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001347</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0021998877441</narative>
                  <branchNum>997</branchNum>
                  <tracer>583034</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>65000.00</amount>
                  <balance>493825441048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000014</narative02>
                  <narative03>AUTODEBET        902070085</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>20:07:40</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001348</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0021998877441</narative>
                  <branchNum>997</branchNum>
                  <tracer>583010</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493825506048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000014</narative02>
                  <narative03>AUTODEBET        938020083</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>19:43:35</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001349</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0021998877441</narative>
                  <branchNum>997</branchNum>
                  <tracer>583010</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>65000.00</amount>
                  <balance>493825508548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000014</narative02>
                  <narative03>AUTODEBET        938020083</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>19:43:35</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001350</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0021998877441</narative>
                  <branchNum>997</branchNum>
                  <tracer>582993</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493825573548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000014</narative02>
                  <narative03>AUTODEBET        922330082</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>19:28:05</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001351</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0021998877441</narative>
                  <branchNum>997</branchNum>
                  <tracer>582993</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>65000.00</amount>
                  <balance>493825576048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000014</narative02>
                  <narative03>AUTODEBET        922330082</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>19:28:05</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001352</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0027000999334 01</narative>
                  <branchNum>997</branchNum>
                  <tracer>531147</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493825641048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 940440514</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:45:52</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001353</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0027000999334</narative>
                  <branchNum>997</branchNum>
                  <tracer>531147</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>250000.00</amount>
                  <balance>493825643548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 940440514</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:45:52</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001354</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>531146</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493825893548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 531145</narative02>
                  <narative03>INTERNET BANKING 940410512</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:45:48</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001355</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>531146</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493825891048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 531145</narative02>
                  <narative03>INTERNET BANKING 940410512</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:45:48</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001356</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0021000999222 01</narative>
                  <branchNum>997</branchNum>
                  <tracer>531145</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493825621048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 940410512</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:45:48</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001357</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0021000999222</narative>
                  <branchNum>997</branchNum>
                  <tracer>531145</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493825623548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 940410512</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:45:48</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001358</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0027000999334 01</narative>
                  <branchNum>997</branchNum>
                  <tracer>531144</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493825893548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 940290510</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:45:36</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001359</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0027000999334</narative>
                  <branchNum>997</branchNum>
                  <tracer>531144</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>250000.00</amount>
                  <balance>493825896048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 940290510</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:45:36</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001360</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>531143</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826146048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 531142</narative02>
                  <narative03>INTERNET BANKING 940260508</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:45:34</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001361</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>531143</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493826143548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 531142</narative02>
                  <narative03>INTERNET BANKING 940260508</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:45:34</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001362</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0021000999222 01</narative>
                  <branchNum>997</branchNum>
                  <tracer>531142</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493825873548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 940260508</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:45:33</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001363</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0021000999222</narative>
                  <branchNum>997</branchNum>
                  <tracer>531142</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493825876048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 940260508</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:45:33</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001364</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0027000999334 01</narative>
                  <branchNum>997</branchNum>
                  <tracer>531137</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826146048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 939180502</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:44:25</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001365</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0027000999334</narative>
                  <branchNum>997</branchNum>
                  <tracer>531137</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>250000.00</amount>
                  <balance>493826148548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 939180502</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:44:25</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001366</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>531136</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826398548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 531135</narative02>
                  <narative03>INTERNET BANKING 939150500</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:44:23</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001367</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>531136</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493826396048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 531135</narative02>
                  <narative03>INTERNET BANKING 939150500</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:44:23</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001368</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0021000999222 01</narative>
                  <branchNum>997</branchNum>
                  <tracer>531135</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826126048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 939150500</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:44:22</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001369</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0021000999222</narative>
                  <branchNum>997</branchNum>
                  <tracer>531135</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493826128548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 939150500</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:44:22</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001370</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0027000999334 01</narative>
                  <branchNum>997</branchNum>
                  <tracer>531127</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826398548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 935530494</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:41:00</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001371</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0027000999334</narative>
                  <branchNum>997</branchNum>
                  <tracer>531127</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>250000.00</amount>
                  <balance>493826401048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 935530494</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:41:00</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001372</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>531126</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826651048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 531125</narative02>
                  <narative03>INTERNET BANKING 935500492</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:40:57</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001373</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>531126</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493826648548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 531125</narative02>
                  <narative03>INTERNET BANKING 935500492</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:40:57</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001374</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0021000999222 01</narative>
                  <branchNum>997</branchNum>
                  <tracer>531125</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826378548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 935500492</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:40:57</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001375</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0021000999222</narative>
                  <branchNum>997</branchNum>
                  <tracer>531125</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493826381048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 935500492</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:40:57</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001376</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>531124</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826651048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 531123</narative02>
                  <narative03>INTERNET BANKING 935390490</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:40:47</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001377</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>531124</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493826648548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 531123</narative02>
                  <narative03>INTERNET BANKING 935390490</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:40:47</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001378</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0021000999222 01</narative>
                  <branchNum>997</branchNum>
                  <tracer>531123</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826378548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 935390490</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:40:46</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001379</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0021000999222</narative>
                  <branchNum>997</branchNum>
                  <tracer>531123</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493826381048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 935390490</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:40:46</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001380</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0027000999334 01</narative>
                  <branchNum>997</branchNum>
                  <tracer>531106</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826651048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 931510484</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:36:58</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001381</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0027000999334</narative>
                  <branchNum>997</branchNum>
                  <tracer>531106</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>250000.00</amount>
                  <balance>493826653548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 931510484</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:36:58</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001382</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>531105</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826903548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 531104</narative02>
                  <narative03>INTERNET BANKING 931480482</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:36:55</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001383</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>531105</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493826901048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 531104</narative02>
                  <narative03>INTERNET BANKING 931480482</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:36:55</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001384</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0021000999222 01</narative>
                  <branchNum>997</branchNum>
                  <tracer>531104</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826631048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 931480482</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:36:55</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001385</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0021000999222</narative>
                  <branchNum>997</branchNum>
                  <tracer>531104</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493826633548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 931480482</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:36:55</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001386</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0027000999334 00 5</narative>
                  <branchNum>997</branchNum>
                  <tracer>530321</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826903548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 904040421</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>12:09:11</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001387</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0027000999334</narative>
                  <branchNum>997</branchNum>
                  <tracer>530321</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>250000.00</amount>
                  <balance>493826906048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 904040421</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>12:09:11</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001388</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>530320</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493827156048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 530319</narative02>
                  <narative03>INTERNET BANKING 904010419</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>12:09:08</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001389</sequenceNum>
                  <date>2010-05-31</date>
                  <description>KOR TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>530320</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493827153548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002 530319</narative02>
                  <narative03>INTERNET BANKING 904010419</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>12:09:08</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001390</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>BIAYA ADMIN (TLKM JAKTIM ) NO :0021000999222 00 5</narative>
                  <branchNum>997</branchNum>
                  <tracer>530319</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>493826883548.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 904010419</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>12:09:08</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001391</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative>TLKM JAKTIM 0021000999222</narative>
                  <branchNum>997</branchNum>
                  <tracer>530319</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>270000.00</amount>
                  <balance>493826886048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010043330000002</narative02>
                  <narative03>INTERNET BANKING 904010419</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>12:09:08</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001392</sequenceNum>
                  <date>2010-05-31</date>
                  <description>SETOR TUNAI</description>
                  <narative>a</narative>
                  <branchNum>718</branchNum>
                  <tracer>511510</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>123456789012.00</amount>
                  <balance>493827156048.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:29:52</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001393</sequenceNum>
                  <date>2010-05-31</date>
                  <description>SETOR TUNAI</description>
                  <narative>a</narative>
                  <branchNum>718</branchNum>
                  <tracer>511508</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>123456789012.00</amount>
                  <balance>370370367036.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:29:45</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001394</sequenceNum>
                  <date>2010-05-31</date>
                  <description>SETOR TUNAI</description>
                  <narative>a</narative>
                  <branchNum>718</branchNum>
                  <tracer>511507</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>123456789012.00</amount>
                  <balance>246913578024.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:29:42</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>001395</sequenceNum>
                  <date>2010-05-31</date>
                  <description>SETOR TUNAI</description>
                  <narative>a</narative>
                  <branchNum>718</branchNum>
                  <tracer>511506</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>123456789012.00</amount>
                  <balance>123456789012.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:29:37</transactionTime>
               </longHistoricals>
               <beginingBalance>123456789012.00</beginingBalance>
               <creditsTotal>493844911821.00</creditsTotal>
               <debitsTotal>493379812648.00</debitsTotal>
               <endingBalance>465099173.00</endingBalance>
               <totalRecords>001395</totalRecords>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0134                    **            003098900100001069447000000     0  I  0 000000  000000001169138953105201031052010013                ]

[ 0354    0270            0000    000000003098900100001069447325499000040320400 000000  0300000000000000116913895Bpk MUHAMAD JUHARDI           EMERALD SAVING                JL. SETIABUDI                           35                                      Setiabudi                               Setia Budi         /Jakarta Selatan     12910   IDR310520103105201000130131052010KOR TRANSFER KE                                                                                                                                                                                                                                        99631282800K             4.00    3337470573.00                                                                                                                                                                                                                                                                      14:21:34                        00130231052010TRANSFER KE                                    I-SAKU      87775277589                                                                                                                                                                                 99631282700D             4.00    3337470569.00                                                                                                                                                                                                                                                                      14:21:31                        00130331052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99731074200D        200000.00    3337470573.00                                                       KARTU 6010043330000002                                       INTERNET BANKING 906150149                                                                                                                        15:08:39                        00130431052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99731073000D        200000.00    3337670573.00                                                       KARTU 6010043330000002                                       INTERNET BANKING 904070148                                                                                                                        15:06:28                        00130531052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99727381900K        500000.00    3337870573.00                                                       KARTU 6010043330000008 273643                                S1CSR001TEK      915020013                                                                                                                        17:17:54                        00130631052010TRF/PAY/TOP-UP ECHANNEL                        CITIBANK CC 4541784836228053                                                                                                                                                                            99727364300D        500000.00    3337370573.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      915020013                                                                                                                        17:17:23                        00130731052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99727363500K        500000.00    3337870573.00                                                       KARTU 6010043330000008 273265                                S1CSR001TEK      913560012                                                                                                                        17:17:21                        00130831052010TRF/PAY/TOP-UP ECHANNEL                        CITIBANK CC 4541784836228053                                                                                                                                                                            99727326500D        500000.00    3337370573.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      913560012                                                                                                                        17:16:17                        00130931052010TRF/PAY/TOP-UP ECHANNEL                        CITIBANK CC 4541784836228053                                                                                                                                                                            99727098800D        500000.00    3337870573.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      930060006                                                                                                                        16:32:26                        00131031052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99727098400K        500000.00    3338370573.00                                                       KARTU 6010043330000008 270983                                S1CSR001TEK      924210005                                                                                                                        16:27:54                        00131131052010TRF/PAY/TOP-UP ECHANNEL                        CITIBANK CC 4541784836228053                                                                                                                                                                            99727098300D        500000.00    3337870573.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      924210005                                                                                                                        16:26:42                        00131231052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99727098200K        500000.00    3338370573.00                                                       KARTU 6010043330000008 270981                                S1CSR001TEK      923040004                                                                                                                        16:26:22                        00131331052010TRF/PAY/TOP-UP ECHANNEL                        CITIBANK CC 4541784836228053                                                                                                                                                                            99727098100D        500000.00    3337870573.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      923040004                                                                                                                        16:25:25                        00131431052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99727098000K        500000.00    3338370573.00                                                       KARTU 6010043330000008 270979                                S1CSR001TEK      920060003                                                                                                                        16:23:17                        00131531052010TRF/PAY/TOP-UP ECHANNEL                        CITIBANK CC 4541784836228053                                                                                                                                                                            99727097900D        500000.00    3337870573.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      920060003                                                                                                                        16:22:26                        00131631052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99727097700K        500000.00    3338370573.00                                                       KARTU 6010043330000008 270976                                S1CSR001TEK      917040002                                                                                                                        16:20:28                        00131731052010TRF/PAY/TOP-UP ECHANNEL                        CITIBANK CC 4541784836228052                                                                                                                                                                            99727097600D        500000.00    3337870573.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      917040002                                                                                                                        16:19:25                        00131831052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99727097500K        500000.00    3338370573.00                                                       KARTU 6010043330000008 270974                                S1CSR001TEK      916170001                                                                                                                        16:19:23                        00131931052010TRF/PAY/TOP-UP ECHANNEL                        CITIBANK CC 4617784836228052                                                                                                                                                                            99727097400D        500000.00    3337870573.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      916170001                                                                                                                        16:18:53                        00132031052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99727097000K        500000.00    3338370573.00                                                       KARTU 6010043330000008 270968                                S1CSR001TEK      905090449                                                                                                                        16:08:22                        00132131052010TRF/PAY/TOP-UP ECHANNEL                        CITIBANK CC 4617784836228052                                                                                                                                                                            99727096900D        500000.00    3337870573.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      905250450                                                                                                                        16:08:21                        00132231052010TRF/PAY/TOP-UP ECHANNEL                        CITIBANK CC 4037310000011181                                                                                                                                                                            99727096800D        500000.00    3338370573.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      905090449                                                                                                                        16:07:30                        00132331052010TRANSFER DARI                                  201812_BE528747110095_10_AAK                                                                                                                                                                            26590005300K       1606400.00    3338870573.00 00000000114458054 SATRIA  SAMBRAMA                                                                                                                                                                                                                                   10:49:46                        00132431052010TRANSFER DARI                                  201812_BE528747110096_10_AAK                                                                                                                                                                            26590004400K       1606400.00    3337264173.00 00000000114458054 SATRIA  SAMBRAMA                                                                                                                                                                                                                                   10:29:03                        00132531052010TRANSFER DARI                                  201812_BE528747110098_10_AAK                                                                                                                                                                            26590002300K       1606400.00    3335657773.00 00000000114458054 SATRIA  SAMBRAMA                                                                                                                                                                                                                                   11:19:10                        00132631052010TRANSFER DARI                                  BE528747110098 201812                                                                                                                                                                                   26590001900K       1606400.00    3334051373.00 00000000114458054 SATRIA  SAMBRAMA                                                                                                                                                                                                                                   11:08:48                        00132731052010TRANSFER DARI                                  BE528747110098 201812                                                                                                                                                                                   26590001700K       1606400.00    3332444973.00 00000000114458054 SATRIA  SAMBRAMA                                                                                                                                                                                                                                   10:42:20                        00132831052010TRF/PAY/TOP-UP ECHANNEL                        CITILINK TOP123456789012                                                                                                                                                                                99722728400D       1504000.00    3330838573.00                                                       KARTU 6010043330000002                                       INTERNET BANKING 944510005                                                                                                                        16:47:11                        00132931052010TRF/PAY/TOP-UP ECHANNEL                        CITILINK TOP123456789012                                                                                                                                                                                99722726200D       1504000.00    3332342573.00                                                       KARTU 6010043330000002                                       INTERNET BANKING 934100002                                                                                                                        16:36:30                        00133031052010TRF/PAY/TOP-UP ECHANNEL                        CITILINK TOP123456789012                                                                                                                                                                                99722725200D       1504000.00    3333846573.00                                                       KARTU 6010043330000002                                       INTERNET BANKING 925210373                                                                                                                        16:27:41                        00133131052010TRF/PAY/TOP-UP ECHANNEL                        CITILINK TOP123456789012                                                                                                                                                                                99722708500D       1504000.00    3335350573.00                                                       KARTU 6010043330000002                                       INTERNET BANKING 907500355                                                                                                                        15:10:09                        00133231052010TRANSFER KE                                    GOPAY CUST  591465201662378                                                                                                                                                                             99622650600D    1000000000.00    3336854573.00                                                                                                                                                                                                                                                                      09:49:21                        00133331052010TRANSFER KE                                                                                                                                                                                                                                            76090302600D           100.00    4336854573.00 00000000114458054 SATRIA  SAMBRAMA                                                                                                                                                                                                                                   09:21:06                        00133431052010TRANSFER KE                                                                                                                                                                                                                                            76090302500D           100.00    4336854673.00 00000000114458054 SATRIA  SAMBRAMA                                                                                                                                                                                                                                   09:21:03                        00133531052010TRANSFER KE                                    AP I        8871701152101100                                                                                                                                                                            26522643500D      19636365.00    4336854773.00                                                                                                                                                                                                                                                                      09:13:34                        00133631052010TRANSFER KE                                                                                                                                                                                                                                            76090302400D           100.00    4356491138.00 00000000114458054 SATRIA  SAMBRAMA                                                                                                                                                                                                                                   08:59:29                        00133731052010TRANSFER KE                                    GOPAY CUST  591465201662378                                                                                                                                                                             99622637100D    1000000000.00    4356491238.00                                                                                                                                                                                                                                                                      19:28:50                        00133831052010TRANSFER KE                                    GOPAY CUST  591465201662378                                                                                                                                                                             99622487300D    1000000000.00    5356491238.00                                                                                                                                                                                                                                                                      14:39:42                        00133931052010TRANSFER KE                                    GOPAY CUST  591465201662378                                                                                                                                                                             99622486900D    1000000000.00    6356491238.00                                                                                                                                                                                                                                                                      14:38:56                        00134031052010TRANSFER KE                                    GOPAY CUST  591465201662378                                                                                                                                                                             99622462700D    1000000000.00    7356491238.00                                                                                                                                                                                                                                                                      10:40:23                        00134131052010TRANSFER KE                                    8696181129152801 zola                                                                                                                                                                                   26590228300D          3000.00    8356491238.00 00000000114468471Sdri   BEND ABIDIN SANTOSA                                                                                                                                                                                                                          15:28:27                        00134231052010TRANSFER KE                                    8696181129152801 zola                                                                                                                                                                                   26590228300D           100.00    8356494238.00 00000000114473763   DEKOETJING LTD.                                                                                                                                                                                                                                  15:28:27                        00134331052010TRANSFER KE                                    8300181003140315 Henady                                                                                                                                                                                 26590228200D           500.00    8356494338.00 00000000114468471Sdri   BEND ABIDIN SANTOSA                                                                                                                                                                                                                          15:00:45                        00134431052010TRANSFER KE                                    8300181003140315 Henady                                                                                                                                                                                 26590228200D        888888.00    8356494838.00 00000000114458054 SATRIA  SAMBRAMA                                                                                                                                                                                                                                   15:00:45                        00134531052010TRANSFER KE                                    8300181003140315 Henady                                                                                                                                                                                 26522225400D           500.00    8357383726.00 00000000114468471Sdri   BEND ABIDIN SANTOSA                                                                                                                                                                                                                          14:59:10                        00134631052010TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                                26522225400D           100.00    8357384226.00 00000000114458054 SATRIA  SAMBRAMA                                                                                                                                                                                                                                   14:59:10                        00134731052010TRANSFER KE                                    8300181003140315 Henady                                                                                                                                                                                 26590228100D           500.00    8357384326.00 00000000114468471Sdri   BEND ABIDIN SANTOSA                                                                                                                                                                                                                          14:57:16                        00134831052010TRANSFER KE                                    8300181003140315 Henady                                                                                                                                                                                 26590228100D        888888.00    8357384826.00 00000000114458054 SATRIA  SAMBRAMA                                                                                                                                                                                                                                   14:57:16                        00134931052010TRANSFER KE                                    8696181129145301 zola                                                                                                                                                                                   99690227900D          3000.00    8358273714.00 00000000114468471Sdri   BEND ABIDIN SANTOSA                                                                                                                                                                                                                          14:54:05                        00135031052010TRANSFER KE                                    8696181129145301 zola                                                                                                                                                                                   99690227900D           100.00    8358276714.00 00000000114473763   DEKOETJING LTD.                                                                                                                                                                                                                                  14:54:05                        00135131052010TRANSFER KE                                    8696181129142601 zola                                                                                                                                                                                   99690227800D          3000.00    8358276814.00 00000000114468471Sdri   BEND ABIDIN SANTOSA                                                                                                                                                                                                                          14:37:29                        00135231052010TRANSFER KE                                    8696181129142601 zola                                                                                                                                                                                   99690227800D           100.00    8358279814.00 00000000114473763   DEKOETJING LTD.                                                                                                                                                                                                                                  14:37:29                        00135331052010TRANSFER KE                                                                                                                                                                                                                                            26522219100D           110.00    8358279914.00 00000000116977973   DEKOETJING LTD.                                                                                                                                                                                                                                  14:31:35                        00135431052010TRANSFER KE                                    sdssdsd                                                                                                                                                                                                 26522218900D           100.00    8358280024.00 00000000116977973   DEKOETJING LTD.                                                                                                                                                                                                                                  14:31:21                        00135531052010TRANSFER DARI                                  INI NARASI KE NON GL000000000000000000000000000000                                                                                                                                                      26522141600K       1348500.00    8358280124.00 02653602090001365                                                                                                                                                                                                                                                    10:07:10                        00135631052010TRANSFER DARI                                  USD00000000000000000000000000000000000000000000000                                                                                                                                                      26522140900K         51000.00    8356931624.00 02653602090001365                                                                                                                                                                                                                                                    10:04:11                        00135731052010TRANSFER DARI                                  USD00000000000000000000000000000000000000000000000                                                                                                                                                      26522139800K         50000.00    8356880624.00 02653602090001365                                                                                                                                                                                                                                                    10:00:58                        00135831052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99722022800D        200000.00    8356830624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      903102269                                                                                                                        10:05:29                        00135931052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99722022000D        200000.00    8357030624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      901442267                                                                                                                        10:04:04                        00136031052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99721993000D        200000.00    8357230624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      952292001                                                                                                                        09:54:49                        00136131052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99721992900D        200000.00    8357430624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      952152000                                                                                                                        09:54:35                        00136231052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99721992800D        200000.00    8357630624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      952131999                                                                                                                        09:54:33                        00136331052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99721992500D        200000.00    8357830624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      950051996                                                                                                                        09:52:26                        00136431052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99721984200D        200000.00    8358030624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      928001994                                                                                                                        09:30:20                        00136531052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99721972700D        200000.00    8358230624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      915281941                                                                                                                        09:17:47                        00136631052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99721971500D        200000.00    8358430624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      913121938                                                                                                                        09:15:32                        00136731052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99721464700D        200000.00    8358630624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      932221792                                                                                                                        11:34:42                        00136831052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99721464100D        200000.00    8358830624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      931501789                                                                                                                        11:34:18                        00136931052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99721450400D        200000.00    8359030624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      958231774                                                                                                                        11:00:43                        00137031052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99721408500D        200000.00    8359230624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      947021729                                                                                                                        09:49:30                        00137131052010TRF/PAY/TOP-UP ECHANNEL                        BNI CC ATM P4105040000011181                                                                                                                                                                            99719935200D        500000.00    8359430624.00                                                       KARTU 6010043330000002                                       INTERNET BANKING 924351608                                                                                                                        14:26:56                        00137231052010TRF/PAY/TOP-UP ECHANNEL                        BNI CC ATM P4105040000011181                                                                                                                                                                            99719933900D        500000.00    8359930624.00                                                       KARTU 6010043330000002                                       INTERNET BANKING 922321605                                                                                                                        14:24:52                        00137331052010TRANSFER KE                                    MPN G2 IDR  620181100026857                                                                                                                                                                             26519308900D       7993000.00    8360430624.00                                                                                                                                                                                                                                                                      11:08:27                        00137431052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99718846200K        200000.00    8368423624.00                                                       KARTU 6010043330000002 185877                                INTERNET BANKING 946011195                                                                                                                        16:44:48                        00137531052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99718846100K        200000.00    8368223624.00                                                       KARTU 6010043330000002 185857                                INTERNET BANKING 943331192                                                                                                                        16:44:48                        00137631052010TRF/PAY/TOP-UP ECHANNEL                        INFAQ       081912452026                                                                                                                                                                                99718594600D        200000.00    8368023624.00                                                       KARTU 6010043330000002                                       INTERNET BANKING 952591202                                                                                                                        09:55:23                        00137731052010TRF/PAY/TOP-UP ECHANNEL                        INFAQ       081912452026                                                                                                                                                                                99718591700D        200000.00    8368223624.00                                                       KARTU 6010043330000002                                       INTERNET BANKING 950301198                                                                                                                        09:52:52                        00137831052010TRF/PAY/TOP-UP ECHANNEL                        INFAQ       081912452026                                                                                                                                                                                99718587700D        200000.00    8368423624.00                                                       KARTU 6010043330000002                                       INTERNET BANKING 946011195                                                                                                                        09:48:22                        00137931052010TRF/PAY/TOP-UP ECHANNEL                        INFAQ       081912452026                                                                                                                                                                                99718585700D        200000.00    8368623624.00                                                       KARTU 6010043330000002                                       INTERNET BANKING 943331192                                                                                                                        09:45:56                        00138031052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99717138300K        200000.00    8368823624.00                                                       KARTU 6010043330000008 171382                                S1CSR001TEK      917230939                                                                                                                        17:19:43                        00138131052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99717138200D        200000.00    8368623624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      917230939                                                                                                                        17:19:43                        00138231052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99717124100D        200000.00    8368823624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      903530936                                                                                                                        17:06:13                        00138331052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99717121900K        200000.00    8369023624.00                                                       KARTU 6010043330000008 170971                                S1CSR001TEK      938540930                                                                                                                        17:04:16                        00138431052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99717097100D        200000.00    8368823624.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      938540930                                                                                                                        16:41:14                        00138531052010TRANSFER KE                                    CMS NEW CARD201004221400 CMS                                                                                                                                                                            26516946800D       1234567.00    8369023624.00                                                                                                                                                                                                                                                                      14:29:29                        00138631052010TRANSFER KE                                                                0090201004221400      CMS NEW CARD201004221400 CMS                                                                                                                          26516046200D       1234567.00    8370258191.00                                                                                                                                                                                                                                                                      14:59:48                        00138731052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99715915600D        200000.00    8371492758.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      916350614                                                                                                                        11:18:55                        00138831052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99715089000D        200000.00    8371692758.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      936400453                                                                                                                        13:39:00                        00138931052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99715082400D        200000.00    8371892758.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      932300442                                                                                                                        13:34:49                        00139031052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99715077100D        200000.00    8372092758.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      927190435                                                                                                                        13:29:38                        00139131052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99715073600D        200000.00    8372292758.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      924370428                                                                                                                        13:26:56                        00139231052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99714792900D        200000.00    8372492758.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      931370294                                                                                                                        09:33:57                        00139331052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99714767100K        200000.00    8372692758.00                                                       KARTU 6010043330000008 147624                                S1CSR001TEK      947420278                                                                                                                        09:01:46                        00139431052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99714762400D        200000.00    8372492758.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      947420278                                                                                                                        08:50:02                        00139531052010TRANSFER KE                                    VA KELUARGA E098CF4618BB556C                                                                                                                                                                            26514516600D        102000.00    8372692758.00                                                                                                                                                                                                                                                                      14:55:14                        00139631052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99714109100D         20000.00    8372794758.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      918160102                                                                                                                        09:20:36                        00139731052010TRF/PAY/TOP-UP ECHANNEL                        ZAKAT       081912452026                                                                                                                                                                                99713173900D        200000.00    8372814758.00                                                       KARTU 6010043330000008                                       S1CSR001TEK      953530054                                                                                                                        18:56:13                        00139831052010TRANSFER KE                                    PLN POSTPAID531                                                                                                                                                                                         26512855800D        679000.00    8373014758.00                                                                                                                                                                                                                                                                      14:21:20                        00139931052010TRANSFER KE                                    PLN POSTPAID531                                                                                                                                                                                         26512854300D        679000.00    8373693758.00                                                                                                                                                                                                                                                                      14:19:59                        00140031052010TRANSFER KE                                    PLN POSTPAID531                                                                                                                                                                                         26512851900D        679000.00    8374372758.00                                                                                                                                                                                                                                                                      14:18:52                        000101    8374372758.00       14481504.00    5052062689.00    3337470573.00 001401]
```