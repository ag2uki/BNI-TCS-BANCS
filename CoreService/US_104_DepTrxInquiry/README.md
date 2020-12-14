Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>BNIDIRECT</systemId>
            <content xsi:type="bo:DepTrxInquiryReq">
               <accountNum>114479721</accountNum>
               <fromDate>2010-05-31</fromDate>
               <toDate>2010-05-31</toDate>
               <journalNum/>
               <branchNum/>
               <amount>0</amount>
               <starttime>0000</starttime>
               <endtime>2400</endtime>
               <transactionType>FI</transactionType>
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
            <content xsi:type="bo:CompiledDepTrxInquiryRes">
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>997</branchNum>
                  <terminalNum>2</terminalNum>
                  <tellerNum>4</tellerNum>
                  <transactionCode>4055</transactionCode>
                  <postDateTime>2010-05-31T14:20:28Z</postDateTime>
                  <journalNum>323045</journalNum>
                  <narative>TRF/PAY/TOP-UP ECH</narative>
                  <amount>-2500.00</amount>
                  <balance>326963696889.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>997</branchNum>
                  <terminalNum>2</terminalNum>
                  <tellerNum>4</tellerNum>
                  <transactionCode>4055</transactionCode>
                  <postDateTime>2010-05-31T14:20:28Z</postDateTime>
                  <journalNum>323045</journalNum>
                  <narative>TRF/PAY/TOP-UP ECH</narative>
                  <amount>-500000.00</amount>
                  <balance>326963699389.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>997</branchNum>
                  <terminalNum>2</terminalNum>
                  <tellerNum>4</tellerNum>
                  <transactionCode>4155</transactionCode>
                  <postDateTime>2010-05-31T11:31:01Z</postDateTime>
                  <journalNum>322681</journalNum>
                  <narative>KOR TRF/PAY/TOP-UP</narative>
                  <amount>2500.00</amount>
                  <balance>326964199389.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>997</branchNum>
                  <terminalNum>2</terminalNum>
                  <tellerNum>4</tellerNum>
                  <transactionCode>4155</transactionCode>
                  <postDateTime>2010-05-31T11:31:01Z</postDateTime>
                  <journalNum>322681</journalNum>
                  <narative>KOR TRF/PAY/TOP-UP</narative>
                  <amount>65000.00</amount>
                  <balance>326964196889.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>997</branchNum>
                  <terminalNum>2</terminalNum>
                  <tellerNum>4</tellerNum>
                  <transactionCode>4055</transactionCode>
                  <postDateTime>2010-05-31T11:31:01Z</postDateTime>
                  <journalNum>322680</journalNum>
                  <narative>TRF/PAY/TOP-UP ECH</narative>
                  <amount>-2500.00</amount>
                  <balance>326964131889.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>997</branchNum>
                  <terminalNum>2</terminalNum>
                  <tellerNum>4</tellerNum>
                  <transactionCode>4055</transactionCode>
                  <postDateTime>2010-05-31T11:31:01Z</postDateTime>
                  <journalNum>322680</journalNum>
                  <narative>TRF/PAY/TOP-UP ECH</narative>
                  <amount>-65000.00</amount>
                  <balance>326964134389.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>997</branchNum>
                  <terminalNum>2</terminalNum>
                  <tellerNum>4</tellerNum>
                  <transactionCode>4155</transactionCode>
                  <postDateTime>2010-05-31T11:13:00Z</postDateTime>
                  <journalNum>322632</journalNum>
                  <narative>KOR TRF/PAY/TOP-UP</narative>
                  <amount>22500.00</amount>
                  <balance>326964199389.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>997</branchNum>
                  <terminalNum>2</terminalNum>
                  <tellerNum>4</tellerNum>
                  <transactionCode>4055</transactionCode>
                  <postDateTime>2010-05-31T11:13:00Z</postDateTime>
                  <journalNum>322631</journalNum>
                  <narative>TRF/PAY/TOP-UP ECH</narative>
                  <amount>-22500.00</amount>
                  <balance>326964176889.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>997</branchNum>
                  <terminalNum>2</terminalNum>
                  <tellerNum>4</tellerNum>
                  <transactionCode>4155</transactionCode>
                  <postDateTime>2010-05-31T10:57:53Z</postDateTime>
                  <journalNum>322586</journalNum>
                  <narative>KOR TRF/PAY/TOP-UP</narative>
                  <amount>150000.00</amount>
                  <balance>326964199389.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0101                    **            003099600100001060583000000     0  I  0 000000  0000000915494130101]

