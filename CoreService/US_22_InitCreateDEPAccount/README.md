Sample SOAP Request
```
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Body>
      <transaction xmlns="http://service.bni.co.id/core" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
         <request xmlns="">
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:InitCreateDEPAccountReq" xmlns:bo="http://service.bni.co.id/core/bo">
               <cif_or_accntNumber>114479721</cif_or_accntNumber>
               <idNumber></idNumber>
               <idType></idType>
               <system>DEP</system>
               <optionType/>
            </content>
         </request>
      </transaction>
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
               <coreJournal>396512</coreJournal>
            </header>
            <content xsi:type="bo:InitCreateDEPAccountRes">
               <accountNumber></accountNumber>
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
               <accountType></accountType>
               <subCategory></subCategory>
               <interestPayMethod/>
               <affAccount></affAccount>
               <freeFeeProfile></freeFeeProfile>
               <languageCode></languageCode>
               <accFrekuensi/>
               <accConsolidate/>
               <calendar></calendar>
               <mailInd/>
               <noteInd/>
               <customerNotification></customerNotification>
               <interestRate>0</interestRate>
               <interestFrekuensi/>
               <siklus></siklus>
               <day></day>
               <agentCode></agentCode>
               <investType></investType>
               <address5></address5>
               <indGroup></indGroup>
               <fasilitationNo></fasilitationNo>
               <applicationID/>
               <visaFlag/>
               <visaSecurityCode/>
               <visaCreditLimit></visaCreditLimit>
               <term></term>
               <termBasis/>
               <nominal>0</nominal>
               <tierRateType/>
               <domesticRisk>17</domesticRisk>
               <limitationRisk/>
               <crossBorderRisk/>
               <indGuarante/>
               <timeLimit/>
               <vostroAcc/>
               <GLCode/>
               <date>0000-00-00</date>
               <copySummary></copySummary>
               <indNote/>
               <indAccountExtract/>
               <rate>0</rate>
               <klausaValas></klausaValas>
               <valuta/>
               <indInterestChange/>
               <indHerTaksasi/>
               <brokerNo></brokerNo>
               <bookingNo></bookingNo>
               <trfPricingRate>0</trfPricingRate>
               <certificateNo/>
               <noIns/>
               <insurance/>
               <openAccReason/>
               <othersOpenAccReason/>
               <srcOfFund/>
               <othersSrcOfFund/>
               <projDep/>
               <projWdl/>
               <acctRatio>0</acctRatio>
               <BICNo/>
               <BICLimit>0</BICLimit>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```