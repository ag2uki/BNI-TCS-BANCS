Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:InitCreateILAAccountReq">
               <cif_or_accntNumber>9100132052</cif_or_accntNumber>
               <idNumber/>
               <idType/>
               <system>ILA</system>
               <optionType/>
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
               <coreJournal>238684</coreJournal>
            </header>
            <content xsi:type="bo:InitCreateILAAccountRes">
               <accountNumber></accountNumber>
               <cifNum>9100132052</cifNum>
               <idNumber/>
               <idType/>
               <customerName>Bpk BAMBANG</customerName>
               <address1>JLN. SETIABUDI V NO 17 GG 2</address1>
               <address2>01 05</address2>
               <npwp>N</npwp>
               <address3>SETIABUDI</address3>
               <nationality>ID</nationality>
               <address4>Setia Budi</address4>
               <postalCode>12910</postalCode>
               <accountType></accountType>
               <subCategory></subCategory>
               <interestPayMethod/>
               <interestAffAccount></interestAffAccount>
               <freeFeeProfile></freeFeeProfile>
               <languageCode></languageCode>
               <accFrekuensi/>
               <accConsolidate/>
               <indTglStatus></indTglStatus>
               <correspondentInd/>
               <notificationInd/>
               <customerNotification></customerNotification>
               <interestRateVar>0</interestRateVar>
               <interestFrequency/>
               <siklus></siklus>
               <day></day>
               <agentCode></agentCode>
               <investmentType></investmentType>
               <address5></address5>
               <indGroup></indGroup>
               <accntNumber5></accntNumber5>
               <applicationID/>
               <defaultString19/>
               <defaultString20/>
               <defInteger7></defInteger7>
               <defInteger13></defInteger13>
               <defaultString21/>
               <unsigned08>0</unsigned08>
               <groupTierID/>
               <domesticRisk>08</domesticRisk>
               <crossRisk/>
               <crossBorderRisk/>
               <guarantieInd/>
               <termLimit/>
               <defaultString18/>
               <glClassfication/>
               <openDate>0000-00-00</openDate>
               <copySummary></copySummary>
               <notipros/>
               <extractionInd/>
               <appropriateRate>0</appropriateRate>
               <valasClausul></valasClausul>
               <valuta/>
               <interestChangeInd/>
               <herTaksasiInd/>
               <brokerNo1></brokerNo1>
               <defInteger8></defInteger8>
               <tprRate>0</tprRate>
               <certNo1/>
               <noIns/>
               <insuranceAccNo/>
               <openAcctRes/>
               <openAcctRes1/>
               <srcOfFund/>
               <srcOfFund1/>
               <projDep>0</projDep>
               <projWdl>0</projWdl>
               <acctRatio>0</acctRatio>
               <bicNo/>
               <bicLimit>0</bicLimit>
               <insuTerm/>
               <autoClose/>
               <autoPremium/>
               <monthPay>0</monthPay>
               <addCover/>
               <affiAcctNo/>
               <insuAcctNo/>
               <princArrears>0</princArrears>
               <premcArrears>0</premcArrears>
               <addSkim/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0131                    **            003099600100001062000000000     0  I  0 000000  00000009100132052                        0000ILA ]

[ 0709    0625            0000    000000003099600100001002085238684000040320600 000000  03                 00000009100132052                        0000Bpk BAMBANG                                                 JLN. SETIABUDI V NO 17 GG 2             01 05                                   NSETIABUDI                               ID Setia Budi                              12910                                                                                                                                                                                                              08                                                                                                                              ]
```