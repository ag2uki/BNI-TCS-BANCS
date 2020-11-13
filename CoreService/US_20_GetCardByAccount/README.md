Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>KSEI_AKSES</systemId>
            <content xsi:type="bo:GetCardByAccountReq">
               <accountNum>0000000114448749</accountNum>
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
               <coreJournal>396493</coreJournal>
            </header>
            <content xsi:type="bo:GetCardByAccountRes">
               <accountNum>114448749</accountNum>
               <description>SAVINGS ACCOUNT</description>
               <accountType>00000001</accountType>
               <status>Active</status>
               <cardNum>6010041002001443</cardNum>
               <num>1</num>
               <cardStatus>Normal</cardStatus>
               <cardName>Sdr I</cardName>
               <cardNum2/>
               <num2/>
               <cardStatus2/>
               <cardName2/>
               <cardNum3/>
               <num3>[</num3>
               <cardStatus3/>
               <cardName3/>
               <cardNum4/>
               <num4/>
               <cardStatus4/>
               <cardName4/>
               <balance>0000000000000000+</balance>
               <lastWithdrawal>2018-07-05</lastWithdrawal>
               <uneffectiveBalance>0000000000000000+</uneffectiveBalance>
               <lastTransaction>2018-07-05</lastTransaction>
               <minimumBalance>0000000000000000+</minimumBalance>
               <lastRefreshBalance>2018-07-05</lastRefreshBalance>
               <availableBalance>0000000000000000+</availableBalance>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```