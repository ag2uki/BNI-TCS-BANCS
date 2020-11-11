# 0415

Transaction code 0415 is known as TermDepositRateInquiry

Sample SOAP request:
```xml
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:TermDepositRateInquiryReq">
               <amount>10000000</amount>
               <accountType>3901</accountType>
               <efektifDate/>
               <intMethod/>
               <frekuensi/>
               <period>12</period>
               <termBasis/>
               <page/>
               <intRate/>
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
               <coreJournal>237980</coreJournal>
            </header>
            <content xsi:type="bo:CompiledTermDepositRateInquiryRes">
               <rateDetails>
                  <kodeRate>1001</kodeRate>
                  <method>T</method>
                  <freq>M</freq>
                  <period>3</period>
                  <frekuensi>30D</frekuensi>
                  <termBasis></termBasis>
                  <nominalRate>0,00</nominalRate>
                  <termRate>1.0000</termRate>
                  <tierVal2></tierVal2>
                  <rate2></rate2>
               </rateDetails>
               <rateDetails>
                  <kodeRate>1501</kodeRate>
                  <method>T</method>
                  <freq>1A</freq>
                  <period>6</period>
                  <frekuensi>12M</frekuensi>
                  <termBasis></termBasis>
                  <nominalRate>0,00</nominalRate>
                  <termRate>1.0000</termRate>
                  <tierVal2></tierVal2>
                  <rate2></rate2>
               </rateDetails>
               <rateDetails>
                  <kodeRate>1511</kodeRate>
                  <method>R</method>
                  <freq>1A</freq>
                  <period>1</period>
                  <frekuensi>12M</frekuensi>
                  <termBasis></termBasis>
                  <nominalRate>0,00</nominalRate>
                  <termRate>1.0000</termRate>
                  <tierVal2></tierVal2>
                  <rate2></rate2>
               </rateDetails>
               <rateDetails>
                  <kodeRate>1521</kodeRate>
                  <method>T</method>
                  <freq>1A</freq>
                  <period>6</period>
                  <frekuensi>12M</frekuensi>
                  <termBasis></termBasis>
                  <nominalRate>0,00</nominalRate>
                  <termRate>1.0000</termRate>
                  <tierVal2></tierVal2>
                  <rate2></rate2>
               </rateDetails>
               <rateDetails>
                  <kodeRate>2501</kodeRate>
                  <method>A</method>
                  <freq>1A</freq>
                  <period>6</period>
                  <frekuensi>12M</frekuensi>
                  <termBasis></termBasis>
                  <nominalRate>0,00</nominalRate>
                  <termRate>1.0000</termRate>
                  <tierVal2></tierVal2>
                  <rate2></rate2>
               </rateDetails>
               <rateDetails>
                  <kodeRate>2901</kodeRate>
                  <method>A</method>
                  <freq>1A</freq>
                  <period>12</period>
                  <frekuensi>24M</frekuensi>
                  <termBasis></termBasis>
                  <nominalRate>0,00</nominalRate>
                  <termRate>1.0000</termRate>
                  <tierVal2></tierVal2>
                  <rate2></rate2>
               </rateDetails>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs formated message:
```
[ 0129                    **            003099600100001000415000000     0  I  0 000000  00000010000000000+390100000000    012 00000000+]

[ 0164    0080            0000    000000003099600100001000415237980000040320000 000000  031001TM    3  30D               0,00        1.0000                               

 0164    0080            0000    000000003099600100001000415237980000040320000 000000  031501T1A   6  12M               0,00        1.0000                               

 0164    0080            0000    000000003099600100001000415237980000040320000 000000  031511R1A   1  12M               0,00        1.0000                               

 0164    0080            0000    000000003099600100001000415237980000040320000 000000  031521T1A   6  12M               0,00        1.0000                               

 0164    0080            0000    000000003099600100001000415237980000040320000 000000  032501A1A   6  12M               0,00        1.0000                               

 0164    0080            0000    000000003099600100001000415237980000040320000 000000  032901A1A  12  24M               0,00        1.0000                               

 0164    0080            0000    000000003099600100001000415237980000040320000 000000  03JangkaWaktu         Nominal    Rate(%)    Diskon_Nominal                        1001TM    3  30D               0,00        1.0000                               1501T1A   6  12M               0,00        1.0000                               1511R1A   1  12M               0,00        1.0000                               1521T1A   6  12M               0,00        1.0000                               2501A1A   6  12M               0,00        1.0000                               2901A1A  12  24M               0,00        1.0000                               0000 O.K.                                                                     ]
```