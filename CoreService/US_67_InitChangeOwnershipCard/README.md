Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SYARIAH</systemId>
            <customHeader>
               <branch>259</branch>
               <terminal>452</terminal>
               <teller>24113</teller>
               <overrideFlag/>
               <supervisorId/>
            </customHeader>
            <content xsi:type="bo:InitChangeOwnershipCardReq">
               <cardNum>5264230630052564</cardNum>
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
               <coreJournal>565405</coreJournal>
            </header>
            <content xsi:type="bo:InitChangeOwnershipCardRes">
               <cardNum>5264230630052564</cardNum>
               <cardDescription>Kartu Taplus Muda - Generik</cardDescription>
               <oldCifNum>555555555</oldCifNum>
               <name>KARTU INSTANT</name>
               <address1/>
               <address2/>
               <address3/>
               <address4/>
               <postCode/>
               <cardName>KARTU INSTANT</cardName>
               <issueCard>09012019</issueCard>
               <expiredCard>31122023</expiredCard>
               <newCifNum/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0101                    **            003025945224113037206000000     0     0 000000  0005264230630052564]

[ 0521    0437            0000    000201003025920124113037207565405000040320600 000000  035264230630052564    Kartu Taplus Muda - Generik   555555555                     KARTU INSTANT                                                                                                                                                                                                                                                       KARTU INSTANT                                               09012019  31122023                   ]
```