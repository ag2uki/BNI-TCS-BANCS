# 37450 

Transaction code 0037450 is known as `GetCardByAccount`

Sample SOAP request:
```xml
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>AUTODB</systemId>
            <content xsi:type="bo:GetCardByAccountReq">
               <accountNum>0115471119</accountNum>
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
               <coreJournal>430005</coreJournal>
            </header>
            <content xsi:type="bo:GetCardByAccountRes">
               <accountNum>115471119</accountNum>
               <description>SAVINGS ACCOUNT</description>
               <accountType>00000001</accountType>
               <status>Active</status>
               <cardNum>5264222590456927</cardNum>
               <num>1</num>
               <cardStatus>Expired</cardStatus>
               <cardName>Bpk JONOMADE  IMAMADE</cardName>
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
               <balance>9899999927293400+</balance>
               <lastWithdrawal>2014-11-03</lastWithdrawal>
               <uneffectiveBalance>0697364782667100+</uneffectiveBalance>
               <lastTransaction>2014-11-03</lastTransaction>
               <minimumBalance>0000000000000000+</minimumBalance>
               <lastRefreshBalance>2018-08-29</lastRefreshBalance>
               <availableBalance>9202635144626300+</availableBalance>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs format message:
```
[ 0099                    **            003099299901001037450000000     0  I  0 000000  00000000115471119]


[ 0690    0606            0000    000000003099299901001037451301744000040320400 000000  03115471119          SAVINGS ACCOUNT
          00000001                                Active    5264222590456927    1         Expired             Bpk JONOMADE  IMAMADE
            5371762590003518    1         Normal              JONOMADE ADE



                9899999927293400+   03112014  0697364782667100+   03112014
  0000000000000000+   29082018  9202635144626300+Txn Code Txn Date
     Txn Amount                                        -------- ------------------- -----------------                                  ]
```