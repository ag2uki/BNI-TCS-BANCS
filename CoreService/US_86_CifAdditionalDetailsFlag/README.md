Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWMOBILE</systemId>
            <content xsi:type="bo:CifAdditionalDetailsFlagReq">
               <institutionNum>3</institutionNum>
               <journalNum>730891</journalNum>
               <trxAmount>1853.910</trxAmount>
               <currency>USD</currency>
               <branch>265</branch>
               <tranCode>1045</tranCode>
               <trxDate>31052010</trxDate>
               <BICode>  </BICode> <!-- hardcode utk flag X -->
               <beneficiaryStatus>N1</beneficiaryStatus> <!-- hardcode utk flag X -->
               <beneficiaryCat>N1</beneficiaryCat><!-- hardcode utk flag X -->
               <applStatus>N1</applStatus> <!-- hardcode utk flag X -->
               <applCat>N1</applCat> <!-- hardcode utk flag X -->
               <recipientRelation>N</recipientRelation> <!-- hardcode utk flag X -->
               <correspondentBank>ID</correspondentBank><!-- hardcode utk flag X -->
               <purposeCode>1000</purposeCode><!-- hardcode utk flag X -->
               <nationality>ID</nationality><!-- hardcode utk flag X -->
               <trxPurpose>07</trxPurpose>
               <documentType>999</documentType>
               <documentNum>999</documentNum>
               <sourceAccount>116913862</sourceAccount>
               <destAccount>116913884</destAccount>
               <flag>X</flag>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>
<!--flag X untuk transaksi transfer valas-->
```

Sample SOAP Response
```
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header>
               <coreJournal>730891</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>O.K.</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```