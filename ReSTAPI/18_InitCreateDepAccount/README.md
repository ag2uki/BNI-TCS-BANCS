# 2000

Transaction code 2000 is known as CreateDepositAccount

Sample SOAP request:
```xml
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <customHeader>
               <branch>63</branch>
               <terminal>210</terminal>
               <teller>30011</teller>
               <systemJournal/>
               <overrideFlag>I</overrideFlag>
            </customHeader>
            <content xsi:type="bo:CreateDepositAccountReq">
               <accountNumber/>
               <cifNum>9100751913</cifNum>
               <idNumber>3271061512600001</idNumber>
               <idType>1</idType>
               <customerName>Bpk FAJAR NURCAHYO</customerName>
               <Address1>JALAN EBONY NO. 99</Address1>
               <Address2>9999KOMPLEK BUDIMAN SENTOSA</Address2>
               <npwp>Y</npwp>
               <Address3>Tanah Sareal</Address3>
               <nasionality>ID</nasionality>
               <Address4>Tanah Sereal       /Bogor</Address4>
               <postalCode>16161</postalCode>
               <accountType>2000</accountType>
               <subCategory>0001</subCategory>
               <interestPayMethod />
               <affAccount/>
               <freeFeeProfile/>
               <languageCode/>
               <accFrekuensi/>
               <accConsolidate/>
               <calendar/>
               <mailInd/>
               <noteInd/>
               <customerNotification/>
               <interestRate>0</interestRate>
               <interestFrekuensi/>
               <siklus/>
               <day>0</day>
               <agentCode/>
               <investType/>
               <address5/>
               <indGroup/>
               <fasilitationNo/>
               <applicationID/>
               <visaFlag/>
               <visaSecurityCode/>
               <visaCreditLimit/>
               <term/>
               <termBasis/>
               <nominal>1</nominal>
               <tierRateType/>
               <domesticRisk>17</domesticRisk>
               <limitationRisk/>
               <crossBorderRisk/>
               <indGuarante/>
               <timeLimit/>
               <vostroAcc/>
               <GLCode/>
               <date>0000-00-00</date>
               <copySummary/>
               <indNote/>
               <indAccountExtract/>
               <rate>0</rate>
               <klausaValas/>
               <valuta/>
               <indInterestChange/>
               <indHerTaksasi/>
               <brokerNo/>
               <bookingNo/>
               <trfPricingRate>0</trfPricingRate>
               <certificateNo/>
               <noIns/>
               <insurance/>
               <openAccReason>6</openAccReason>
               <othersOpenAccReason></othersOpenAccReason>
               <srcOfFund>2</srcOfFund>
               <othersSrcOfFund/>
               <projDep/>
               <projWdl/>
               <acctRatio>0</acctRatio>
               <BICNo/>
               <BICLimit>0</BICLimit>
               <sourceAccount>114479721</sourceAccount>
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
               <coreJournal>396539</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>O.K. 003         11450652-0 0063 210 30011 00000000000001000+ 000000</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs formated message:
```
[ 1055                    **            003006321030011002000000000     0  I  0 000000  00000000000000000000000091007519133271061512600001        0001Bpk FAJAR NURCAHYO                                          JALAN EBONY NO. 99                      9999KOMPLEK BUDIMAN SENTOSA             YTanah Sareal                            ID Tanah Sereal       /Bogor               16161   20000001   R   00000000000000000000004  01000000000000000000000000      0000000000000000       000000000000000000                 00    000000000000000                 0000 00000000000001000+            17  ZZBZZ                                     00000000000 0000000+0     00000000000000000                   000000000000          00000006                    0002                              00000000000000000000000000000000000000000000000000000000000000000000000                                                                                                                                                  0000                                              00000000114479721]

[ 0162    0078            0000    000000003006321030011002000396539000040320200 000000  080000 O.K. 003         11450652-0 0063 210 30011 00000000000001000+ 00000000000]
```