[ 0253    0169            0000    000000003099600100001060584325165000040320400 000000  0300000009154941301Sdr HAN HAN SOLO                                                                                                                                        00000000116956409BUKAIBNI TAPLUS TAX AMNESTY        IDROWN        9.549.694,00                0,00  20001001      9.549.694,00                      0718000000000116989571BUKAIBNI TAPLUS                    IDROWN          300.000,00                0,00  20000001        300.000,00                      0718000000000114444711BUKAITAPLUS BISNIS PERORANGAN      IDROWN                0,00                0,00  23000001              0,00                      0259000000000114469112BUKAIBNI TAPLUS                    IDROWN  323.844.042.824,00                0,00  20000001323.844.042.824,00                      0100000000000114551472BUKAIBNI TAPLUS                    IDROWN           36.500,00                0,00  20000001         36.500,00                      0100100000000114553004BUKAIDEPOSITO KAPITALISASI 1 IDR   IDROWN       10.000.000,00                0,00  32010001     10.000.000,00                      0100100000000114758308BUKAIBNI TAPLUS                    IDROWN          496.500,00                0,00  20000001        496.500,00                      0100100000000114758397BUKAIBNI TAPLUS                    IDROWN          600.000,00                0,00  20000001        600.000,00                      0100100000000114758885BUKAIBNI TAPLUS                    IDROWN          600.000,00                0,00  20000001        600.000,00                      0100100000000114788457BUKAIBNI TAPLUS                    IDROWN        1.000.000,00                0,00  20000001      1.000.000,00                      0100100000000114789711BUKAIBNI TAPLUS                    IDROWN          896.500,00                0,00  20000001        896.500,00                      0100100000000114791378BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000113165035BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000116954515BUKAIBNI TAPLUS                    IDROWN        3.299.989,00                0,00  20000001      3.299.989,00                      0718000000000116956556BUKAIBNI TAPLUS TAX AMNESTY        IDROWN          350.000,00                0,00  20001001        350.000,00                      0718000000000116989605BUKAIBNI TAPLUS TAX AMNESTY        IDROWN          756.000,00                0,00  20001001        756.000,00                      0718000000000114444722BUKAITAPLUS BISNIS CO BRAND LOTTE  IDROWN                0,00                0,00  23030001              0,00                      0259000000000114469123BUKAIBNI TAPLUS                    IDROWN                0,00                0,00  20000001              0,00                      0100000000000114551483BUKAITAPLUS BISNIS PERORANGAN      IDROWN          745.000,00                0,00  23000001        745.000,00                      0100100000000114587330BUKAIDEPOSITO KAPITALISASI 1 IDR   IDROWN       10.000.000,00                0,00  32010001     10.000.000,00                      0259100000000114758320BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000114758400BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000114758896BUKAIBNI TAPLUS                    IDROWN          700.000,00                0,00  20000001        700.000,00                      0100100000000114788480BUKAIBNI TAPLUS                    IDROWN        1.000.000,00                0,00  20000001      1.000.000,00                      0100100000000114791243BUKAIBNI TAPENAS                   IDROWN        1.000.000,00                0,00  28000001      1.000.000,00                      0100100000000114791389BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000113165046BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000116954526BUKAIBNI TAPLUS TAX AMNESTY        IDROWN          140.000,00                0,00  20001001        140.000,00                      0718000000000116981447BUKAIBNI TAPLUS TAX AMNESTY        IDROWN                0,00                0,00  20001001              0,00                      0718000000000116989718BUKAIBNI TAPLUS TAX AMNESTY        IDROWN        1.050.000,00                0,00  20001001      1.050.000,00                      0718000000000114450292BUKAIBNI TAPENAS                   IDROWN          500.000,00                0,00  28000001        500.000,00                      0718100000000114469134DORMIBNI TAPLUS                    IDROWN   21.312.981.213,00                0,00  20000001 21.312.981.213,00                      0100000000000114551494BUKAIBNI TAPENAS                   IDROWN          100.000,00                0,00  28000001        100.000,00                      0100100000000114587341BUKAIDEPOSITO KAPITALISASI 1 IDR   IDROWN       10.000.000,00                0,00  32010001     10.000.000,00                      0100100000000114758331BUKAIBNI TAPLUS                    IDROWN          600.000,00                0,00  20000001        600.000,00                      0100100000000114758422BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000114758909BUKAIBNI TAPLUS                    IDROWN          800.000,00                0,00  20000001        800.000,00                      0100100000000114788854BUKAIBNI TAPLUS                    IDROWN        1.000.000,00                0,00  20000001      1.000.000,00                      0100100000000114791298BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000113164676BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000113165057BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000116954537BUKAITAB BNI DOLLAR TAX AMNESTY USDUSDOWN            2.617,95                0,00  20041002          2.617,95                      0718000000000116989286BUKAIBNI TAPLUS TAX AMNESTY        IDROWN        2.381.000,00                0,00  20001001      2.381.000,00                      0718000000000116989729BUKAIBNI TAPLUS TAX AMNESTY        IDROWN        3.000.000,00                0,00  20001001      3.000.000,00                      0718000000000114454286BUKAIBNI TAPLUS                    IDROWN   40.979.338.192,00                0,00  20000001 40.979.338.192,00                      0259000000000114469156DORMIBNI TAPLUS                    IDROWN   31.214.081.312,00                0,00  20000001 31.214.081.312,00                      0100000000000114551507BUKAIBNI TAPENAS                   IDROWN          100.000,00                0,00  28000001        100.000,00                      0100100000000114587352BUKAIDEPOSITO KAPITALISASI 1 IDR   IDROWN       10.000.000,00                0,00  32010001     10.000.000,00                      0100100000000114758342BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000114758433BUKAIBNI TAPLUS                    IDROWN          600.000,00                0,00  20000001        600.000,00                      0100100000000114758910BUKAIBNI TAPLUS                    IDROWN          900.000,00                0,00  20000001        900.000,00                      0100100000000114788876BUKAIBNI TAPLUS                    IDROWN        1.000.000,00                0,00  20000001      1.000.000,00                      0100100000000114791301BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000113164949BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0718100000000113165068BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000116955790BUKAIGIRO TDK HIT BBB PERUSAHAAN   IDROWN                0,00                0,00  10110001              0,00                      0718000000000116989300BUKAIBNI TAPLUS TAX AMNESTY        IDROWN          381.000,00                0,00  20001001        381.000,00                      0718000000000116989730BUKAIBNI TAPLUS                    IDROWN                0,00                0,00  20000001              0,00                      0718000000000114461645BUKAITAB BNI DOLLAR PERORANGAN USD USDOWN              715,88                0,00  20040002            715,88                      0259000000000114469167DORMIBNI TAPLUS                    IDROWN   21.172.752.113,00                0,00  20000001 21.172.752.113,00                      0100000000000114591482BUKAIDEPOSITO KAPITALISASI 1 IDR   IDROWN       10.000.000,00                0,00  32010001     10.000.000,00                      0100100000000114758353BUKAIBNI TAPLUS                    IDROWN          600.000,00                0,00  20000001        600.000,00                      0100100000000114758444BUKAIBNI TAPLUS                    IDROWN        1.000.000,00                0,00  20000001      1.000.000,00                      0100100000000114788286BUKAIBNI TAPLUS                    IDROWN        1.000.000,00                0,00  20000001      1.000.000,00                      0100100000000114788887BUKAIBNI TAPLUS                    IDROWN        1.000.000,00                0,00  20000001      1.000.000,00                      0100100000000114791334BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000113164950BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000113165079BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000116989366BUKAIBNI TAPLUS TAX AMNESTY        IDROWN        5.250.000,00                0,00  20001001      5.250.000,00                      0718000000000114444686BUKAIGIRO TDK HIT BBB PERORANGAN   IDROWN                0,00                0,00  10100001              0,00                      0259000000000114469087BUKAIBNI TAPLUS                    IDROWN      346.909.900,00                0,00  20000001    346.909.900,00                      0100000000000114469178DORMIBNI TAPLUS                    IDROWN  132.132.290.321,00                0,00  20000001132.132.290.321,00                      0100000000000114552487BUKAIPINJAMAN DARI DEPKOR DN IDR   IDROWN                0,00                0,00  75550501              0,00                      0259000000000114755090BUKAIBNI TAPENAS                   IDROWN          100.000,00                0,00  28000001        100.000,00                      0100100000000114758364BUKAIBNI TAPLUS                    IDROWN          700.000,00                0,00  20000001        700.000,00                      0100100000000114758502BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000114788297BUKAIBNI TAPLUS                    IDROWN        1.000.000,00                0,00  20000001      1.000.000,00                      0100100000000114788898BUKAIBNI TAPLUS                    IDROWN        1.000.000,00                0,00  20000001      1.000.000,00                      0100100000000114791345BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000113164961BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000116956385BUKAIBNI TAPLUS TAX AMNESTY        IDROWN        1.475.000,00                0,00  20001001      1.475.000,00                      0718000000000116989388BUKAIBNI TAPLUS TAX AMNESTY        IDROWN        3.240.000,00                0,00  20001001      3.240.000,00                      0718000000000114444697BUKAIGIRO TDK HIT BBB PERORANGAN   IDROWN                0,00                0,00  10100001              0,00                      0259000000000114469098BUKAIBNI TAPLUS                    IDROWN  213.148.961.321,00                0,00  20000001213.148.961.321,00                      0100000000000114483284DORMIGIRO TANPA SO MIN TRX DB TERBTIDROWN                0,00                0,00  18116101              0,00                      0259000000000114552975BUKAITAPLUS BISNIS CO BRAND LOTTE  IDROWN          200.000,00                0,00  23030001        200.000,00                      0100100000000114755147BUKAIBNI TAPENAS                   IDROWN          100.000,00                0,00  28000001        100.000,00                      0100100000000114758375BUKAIBNI TAPLUS                    IDROWN          800.000,00                0,00  20000001        800.000,00                      0100100000000114758670BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000114788377BUKAIBNI TAPLUS                    IDROWN        1.000.000,00                0,00  20000001      1.000.000,00                      0100100000000114788901BUKAIBNI TAPLUS                    IDROWN        1.000.000,00                0,00  20000001      1.000.000,00                      0100100000000114791356BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000113164972BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000116956396BUKAITAB BNI DOLLAR TAX AMNESTY USDUSDOWN            1.580,00                0,00  20041002          1.580,00                      0718000000000116989446BUKAIBNI TAPLUS TAX AMNESTY        IDROWN       10.000.000,00                0,00  20001001     10.000.000,00                      0718000000000114444700BUKAIGIRO TDK HIT BBB PERORANGAN   IDROWN                0,00                0,00  10105001              0,00                      0259000000000114469101BUKAIEMERALD SAVING                IDROWN  200.100.075.000,00                0,00  23010001    100.075.000,00                      0100000000000114501907BUKAIBNI TAPLUS                    IDROWN          310.000,00                0,00  20000001        310.000,00                      0259100000000114552986BUKAIDEPOSITO KAPITALISASI 1 IDR   IDROWN       10.000.000,00                0,00  32010001     10.000.000,00                      0100100000000114758295BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000114758386BUKAIBNI TAPLUS                    IDROWN          700.000,00                0,00  20000001        700.000,00                      0100100000000114758874BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000114788435BUKAIBNI TAPLUS                    IDROWN        1.000.000,00                0,00  20000001      1.000.000,00                      0100100000000114789700BUKAIBNI TAPLUS                    IDROWN        1.000.000,00                0,00  20000001      1.000.000,00                      0100100000000114791367BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      0100100000000113164983BUKAIBNI TAPLUS                    IDROWN          500.000,00                0,00  20000001        500.000,00                      01001]
```