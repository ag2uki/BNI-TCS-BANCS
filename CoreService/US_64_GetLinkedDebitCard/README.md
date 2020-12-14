Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SMS</systemId>
            <content xsi:type="bo:GetLinkedDebitCardReq">
               <accountNum>0114462537</accountNum>
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
               <coreJournal>237117</coreJournal>
            </header>
            <content xsi:type="bo:CompiledGetLinkedDebitCardRes">
               <debitCard>
                  <cardName>JONOMADE  IMAMADE</cardName>
                  <cardType>BNI CARD PLATINUM</cardType>
                  <cardNum>00005198932590000381</cardNum>
                  <cardStatus>Normal</cardStatus>
                  <validFrom>31/12/14</validFrom>
                  <validTo>31/12/19</validTo>
               </debitCard>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0105                    **            003099200100001037460000000     0  I  0 000000  00000000114462537  0000]

[ 0164    0080            0000    000000003099200100001037460237125000040320000 000000  03Card Name                                Type & Status      Pan & Dates         ---------------------------------------- ------------------ --------------------JONOMADE  IMAMADE                        BNI CARD PLATINUM  00005198932590000381                                         Normal             31/12/14 - 31/12/19 ]
```