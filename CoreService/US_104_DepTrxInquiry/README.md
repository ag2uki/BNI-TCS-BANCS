Sample SOAP Request
```
<soapenv:Envelope
	xmlns:q0="http://service.bni.co.id/core"
	xmlns:bo="http://service.bni.co.id/core/bo"  
	xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
	xmlns:xsd="http://www.w3.org/2001/XMLSchema"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body> 
		<q0:transaction>
			<request>
				<systemId>IBANK</systemId>
				<content xsi:type="bo:DepTrxInquiryReq">
					<accountNum>333018</accountNum>
					<fromDate>2010-05-31</fromDate>
					<toDate>2010-05-31</toDate>
					<journalNum>956604</journalNum>
					<transactionType>01</transactionType>
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
            <content xsi:type="bo:CompiledDepTrxInquiryRes">
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>265</branchNum>
                  <terminalNum>9</terminalNum>
                  <tellerNum>5952</tellerNum>
                  <transactionCode>1055</transactionCode>
                  <postDateTime>2010-05-31T10:41:29Z</postDateTime>
                  <journalNum>250371</journalNum>
                  <narative>TRANSFER KE</narative>
                  <amount>-2000.00</amount>
                  <balance>326979576473.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>265</branchNum>
                  <terminalNum>9</terminalNum>
                  <tellerNum>5952</tellerNum>
                  <transactionCode>1055</transactionCode>
                  <postDateTime>2010-05-31T10:41:29Z</postDateTime>
                  <journalNum>250371</journalNum>
                  <narative>TRANSFER KE</narative>
                  <amount>-400000.00</amount>
                  <balance>326979578473.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>265</branchNum>
                  <terminalNum>9</terminalNum>
                  <tellerNum>5952</tellerNum>
                  <transactionCode>1055</transactionCode>
                  <postDateTime>2010-05-31T10:19:39Z</postDateTime>
                  <journalNum>250313</journalNum>
                  <narative>TRANSFER KE</narative>
                  <amount>-2000.00</amount>
                  <balance>326979978473.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>265</branchNum>
                  <terminalNum>9</terminalNum>
                  <tellerNum>5952</tellerNum>
                  <transactionCode>1055</transactionCode>
                  <postDateTime>2010-05-31T10:19:39Z</postDateTime>
                  <journalNum>250313</journalNum>
                  <narative>TRANSFER KE</narative>
                  <amount>-400000.00</amount>
                  <balance>326979980473.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>265</branchNum>
                  <terminalNum>9</terminalNum>
                  <tellerNum>5952</tellerNum>
                  <transactionCode>1055</transactionCode>
                  <postDateTime>2010-05-31T10:14:29Z</postDateTime>
                  <journalNum>250298</journalNum>
                  <narative>TRANSFER KE</narative>
                  <amount>-2000.00</amount>
                  <balance>326980380473.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>265</branchNum>
                  <terminalNum>9</terminalNum>
                  <tellerNum>5952</tellerNum>
                  <transactionCode>1055</transactionCode>
                  <postDateTime>2010-05-31T10:14:29Z</postDateTime>
                  <journalNum>250298</journalNum>
                  <narative>TRANSFER KE</narative>
                  <amount>-400000.00</amount>
                  <balance>326980382473.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>259</branchNum>
                  <terminalNum>3</terminalNum>
                  <tellerNum>5763</tellerNum>
                  <transactionCode>1055</transactionCode>
                  <postDateTime>2010-05-31T10:08:38Z</postDateTime>
                  <journalNum>250216</journalNum>
                  <narative>TRANSFER KE</narative>
                  <amount>-2000.00</amount>
                  <balance>326980782473.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>259</branchNum>
                  <terminalNum>3</terminalNum>
                  <tellerNum>5763</tellerNum>
                  <transactionCode>1055</transactionCode>
                  <postDateTime>2010-05-31T10:08:38Z</postDateTime>
                  <journalNum>250216</journalNum>
                  <narative>TRANSFER KE</narative>
                  <amount>-237400.00</amount>
                  <balance>326980784473.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
               <shortHistorical>
                  <transactionDate>2010-05-31</transactionDate>
                  <branchNum>259</branchNum>
                  <terminalNum>3</terminalNum>
                  <tellerNum>5763</tellerNum>
                  <transactionCode>1055</transactionCode>
                  <postDateTime>2010-05-31T10:07:25Z</postDateTime>
                  <journalNum>250213</journalNum>
                  <narative>TRANSFER KE</narative>
                  <amount>-2000.00</amount>
                  <balance>326981021873.00</balance>
                  <promoCode>XA</promoCode>
               </shortHistorical>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```