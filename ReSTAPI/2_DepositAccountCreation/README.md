# 002000

Transaction 002000 is known as `CreateDepositAccount`

Sample SOAP Request:
```xml
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:CreateDepositAccountReq">
               <accountNumber/>
               <cifNum>9100130666</cifNum>
               <idNumber>1234567890</idNumber>
               <idType>1</idType>
               <customerName>Ibu MAHATMA  DANDI</customerName>
               <Address1>PAMULANG 1</Address1>
               <Address2>1  1  PAMULANG SUITE</Address2>
               <npwp>N</npwp>
               <Address3>Pamulang</Address3>
               <nasionality>ID</nasionality>
               <Address4>PAMULANG MERDEKA</Address4>
               <postalCode>15417</postalCode>
               <accountType>2000</accountType>
               <subCategory>0001</subCategory>
               <interestPayMethod>R</interestPayMethod>
               <affAccount/>
               <freeFeeProfile/>
               <languageCode></languageCode>
               <accFrekuensi/>
               <accConsolidate/>
               <calendar/>
               <mailInd>1</mailInd>
               <noteInd>0</noteInd>
               <customerNotification/>
               <interestRate>0</interestRate>
               <interestFrekuensi/>
               <siklus/>
               <day/>
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
               <nominal>100000</nominal>
               <tierRateType/>
               <domesticRisk>09</domesticRisk>
               <limitationRisk>ZZ</limitationRisk>
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
               <openAccReason>2</openAccReason>
               <othersOpenAccReason/>
               <srcOfFund>1</srcOfFund>
               <othersSrcOfFund/>
               <projDep/>
               <projWdl/>
               <acctRatio>0</acctRatio>
               <BICNo/>
               <BICLimit>0</BICLimit>
               <sourceAccount>11223345</sourceAccount>
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
            <header>
               <coreJournal>076142</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>O.K. 003         11535283-9 0996 001 00001 00000000000001000+ 000000</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs format message:
```
[ 1055                    **
           003025900000161002000000000     0  I  0 000000  00000000000000000000000091007630873201020402970012        0001Bpk RASYID
                                 SURABAYA                                11                                      NGebang Putih 1
      ID Sukolilo           /Surabaya            60117   20000001   R   00000000000000000000004  09000000000000000000000000      0000000000000000
    000000000000000000                 00    000000000000000
   0000 00000000000000000+            01ZZZZBZZ
          00000000009 0000000+0     00000000000000000                   000000000000          00000007                    0003
        00000000755000000000000000000000000000000000000000000000000000000000000

   0000                                              99999999999999999]
   
[ 0162    0078            0000
000000003025900000161002000284448000040320200 000000  080000 O.K. 003
   100000878-4 0259 000 00161 00000000000000000+ 00000000000]
```