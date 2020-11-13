Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:OpenLoanAccountListReq">
               <cifNum>9100202500</cifNum>
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
               <coreJournal>298702</coreJournal>
            </header>
            <content xsi:type="bo:CompiledOpenLoanAccountListRes">
               <cifNum>00000009100202500</cifNum>
               <customerName>Bpk FAJAR ARIF FAJAR ARIF BUDIMAN, SE.MM</customerName>
               <keyPerson></keyPerson>
               <noDIN></noDIN>
               <noHP>08129942310</noHP>
               <curr>IDR</curr>
               <totAprvAmt>0,00</totAprvAmt>
               <totOutstd>0,00</totOutstd>
               <totArrear>0,00</totArrear>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```