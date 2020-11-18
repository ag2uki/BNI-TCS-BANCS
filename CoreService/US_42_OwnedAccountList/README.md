Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>KSEI</systemId>]
            <content xsi:type="bo:OwnedAccountListReq">
               <cif_or_accountNum>9144751232</cif_or_accountNum>
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
            <content xsi:type="NS_BO:CompiledOwnedAccountListRes" xmlns:NS_BO="http://service.bni.co.id/core/bo">
               <cifNum>00000009144751232</cifNum>
               <cifName>Ibu SHERLOCK HOLMES</cifName>
               <shortAccountInfo>
                  <accountNum>00000000115387410</accountNum>
                  <status>DRMT</status>
                  <accountSystem>D</accountSystem>
                  <productName>BNI TAPLUS</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>4369376517556</balance>
                  <limit></limit>
                  <accountTypeCode>2000</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000115409515</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>EMERALD SAVING</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>89998045224650</balance>
                  <limit></limit>
                  <accountTypeCode>2301</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000115409649</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>BNI TAPLUS</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>1001364874532</balance>
                  <limit></limit>
                  <accountTypeCode>2000</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000115409650</accountNum>
                  <status>DRMT</status>
                  <accountSystem>D</accountSystem>
                  <productName>BNI TAPLUS</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>40.492.265,00</balance>
                  <limit></limit>
                  <accountTypeCode>2000</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000115409694</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>TAB BNI DOLLAR PERORANGAN SGD</productName>
                  <currency>SGD</currency>
                  <ownership>OWN</ownership>
                  <balance>0,00</balance>
                  <limit></limit>
                  <accountTypeCode>2004</accountTypeCode>
                  <subCatCode>0003</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000115409707</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>TAB BNI DOLLAR PERORANGAN SGD</productName>
                  <currency>SGD</currency>
                  <ownership>OWN</ownership>
                  <balance>0,00</balance>
                  <limit></limit>
                  <accountTypeCode>2004</accountTypeCode>
                  <subCatCode>0003</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000115409718</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>TAB BNI DOLLAR PERORANGAN SGD</productName>
                  <currency>SGD</currency>
                  <ownership>OWN</ownership>
                  <balance>0,00</balance>
                  <limit></limit>
                  <accountTypeCode>2004</accountTypeCode>
                  <subCatCode>0003</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000115409729</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>TAB BNI DOLLAR PERORANGAN SGD</productName>
                  <currency>SGD</currency>
                  <ownership>OWN</ownership>
                  <balance>0,00</balance>
                  <limit></limit>
                  <accountTypeCode>2004</accountTypeCode>
                  <subCatCode>0003</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000115427035</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>TAB BNI DOLLAR PERORANGAN USD</productName>
                  <currency>USD</currency>
                  <ownership>OWN</ownership>
                  <balance>3.003.707.559,77</balance>
                  <limit></limit>
                  <accountTypeCode>2004</accountTypeCode>
                  <subCatCode>0002</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000115428812</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>BNI TAPLUS</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>2072701268720</balance>
                  <limit></limit>
                  <accountTypeCode>2000</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000115428823</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>TAB BNI DOLLAR PERORANGAN USD</productName>
                  <currency>USD</currency>
                  <ownership>OWN</ownership>
                  <balance>3.938.331,61</balance>
                  <limit></limit>
                  <accountTypeCode>2004</accountTypeCode>
                  <subCatCode>0002</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000115446092</accountNum>
                  <status>DRMT</status>
                  <accountSystem>D</accountSystem>
                  <productName>TAPLUS BISNIS PERORANGAN</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>21.707.056.717,00</balance>
                  <limit></limit>
                  <accountTypeCode>2300</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000115446105</accountNum>
                  <status>DRMT</status>
                  <accountSystem>D</accountSystem>
                  <productName>TAPLUS BISNIS PERORANGAN</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>88396199469822</balance>
                  <limit></limit>
                  <accountTypeCode>2300</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000002196112751</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>GIRO TDK HIT BBB PERORANGAN</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>9.139.762.272,00</balance>
                  <limit></limit>
                  <accountTypeCode>1010</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000219611275</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>GIRO TDK HIT BBB PERORANGAN</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>10.112.829.604,00</balance>
                  <limit></limit>
                  <accountTypeCode>1010</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000115475216</accountNum>
                  <status>OPEN</status>
                  <accountSystem>C</accountSystem>
                  <productName>LC Import Sight IDR</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>0,00</balance>
                  <limit></limit>
                  <accountTypeCode>1600</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000116911843</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>GIRO OVERDRAFT BB PERORANGAN</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>0,00</balance>
                  <limit></limit>
                  <accountTypeCode>1410</accountTypeCode>
                  <subCatCode>5001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000116911854</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>GIRO CORP SPECIAL YIELD PERSH</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>11.819.396,00</balance>
                  <limit></limit>
                  <accountTypeCode>1811</accountTypeCode>
                  <subCatCode>6001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114449651</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>BNI TAPLUS</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>97.473.000,00</balance>
                  <limit></limit>
                  <accountTypeCode>2000</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114454297</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>BNI TAPLUS</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>693.801.705,00</balance>
                  <limit></limit>
                  <accountTypeCode>2000</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114454333</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>TAPLUS BISNIS PERORANGAN</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>209.376.993,00</balance>
                  <limit></limit>
                  <accountTypeCode>2300</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114455439</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>KMK BNI MIDDLE</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>100.000.000,00</balance>
                  <limit></limit>
                  <accountTypeCode>1010</accountTypeCode>
                  <subCatCode>0701</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114455451</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>KMK BNI SMALL</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>100.000.000,00</balance>
                  <limit></limit>
                  <accountTypeCode>1020</accountTypeCode>
                  <subCatCode>0701</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114455609</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>KI BNI KORPORASI IDR</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>0,00</balance>
                  <limit></limit>
                  <accountTypeCode>2010</accountTypeCode>
                  <subCatCode>0701</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114455814</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>KI BNI KORPORASI IDR</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>100.000.000,00</balance>
                  <limit></limit>
                  <accountTypeCode>2010</accountTypeCode>
                  <subCatCode>0701</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114455949</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>KMK BNI MIDDLE</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>100.000.000,00</balance>
                  <limit></limit>
                  <accountTypeCode>1010</accountTypeCode>
                  <subCatCode>0701</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114456238</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>KMK BNI MIDDLE</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>100.000.000,00</balance>
                  <limit></limit>
                  <accountTypeCode>1010</accountTypeCode>
                  <subCatCode>0701</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114456793</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>KMK BNI MIDDLE</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>434.146,00</balance>
                  <limit></limit>
                  <accountTypeCode>1010</accountTypeCode>
                  <subCatCode>0701</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114459943</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>KMK BNI MIDDLE</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>0,00</balance>
                  <limit></limit>
                  <accountTypeCode>1010</accountTypeCode>
                  <subCatCode>0701</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114459954</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>KMK BNI MIDDLE</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>0,00</balance>
                  <limit></limit>
                  <accountTypeCode>1010</accountTypeCode>
                  <subCatCode>0701</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114459965</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>KMK BNI MIDDLE</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>0,00</balance>
                  <limit></limit>
                  <accountTypeCode>1010</accountTypeCode>
                  <subCatCode>0701</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114459976</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>KMK BNI MIDDLE</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>0,00</balance>
                  <limit></limit>
                  <accountTypeCode>1010</accountTypeCode>
                  <subCatCode>0701</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114460164</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>KI BNI KORPORASI IDR</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>100.000.000,00</balance>
                  <limit></limit>
                  <accountTypeCode>2010</accountTypeCode>
                  <subCatCode>0701</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114460175</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>BNI GRIYA IND IDR</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>100.000.000,00</balance>
                  <limit></limit>
                  <accountTypeCode>3010</accountTypeCode>
                  <subCatCode>0201</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114460618</accountNum>
                  <status>OPEN</status>
                  <accountSystem>L</accountSystem>
                  <productName>KMK BNI MIDDLE</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>0,00</balance>
                  <limit></limit>
                  <accountTypeCode>1010</accountTypeCode>
                  <subCatCode>0701</subCatCode>
               </shortAccountInfo>
               <shortAccountInfo>
                  <accountNum>00000000114487733</accountNum>
                  <status>OPEN</status>
                  <accountSystem>D</accountSystem>
                  <productName>BNI TAPLUS</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>20.975.299,00</balance>
                  <limit></limit>
                  <accountTypeCode>2000</accountTypeCode>
                  <subCatCode>0001</subCatCode>
               </shortAccountInfo>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0099                    **            003098700100001060450000000     0  I  0 000000  00000009144751232]

