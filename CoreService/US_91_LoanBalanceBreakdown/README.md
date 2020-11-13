Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>BNIDIRECT</systemId>
            <content xsi:type="bo:LoanBalanceBreakdownReq">
               <accountNum>114449083</accountNum>
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
            <content xsi:type="bo:LoanBalanceBreakdownRes">
               <accountNum>11444908-3</accountNum>
               <saldoPokok>0,00</saldoPokok>
               <tunggakanPokok>150.000.000,00-</tunggakanPokok>
               <saldoBunga>0,00</saldoBunga>
               <tunggakanBunga>0,00</tunggakanBunga>
               <saldoBiaya>0,00</saldoBiaya>
               <tunggakanBiaya>0,00</tunggakanBiaya>
               <saldoDenda>0,00</saldoDenda>
               <tunggakanDenda>0,00</tunggakanDenda>
               <saldoBiayaProvisi>0,00</saldoBiayaProvisi>
               <tunggakanBiayaProvisi>0,00</tunggakanBiayaProvisi>
               <saldoTotal>1.750.000,00</saldoTotal>
               <tunggakanTotal>148.250.000,00-</tunggakanTotal>
               <teoPokok>150.000.000,00</teoPokok>
               <teoBunga>0,00</teoBunga>
               <teoBiaya>0,00</teoBiaya>
               <teoDenda>0,00</teoDenda>
               <teoBiayaProvisi>0,00</teoBiayaProvisi>
               <teoTotal>150.000.000,00</teoTotal>
               <saldoMarkup>0,00</saldoMarkup>
               <tunggakanMarkup>0,00</tunggakanMarkup>
               <teoMarkup>0,00</teoMarkup>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```