Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>BNIDIRECT</systemId>
            <content xsi:type="bo:LoanInterestReq">
               <accountNum>114449083</accountNum>
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
               <coreJournal>574744</coreJournal>
            </header>
            <content xsi:type="bo:LoanInterestRes">
               <accountNum>114449083</accountNum>
               <collectibility>01:PASS</collectibility>
               <collectibilityMaintainedDate>9999-99-99</collectibilityMaintainedDate>
               <writtenOffDate>9999-99-99</writtenOffDate>
               <outArrearsDate>9999-99-99</outArrearsDate>
               <industryCode>912</industryCode>
               <subSectorCode>0</subSectorCode>
               <seqmentCode/>
               <suspendedInterest>0</suspendedInterest>
               <insuranceClaim>0</insuranceClaim>
               <writtenOffInterest>0</writtenOffInterest>
               <principleInterestAmount>0</principleInterestAmount>
               <InterestInstallmentAmount>0</InterestInstallmentAmount>
               <previousInterestAccrual>0</previousInterestAccrual>
               <prevArrearsInterestAccrual>0</prevArrearsInterestAccrual>
               <holidayRepayment/>
               <holidayRepaymentTotal>12</holidayRepaymentTotal>
               <fundType>4</fundType>
               <channelExecution/>
               <syndicateType/>
               <kukCode>Y</kukCode>
               <nextReviewDate>2011-05-31</nextReviewDate>
               <agreementNum>4656564</agreementNum>
               <effectiveDate>9999-99-99</effectiveDate>
               <approvedAmount>150000000.000</approvedAmount>
               <maturityPenalty>0</maturityPenalty>
               <totalPPA>0</totalPPA>
               <afiliatedAccount/>
               <worstCollectibility>01:PASS</worstCollectibility>
               <maintananceFee>0</maintananceFee>
               <penaltyRate>7.0000</penaltyRate>
               <rahnAkum>0</rahnAkum>
               <rahnHarian>0</rahnHarian>
               <pengurangPPA>0</pengurangPPA>
               <talangan>0</talangan>
               <sisaPokokIjaroh>0</sisaPokokIjaroh>
               <sisaFeeIjaroh>0</sisaFeeIjaroh>
               <applicationNum/>
               <rmCode/>
               <fixRateDate>9999-99-99</fixRateDate>
               <subsidyRate>0</subsidyRate>
               <economicSectorCode>9120</economicSectorCode>
               <economicSectorQual>00</economicSectorQual>
               <grecePeriodType/>
               <gracePeriodDate>9999-99-99</gracePeriodDate>
               <gracePeriod/>
               <interestDayCap>25</interestDayCap>
               <multifinanceCode/>
               <purpCode>002</purpCode>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0099                    **            003098900100001010455000000     0  I  0 000000  00000000114449083]

[ 0668    0584            0000    000000003098900100001010456288198000040320600 000000  030000000011444908301:PASS             9999999999999999999999999120000000000000000000+00000000000000000+00000000000000000+00000000000000000+00000000000000000+00000000000000000+00000000000000000+000124  Y310520114656564                       9999999900000150000000000+00000000000000000+00000000000000000+0000000000000000001:PASS                               0070000+00000000000000000+00000000000000000+00000000000000000+00000000000000000+                                                                  999999990000912000 99999999000025   00200000000000000000+                         ]
```