[ 0232    0148            0000    000000003098700100001060450000000000040320000 000000  0300000000115387410DRMT  DBNI TAPLUS                    IDROWN       4369376517556                      2000000100000000115409515OPEN  DEMERALD SAVING                IDROWN      89998045224650                      2301000100000000115409649OPEN  DBNI TAPLUS                    IDROWN       1001364874532                      2000000100000000115409650DRMT  DBNI TAPLUS                    IDROWN       40.492.265,00                      2000000100000000115409694OPEN  DTAB BNI DOLLAR PERORANGAN SGD SGDOWN                0,00                      2004000300000000115409707OPEN  DTAB BNI DOLLAR PERORANGAN SGD SGDOWN                0,00                      2004000300000000115409718OPEN  DTAB BNI DOLLAR PERORANGAN SGD SGDOWN                0,00                      2004000300000000115409729OPEN  DTAB BNI DOLLAR PERORANGAN SGD SGDOWN                0,00                      2004000300000000115427035OPEN  DTAB BNI DOLLAR PERORANGAN USD USDOWN    3.003.707.559,77                      2004000200000000115428812OPEN  DBNI TAPLUS                    IDROWN       2072701268720                      2000000100000000115428823OPEN  DTAB BNI DOLLAR PERORANGAN USD USDOWN        3.938.331,61                      2004000200000000115446092DRMT  DTAPLUS BISNIS PERORANGAN      IDROWN   21.707.056.717,00                      2300000100000000115446105DRMT  DTAPLUS BISNIS PERORANGAN      IDROWN      88396199469822                      2300000100000002196112751OPEN  DGIRO TDK HIT BBB PERORANGAN   IDROWN    9.139.762.272,00                      1010000100000000219611275OPEN  DGIRO TDK HIT BBB PERORANGAN   IDROWN   10.112.829.604,00                      1010000100000000115475216OPEN  CLC Import Sight IDR           IDROWN                0,00                      1600000100000000116911843OPEN  DGIRO OVERDRAFT BB PERORANGAN  IDROWN                0,00                      1410500100000000116911854OPEN  DGIRO CORP SPECIAL YIELD PERSH IDROWN       11.819.396,00                      1811600100000000114449651OPEN  DBNI TAPLUS                    IDROWN       97.473.000,00                      2000000100000000114454297OPEN  DBNI TAPLUS                    IDROWN      693.801.705,00                      2000000100000000114454333OPEN  DTAPLUS BISNIS PERORANGAN      IDROWN      209.376.993,00                      2300000100000000114455439OPEN  LKMK BNI MIDDLE                IDROWN      100.000.000,00                      1010070100000000114455451OPEN  LKMK BNI SMALL                 IDROWN      100.000.000,00                      1020070100000000114455609OPEN  LKI BNI KORPORASI IDR          IDROWN                0,00                      2010070100000000114455814OPEN  LKI BNI KORPORASI IDR          IDROWN      100.000.000,00                      2010070100000000114455949OPEN  LKMK BNI MIDDLE                IDROWN      100.000.000,00                      1010070100000000114456238OPEN  LKMK BNI MIDDLE                IDROWN      100.000.000,00                      1010070100000000114456793OPEN  LKMK BNI MIDDLE                IDROWN          434.146,00                      1010070100000000114459943OPEN  LKMK BNI MIDDLE                IDROWN                0,00                      1010070100000000114459954OPEN  LKMK BNI MIDDLE                IDROWN                0,00                      1010070100000000114459965OPEN  LKMK BNI MIDDLE                IDROWN                0,00                      1010070100000000114459976OPEN  LKMK BNI MIDDLE                IDROWN                0,00                      1010070100000000114460164OPEN  LKI BNI KORPORASI IDR          IDROWN      100.000.000,00                      2010070100000000114460175OPEN  LBNI GRIYA IND IDR             IDROWN      100.000.000,00                      3010020100000000114460618OPEN  LKMK BNI MIDDLE                IDROWN                0,00                      1010070100000000114487733OPEN  DBNI TAPLUS                    IDROWN       20.975.299,00                      2000000100000009144751232010000002Ibu SHERLOCK HOLMES                                         JALAN                   ]
```