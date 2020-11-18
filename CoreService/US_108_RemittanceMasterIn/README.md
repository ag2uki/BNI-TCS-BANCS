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
            <systemId>GLOBS</systemId>
            <content xsi:type="bo:RemittanceMasterInReq">
               <transactionCode>PMT</transactionCode>
               <refferenceNum>S06ITR2000287714</refferenceNum>
               <counterAdvis>ITR000287</counterAdvis>
               <transactionType>CRD</transactionType>
               <transactionDate>2011-09-12+07:00</transactionDate>
               <transactionCurrency>IDR</transactionCurrency>
               <senderBank>ITR</senderBank>
               <toBank/>
               <bicCover>ALBISARIXXX</bicCover>
               <bicKIR>ALBISARIXXX</bicKIR>
               <correspondentReff>TESTCS300113</correspondentReff>
               <beneficiaryAccount>10508614</beneficiaryAccount>
               <beneficiaryName>BEN NAME</beneficiaryName>
               <beneficiaryAddress1>BEN ADD1</beneficiaryAddress1>
               <beneficiaryAddress2>BEN ADD2</beneficiaryAddress2>
               <beneficiaryAddress3>123456</beneficiaryAddress3>
               <senderName>ORD NAME</senderName>
               <senderAddress1>ORDER ADD1</senderAddress1>
               <senderAddress2>ORDER ADD2</senderAddress2>
               <senderAddress3>456789</senderAddress3>
               <news1>DET PO1</news1>
               <news2>DET PO2</news2>
               <detailCharge>BEN</detailCharge>
               <remittanceAmount>250000</remittanceAmount>
               <chargeAmount>5000</chargeAmount>
               <refundChargeAmount>5000</refundChargeAmount>
               <coverAccount>10508614</coverAccount>
               <amdCharges>0</amdCharges>
               <xtrCharges>0</xtrCharges>
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
               <coreJournal>237900</coreJournal>
            </header>
            <content xsi:type="bo:RemittanceMasterInRes">
               <responseResult>0</responseResult>
               <journalNumber>237900</journalNumber>
               <responseDateTime>3105201016:07:43</responseDateTime>
               <errorCode>0000</errorCode>
               <errorDesc/>
               <stp>MAN</stp>
               <nonstpDesc>BEN NAME UNMATCH</nonstpDesc>
               <account>000000001050861</account>
               <accountName>Sdri 9017966797 901796</accountName>
               <homeBranch>017</homeBranch>
               <currency>IDR</currency>
               <remitAmount>245000.00</remitAmount>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0748                    **            003076600100777029001000000     0  I  0 000000  PMTS06ITR2000287714ITR000287CRD12092011IDR ITR                                     ALBISARIXXXALBISARIXXXTESTCS300113    00000000010508614BEN NAME                           BEN ADD1                           BEN ADD2                           123456                             ORD NAME                           ORDER ADD1                         ORDER ADD2                         456789                             DET PO1                            DET PO2                                                                                                  BEN000000250000000000000050000000000000500000000000000105086140000000000000000000000000000000000000000000000]

[ 1043    0959            0000    000000003076600100777029001237900000040320000 000000  0302379003105201016:07:430000                                                  MANBEN NAME UNMATCH    000000001050861Sdri 9017966797 901796017IDR0000000024500000                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                0000 O.K.                                                                     ]
```