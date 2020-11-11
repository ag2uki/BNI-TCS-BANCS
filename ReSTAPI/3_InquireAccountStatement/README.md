# 69447

Transaction code 69447 is known as `HistoricalTransactions` in SOA.

Sample SOAP request:
```xml
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" 
xmlns:bo="http://service.bni.co.id/core/bo" 
xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" 
xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
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

Sample SOAP response:
```xml
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header>
               <coreJournal>396496</coreJournal>
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

Bancs Format Sample Request Message:
```
[ 0134                    **            003098900100001069447000000     0  I  0 000000  000000001169138953105201031052010013                ]
```

Bancs Format Sample Response Message:
```
[ 0354    0270            0000    000000003098900100001069447396496000040320400 000000  0300000000000000116913895Bpk MUHAMAD JUHARDI           EMERALD SAVING                JL. SETIABUDI                           35                                      Setiabudi                               Setia Budi         /Jakarta Selatan     12910   IDR3105201031052010]
[ 0685    0601            0000    000000003098900100001069447396496000040320000 000000  0300130131052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99755806300K          2500.00     465099173.00                                                       KARTU 6010043330000014 558062                                AUTODEBET        901390018                                                                                                                        10:11:49                        ]
[ 0685    0601            0000    000000003098900100001069447396496000040320000 000000  0300130231052010KOR TRF/PAY/TOP-UP ECHANNEL                                                                                                                                                                                                                            99755806300K         65000.00     465096673.00                                                       KARTU 6010043330000014 558062                                AUTODEBET        901390018                                                                                                                        10:11:49                        ]
[ 0685    0601            0000    000000003098900100001069447396503000040320000 000000  0300139531052010SETOR TUNAI                                    a                                                                                                                                                                                                       71851150600K  123456789012.00  123456789012.00                                                                                                                                                                                                                                                                      09:29:37                        ]
[ 0166    0082            0000    000000003098900100001069447396503000040320200 000000  03000096  123456789012.00   493844911821.00  493379812648.00     465099173.00 001395]
```