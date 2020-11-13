Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>ATM</systemId>
            <content xsi:type="bo:AtmCardlessDepositTransferReq">
               <toAcctNo>114479721</toAcctNo>
               <amount>15000</amount>
               <clearCode></clearCode>
               <tranDate>31052010</tranDate>
               <baseCurrAmt>1</baseCurrAmt>
               <sysDate>31052010</sysDate>
               <bin>601004</bin>
               <refference>9999KOMPLEK BUDIMAN SENTOSA</refference>
               <merchant>Tanah Sareal</merchant>
               <country>ID</country>
               <postTime>31052010</postTime>
               <termId>00000000</termId>
               <termAddress>00000000</termAddress>
               <branch>0063</branch>
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
               <coreJournal>564140</coreJournal>
            </header>
            <content xsi:type="bo:AtmCardlessDepositTransferRes">
               <accountNum>00000000114479721</accountNum>
               <date>2019062010032301</date>
               <cif>00000009100751913</cif>
               <ledgerBalance>00005382001064000+</ledgerBalance>
               <availableBalance>00005362188064000+</availableBalance>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```