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
            <content xsi:type="bo:LoanProcessInquiryReq">
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
               <coreJournal>650541</coreJournal>
            </header>
            <content xsi:type="bo:LoanProcessInquiryRes">
               <accountNum>114537297</accountNum>
               <customerNum>00000009100751913</customerNum>
               <idNumber>3271061512600001</idNumber>
               <idType>0001</idType>
               <customerName>Bpk FAJAR NURCAHYO</customerName>
               <borrowingType>0000</borrowingType>
               <borrowerGroup>01</borrowerGroup>
               <borrowerSubGroup>01</borrowerSubGroup>
               <interestRate>0</interestRate>
               <repIntConc>0</repIntConc>
               <repConcMov>0</repConcMov>
               <repConcAdj>0</repConcAdj>
               <intIncrMov>0</intIncrMov>
               <intIncrAdj>0</intIncrAdj>
               <duesStartDate>2010-05-31</duesStartDate>
               <intStartDate>2010-05-31</intStartDate>
               <intMethod/>
               <pendRate>0</pendRate>
               <pendDueDate>0000-00-00</pendDueDate>
               <pendDuesAmt>0</pendDuesAmt>
               <addLoanCode>0</addLoanCode>
               <addDuesAmt>0</addDuesAmt>
               <intCap>99.99</intCap>
               <interestTaxYTD>0</interestTaxYTD>
               <dischargePenaltyMths>0000</dischargePenaltyMths>
               <fixedRateDate>0000-00-00</fixedRateDate>
               <instlNotDays>0000</instlNotDays>
               <referralCode>0</referralCode>
               <reasonArrCde>00</reasonArrCde>
               <sourceCode>00</sourceCode>
               <settleFeeCode>Y</settleFeeCode>
               <misDebit1>0</misDebit1>
               <ledgerCode1>0</ledgerCode1>
               <subLedgerCode1>00</subLedgerCode1>
               <misDebit2>0</misDebit2>
               <ledgerCode2>0</ledgerCode2>
               <subLedgerCode2>00</subLedgerCode2>
               <misDebit3>0</misDebit3>
               <ledgerCode3>0</ledgerCode3>
               <subLedgerCode3>00</subLedgerCode3>
               <duesRecalcInd/>
               <baseRateRecalcInd>5</baseRateRecalcInd>
               <repayMeth/>
               <serialInterestRepay>01</serialInterestRepay>
               <serialInterestDay/>
               <fixedRateExpiryProduct>0000</fixedRateExpiryProduct>
               <ApprAvail>100000000.000</ApprAvail>
               <WDLimit>000</WDLimit>
               <tglPkAkhir>2011-04-01</tglPkAkhir>
               <tglPkAwal>2010-04-01</tglPkAwal>
               <noPkAkhir>121212121212121212121212121212</noPkAkhir>
               <noPkAwal>121212121212121212121212121212</noPkAwal>
               <namaAgent/>
               <namaProyek/>
               <nilaiProyek>0</nilaiProyek>
               <refRateType/>
               <refRateTenor/>
               <refRateMargin>0</refRateMargin>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0099                    **            003098900100099017051000000     0  I  0 000000  00000000114537297]

[ 0720    0636            0000    000000003098900100099017001650541000040320600 000000  0300000000114537297000000091007519133271061512600001        0001Bpk FAJAR NURCAHYO                                          000001010000000+0000000+0000000+0000000+0000000+0000000+3105201031052010 0000000+0000000000000000000000000+000000000000000000+999900000000000000000+000000000000000000000Y 000000000+000000000000+000000000000+000 2 01  000000000100000000000+0000104201101042010121212121212121212121212121212121212121212121212121212121212                                                                                                                                                                00000000000000000+    0000000+4  N31]
```