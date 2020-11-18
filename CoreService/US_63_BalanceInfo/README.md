Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>IBANK</systemId>
            <systemJournal/>
            <content xsi:type="bo:BalanceInfoReq">
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
               <coreJournal>000000</coreJournal>
            </header>
            <content xsi:type="bo:BalanceInfoRes">
               <customerName>Bpk JONOMADE MADEMADEMADEMADE IMAMADE</customerName>
               <currency>IDR</currency>
               <balance>121402163328.00</balance>
               <status>BUKA</status>
               <accountType>DEP</accountType>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0099                    **            003099600100001069440000000     0  I  0 000000  00000000114462537]

[ 1042    0958            0000    000000003099600100001032001000000000040320400 000000  03          11446253-7IDRBNI TAPLUS                    0100..0.0.............1.BUKA00000000    01                                                            Bpk JONOMADE MADEMADEMADEMADE IMAMADE                       BENDI VII NO 14                                       0,00                                                       0,00 kebayoran                                             0,00 Kebayoran Baru                          12120                 0,00 31052010   3,0000 0,0000              0,00 121.402.163.328,00                    99/99/9999  1.699.504.381,00-              0,00              0              0,00     10105270,55516 31052010                0,00     10105270,55516 31052010                0,00     10144386,06341 31052010  00000                                                       00                     0                        0,000099999999              ,00000 121.402.163.328,00 SETOR 0                  0                  14937 ]
```