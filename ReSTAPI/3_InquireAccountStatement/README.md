# 69447

Transaction code 69447 is known as `HistoricalTransactions` in SOA.

Sample SOAP request:
```xml
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>BNIDIRECT</systemId>
            <customHeader>
               <teller>200</teller>
               <branch>259</branch>
               <overrideFlag>I</overrideFlag>
            </customHeader>
            <content xsi:type="bo:HistoricalTransactionsReq">
               <accountNum>114479721</accountNum>
               <fromDate>2010/05/31</fromDate>
               <toDate>2010/05/31</toDate>
               <pageNum>0</pageNum>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>
```

```xml
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header>
               <coreJournal>422114</coreJournal>
            </header>
            <content xsi:type="bo:CompiledHistoricalTransactionsRes">
               <accountNum>114479721</accountNum>
               <accountName>Bpk FAJAR NURCAHYO</accountName>
               <productName>TAPLUS BISNIS PERORANGAN</productName>
               <address1>JALAN EBONY NO. 99</address1>
               <address2>9999. KOMPLEK BUDIMAN SENTOSA</address2>
               <address3>Tanah Sareal</address3>
               <address4>Tanah Sereal</address4>
               <postCode>16161</postCode>
               <accountCurrency>IDR</accountCurrency>
               <fromDate>2010-05-31</fromDate>
               <toDate>2010-05-31</toDate>
               <longHistoricals>
                  <sequenceNum>000001</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>421871</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006120789247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:16:20</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000002</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>421871</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006120795747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:16:20</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000003</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>421861</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006121335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:13:33</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000004</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>421861</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006121342247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:13:33</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000005</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>421620</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006121882247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>17:07:27</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000006</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>421620</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006121888747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>17:07:27</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000007</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>421617</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006122428747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>17:06:24</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000008</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>421617</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006122435247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>17:06:24</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000009</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>421424</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006122975247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:15:43</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000010</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>421424</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006122981747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:15:43</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000011</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>421395</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006123521747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:59:59</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000012</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>421395</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006123528247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:59:59</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000013</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>421393</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006124068247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:59:03</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000014</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>421393</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006124074747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:59:03</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000015</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>421392</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006124614747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:59:01</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000016</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>421392</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006124621247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:59:01</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000017</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>421273</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006125161247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:45:25</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000018</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>421273</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006125167747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:45:25</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000019</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>421265</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006125707747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:41:56</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000020</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>421265</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006125714247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:41:56</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000021</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>421188</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006126254247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:15:19</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000022</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>421188</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006126260747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:15:19</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000023</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>421171</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006126800747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:03:33</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000024</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>421171</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006126807247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:03:33</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000025</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>421145</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006127347247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>13:56:46</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000026</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>421145</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006127353747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>13:56:46</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000027</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>420667</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006127893747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>10:04:28</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000028</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>420667</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006127900247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>10:04:28</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000029</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>420427</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006128440247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:25:59</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000030</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>420427</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006128446747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:25:59</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000031</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>419550</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006128986747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:45:34</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000032</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>419550</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006128993247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:45:34</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000033</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>VA KELUARGA E098CF4618BB556C</narative>
                  <branchNum>986</branchNum>
                  <tracer>417893</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>306000.00</amount>
                  <balance>6006129533247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>18:08:16</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000034</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>VA KELUARGA E098CF4618BB556C</narative>
                  <branchNum>986</branchNum>
                  <tracer>415266</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>306000.00</amount>
                  <balance>6006129839247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:49:45</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000035</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>415018</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006130145247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>08:46:15</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000036</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>415018</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006130151747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>08:46:15</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000037</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>414943</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006130691747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>17:33:42</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000038</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>414943</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006130698247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>17:33:42</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000039</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>414805</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006131238247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:52:53</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000040</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>414805</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006131244747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:52:53</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000041</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>414709</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006131784747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:11:44</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000042</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>414709</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006131791247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:11:44</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000043</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>985</branchNum>
                  <tracer>414348</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006132331247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:20:15</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000044</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>985</branchNum>
                  <tracer>414348</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006132337747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:20:15</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000045</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>265</branchNum>
                  <tracer>414345</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006132877747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:19:26</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000046</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>265</branchNum>
                  <tracer>414345</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006132884247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:19:26</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000047</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (H2H BNP2TKI ) NO :12345678901234567</narative>
                  <branchNum>265</branchNum>
                  <tracer>414300</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006133424247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:09:21</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000048</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>H2H BNP2TKI 1234567890123456</narative>
                  <branchNum>265</branchNum>
                  <tracer>414300</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>540000.00</amount>
                  <balance>6006133430747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:09:21</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000049</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>elit. Aenean tempor accumsan turpis, quis luctus qIBS Pelindo 2019082815191966</narative>
                  <branchNum>986</branchNum>
                  <tracer>900716</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>5000000.00</amount>
                  <balance>6006133970747.00</balance>
                  <tofrAccount>00000000114580775</tofrAccount>
                  <narative36>DEKOETJING LTD.</narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:20:29</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000050</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>elit. Aenean tempor accumsan turpis, quis luctus qIBS Pelindo 2019082815191966</narative>
                  <branchNum>986</branchNum>
                  <tracer>900684</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>5000000.00</amount>
                  <balance>6006138970747.00</balance>
                  <tofrAccount>00000000114580775</tofrAccount>
                  <narative36>DEKOETJING LTD.</narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>11:01:24</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000051</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>VA KELUARGA E098CF4618BB556C</narative>
                  <branchNum>986</branchNum>
                  <tracer>412177</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>306000.00</amount>
                  <balance>6006143970747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:23:38</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000052</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>VA KELUARGA E098CF4618BB556C</narative>
                  <branchNum>986</branchNum>
                  <tracer>411992</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>306000.00</amount>
                  <balance>6006144276747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:50:28</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000053</sequenceNum>
                  <date>2010-05-31</date>
                  <description>BIAYA ATM LINK TUNAI</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>411918</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>6500.00</amount>
                  <balance>6006144582747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:23:53</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000054</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRF/PAY/TOP-UP ECHANNEL</description>
                  <narative></narative>
                  <branchNum>997</branchNum>
                  <tracer>411918</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>500000.00</amount>
                  <balance>6006144589247.00</balance>
                  <tofrAccount>0000003333333333</tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 6010047891234561 AGENT461234           JAK ARTA      JK</narative02>
                  <narative03>BNI DIRECT       100000000071</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:23:53</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000055</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>VA KELUARGA E098CF4618BB556C</narative>
                  <branchNum>986</branchNum>
                  <tracer>411862</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>306000.00</amount>
                  <balance>6006145089247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:24:22</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000056</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>VA KELUARGA E098CF4618BB556C</narative>
                  <branchNum>265</branchNum>
                  <tracer>411861</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>307000.00</amount>
                  <balance>6006145395247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:21:53</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000057</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>VA KELUARGA E098CF4618BB556C</narative>
                  <branchNum>986</branchNum>
                  <tracer>411859</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>306000.00</amount>
                  <balance>6006145702247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:21:03</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000058</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>VA KELUARGA E098CF4618BB556C</narative>
                  <branchNum>986</branchNum>
                  <tracer>411858</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>306000.00</amount>
                  <balance>6006146008247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:20:05</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000059</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>VA KELUARGA E098CF4618BB556C</narative>
                  <branchNum>986</branchNum>
                  <tracer>411857</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>306000.00</amount>
                  <balance>6006146314247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:19:53</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000060</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>VA KELUARGA E098CF4618BB556C</narative>
                  <branchNum>265</branchNum>
                  <tracer>411800</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>307000.00</amount>
                  <balance>6006146620247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:31:53</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000061</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>VA KELUARGA E098CF4618BB556C</narative>
                  <branchNum>265</branchNum>
                  <tracer>411796</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>306000.00</amount>
                  <balance>6006146927247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>14:31:33</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000062</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410986</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006147233247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>18:44:50</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000063</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410985</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006148233247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>18:44:40</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000064</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410984</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006149233247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>18:44:29</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000065</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410949</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006150233247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>17:56:30</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000066</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (KTMT        ) NO :5 19080113540185</narative>
                  <branchNum>265</branchNum>
                  <tracer>410935</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>6006151233247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>17:50:50</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000067</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>KTMT        5</narative>
                  <branchNum>265</branchNum>
                  <tracer>410935</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>100000.00</amount>
                  <balance>6006151235747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>17:50:50</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000068</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410930</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006151335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>17:49:55</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000069</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410922</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006152335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>17:48:09</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000070</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410917</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006153335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>17:47:40</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000071</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410779</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006154335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:56:16</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000072</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410484</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006155335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:23:18</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000073</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410482</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006156335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:22:42</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000074</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410481</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006157335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:22:15</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000075</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410480</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006158335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:22:13</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000076</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410479</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006159335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:22:11</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000077</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410477</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006160335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:21:57</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000078</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410474</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006161335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:21:41</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000079</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410470</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006162335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:21:30</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000080</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410468</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006163335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:21:14</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000081</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>MPN G2 IDR  916011003876169</narative>
                  <branchNum>997</branchNum>
                  <tracer>410465</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>1000000.00</amount>
                  <balance>6006164335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>15:20:20</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000082</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (KTMT        ) NO :32423443 3540183</narative>
                  <branchNum>265</branchNum>
                  <tracer>390577</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>6006165335747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:04:07</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000083</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>KTMT        32423443</narative>
                  <branchNum>265</branchNum>
                  <tracer>390577</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>100000.00</amount>
                  <balance>6006165338247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>16:04:07</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000084</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (KTMT        ) NO :0100000416 6 183</narative>
                  <branchNum>028</branchNum>
                  <tracer>380156</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>6006165438247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>11:11:18</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000085</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>KTMT        0100000416</narative>
                  <branchNum>028</branchNum>
                  <tracer>380156</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>33270000.00</amount>
                  <balance>6006165440747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>11:11:18</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000086</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BIAYA ADMIN (KTMT        ) NO :0100000416 2 183</narative>
                  <branchNum>028</branchNum>
                  <tracer>380141</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>2500.00</amount>
                  <balance>6006198710747.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>11:05:12</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000087</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>KTMT        0100000416</narative>
                  <branchNum>028</branchNum>
                  <tracer>380141</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>33270000.00</amount>
                  <balance>6006198713247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>11:05:12</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000088</sequenceNum>
                  <date>2010-05-31</date>
                  <description>SETOR TUNAI</description>
                  <narative></narative>
                  <branchNum>992</branchNum>
                  <tracer>380067</tracer>
                  <txcode>00</txcode>
                  <debit_credit>K</debit_credit>
                  <amount>1000.00</amount>
                  <balance>6006231983247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02>KARTU 0000000000000000 Tanah Sareal</narative02>
                  <narative03>00000000         9999KOMPLEK BUDIMAN SEN</narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime></transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000089</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BPJS TK     5</narative>
                  <branchNum>265</branchNum>
                  <tracer>968003</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>5000000.00</amount>
                  <balance>6006231982247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:44:38</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000090</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>BPJS TK     8260018022864000</narative>
                  <branchNum>265</branchNum>
                  <tracer>962202</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>5000000.00</amount>
                  <balance>6006236982247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>09:43:39</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000091</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>I-SAKU      088884444222</narative>
                  <branchNum>996</branchNum>
                  <tracer>350550</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>25000.00</amount>
                  <balance>6006241982247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>21:28:51</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000092</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>I-SAKU      088884444222</narative>
                  <branchNum>996</branchNum>
                  <tracer>350549</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>25000.00</amount>
                  <balance>6006242007247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>21:28:51</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000093</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>I-SAKU      088884444222</narative>
                  <branchNum>996</branchNum>
                  <tracer>350548</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>25000.00</amount>
                  <balance>6006242032247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>21:28:40</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000094</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>I-SAKU      088884444222</narative>
                  <branchNum>996</branchNum>
                  <tracer>350547</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>25000.00</amount>
                  <balance>6006242057247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>21:27:53</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000095</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>I-SAKU      088884444222</narative>
                  <branchNum>996</branchNum>
                  <tracer>350544</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>25000.00</amount>
                  <balance>6006242082247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>21:27:44</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000096</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>I-SAKU      088884444222</narative>
                  <branchNum>996</branchNum>
                  <tracer>350543</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>25000.00</amount>
                  <balance>6006242107247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>21:27:28</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000097</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>I-SAKU      088884444222</narative>
                  <branchNum>996</branchNum>
                  <tracer>350542</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>25000.00</amount>
                  <balance>6006242132247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>21:26:41</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000098</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>I-SAKU      088884444222</narative>
                  <branchNum>996</branchNum>
                  <tracer>350541</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>25000.00</amount>
                  <balance>6006242157247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>21:26:40</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000099</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>I-SAKU      088884444222</narative>
                  <branchNum>996</branchNum>
                  <tracer>350540</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>25000.00</amount>
                  <balance>6006242182247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>21:26:40</transactionTime>
               </longHistoricals>
               <longHistoricals>
                  <sequenceNum>000100</sequenceNum>
                  <date>2010-05-31</date>
                  <description>TRANSFER KE</description>
                  <narative>I-SAKU      088884444222</narative>
                  <branchNum>996</branchNum>
                  <tracer>350539</tracer>
                  <txcode>00</txcode>
                  <debit_credit>D</debit_credit>
                  <amount>25000.00</amount>
                  <balance>6006242207247.00</balance>
                  <tofrAccount></tofrAccount>
                  <narative36></narative36>
                  <narative02></narative02>
                  <narative03></narative03>
                  <narative38></narative38>
                  <narative39></narative39>
                  <transactionTime>21:26:37</transactionTime>
               </longHistoricals>
               <beginingBalance>6006242207247.00</beginingBalance>
               <creditsTotal>1000.00</creditsTotal>
               <debitsTotal>121444000.00</debitsTotal>
               <endingBalance>6006120789247.00</endingBalance>
               <totalRecords>000100</totalRecords>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format message:
```
[ 0134                    **
           003099100100001069447000000     0  I  0 000000  000000001147397142810202004112020000                ]
```