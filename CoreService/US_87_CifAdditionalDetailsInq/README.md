Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWMOBILE</systemId>
            <content xsi:type="bo:CifAdditionalDetailsInqReq">
               <institutionNum>3</institutionNum>
               <journalNum>730891</journalNum>
               <trxAmount>1853.910</trxAmount>
               <currency>USD</currency>
               <branch>265</branch>
               <tranCode>1045</tranCode>
               <trxDate>31052010</trxDate>
               <sourceAccount>116913862</sourceAccount>
               <destAccount>116913884</destAccount>
               <flag>X</flag>
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
               <coreJournal>730891</coreJournal>
            </header>
            <content xsi:type="bo:CifAdditionalDetailsInqRes">
               <institutionNum>3</institutionNum>
               <journalNum>730891</journalNum>
               <trxAmount>1853.910</trxAmount>
               <currency>USD</currency>
               <branch>265</branch>
               <tranCode>1045</tranCode>
               <trxDate>31052010</trxDate>
               <BICode></BICode>
               <beneficiaryStatus/>
               <beneficiaryCat/>
               <applStatus/>
               <applCat/>
               <recipientRelation/>
               <correspondentBank/>
               <purposeCode></purposeCode>
               <nationality></nationality>
               <sourceAccount>116913862</sourceAccount>
               <destAccount>116913884</destAccount>
               <flag>X</flag>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0164 ** 003099100100001060408000000 0 I 0 000000 00373089100000000001853910+USD265001045310520100000000011691386200000000116913884X]

[ 0234 0150 0000 000000003099100100001060409730891000040320600 000000 0300373089100000000001853910+USD26500104531052010 N1N1N1N1NID1000ID0000000011691386200000000116913884X ]
```