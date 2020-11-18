Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:InquiryChequeReq">
               <accountNo>115469575</accountNo>
               <chequePrefix/>
               <chequeFirstNo/>
               <status/>
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
               <coreJournal>237468</coreJournal>
            </header>
            <content xsi:type="NS_BO:CompiledInquiryChequeRes" xmlns:NS_BO="http://service.bni.co.id/core/bo">
               <chequeInfo>
                  <chequeNo>CA151511</chequeNo>
                  <numberofCheques>00025</numberofCheques>
                  <status>P</status>
                  <availableCheque>00002</availableCheque>
                  <bookType>1025</bookType>
                  <branchCode>0259</branchCode>
                  <issuedDate>31052010</issuedDate>
               </chequeInfo>
               <chequeInfo>
                  <chequeNo>CB414111</chequeNo>
                  <numberofCheques>00025</numberofCheques>
                  <status>P</status>
                  <availableCheque>00024</availableCheque>
                  <bookType>1025</bookType>
                  <branchCode>0259</branchCode>
                  <issuedDate>31052010</issuedDate>
               </chequeInfo>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0108                    **            003099600100001052211000000     0  I  0 000000  00000000115469575         ]

[ 0119    0035            0000    000000003099600100001052211237468000040320000 000000  03CA15151100025P000021025025931052010CB41411100025P0002410250259310520100000 O.K.                                                                     ]
```