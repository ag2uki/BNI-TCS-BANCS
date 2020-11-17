Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>KSEI_AKSES</systemId>
            <content xsi:type="bo:GetCardByAccountReq">
               <accountNum>114479721</accountNum>
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
               <coreJournal>319026</coreJournal>
            </header>
            <content xsi:type="bo:GetCardByAccountRes">
               <accountNum>114479721</accountNum>
               <description>SAVINGS ACCOUNT</description>
               <accountType>00000001</accountType>
               <status>Active</status>
               <cardNum>5264222590517835</cardNum>
               <num>1</num>
               <cardStatus>Normal</cardStatus>
               <cardName>FAJAR  NURCAHYO</cardName>
               <cardNum2/>
               <num2/>
               <cardStatus2/>
               <cardName2/>
               <cardNum3/>
               <num3/>
               <cardStatus3/>
               <cardName3/>
               <cardNum4/>
               <num4/>
               <cardStatus4/>
               <cardName4/>
               <balance>0600566870092800+</balance>
               <lastWithdrawal>2018-12-31</lastWithdrawal>
               <uneffectiveBalance>0000001436910000+</uneffectiveBalance>
               <lastTransaction>2018-12-31</lastTransaction>
               <minimumBalance>0000000000000000+</minimumBalance>
               <lastRefreshBalance>2020-03-23</lastRefreshBalance>
               <availableBalance>0600565433182800+</availableBalance>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0099                    **            003098700100001037450000000     0  I  0 000000  00000000114479721]

Response :
[ 0690    0606            0000    000000003098700100001037451319026000040320400 000000  03114479721          SAVINGS ACCOUNT               00000001                                Active    5264222590517835    1         Normal              FAJAR  NURCAHYO                                                                                                                                                                                                                                                                                                                                               0600566870092800+   31122018  0000001436910000+   31122018  0000000000000000+   23032020  0600565433182800+Txn Code Txn Date             Txn Amount                                        -------- ------------------- -----------------                                  ]
```