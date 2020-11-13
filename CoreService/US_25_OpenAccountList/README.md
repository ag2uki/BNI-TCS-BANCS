Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body>
		<q0:transaction>
			<request>
				<systemId>NEWIBANK-CORE</systemId>
				<content xsi:type="bo:OpenAccountListReq">
					<cifNum>9161995756</cifNum>
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
               <coreJournal>396643</coreJournal>
            </header>
            <content xsi:type="bo:CompiledOpenAccountListRes">
               <cifNum>00000009161995756</cifNum>
               <openAccountInfo>
                  <accountNum>00000000114487915</accountNum>
                  <status>BUKA</status>
                  <accountTypeCode>DEP</accountTypeCode>
                  <productName>GIRO TDK HIT BBB NON RSD</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>0,00</balance>
                  <limit>0,00</limit>
                  <accType>1019</accType>
                  <subCat>0001</subCat>
                  <effectiveBalance>0,00</effectiveBalance>
                  <disburseAmount/>
                  <branchCode>0063</branchCode>
                  <flagIbank>0</flagIbank>
               </openAccountInfo>
               <openAccountInfo>
                  <accountNum>00000000184612173</accountNum>
                  <status>BUKA</status>
                  <accountTypeCode>DEP</accountTypeCode>
                  <productName>GIRO TDK HIT BBB PEMERINTAH</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>9.413.745.433,00</balance>
                  <limit>0,00</limit>
                  <accType>1012</accType>
                  <subCat>0001</subCat>
                  <effectiveBalance>9.413.745.433,00</effectiveBalance>
                  <disburseAmount/>
                  <branchCode>0130</branchCode>
                  <flagIbank></flagIbank>
               </openAccountInfo>
               <openAccountInfo>
                  <accountNum>00000000188659184</accountNum>
                  <status>BUKA</status>
                  <accountTypeCode>DEP</accountTypeCode>
                  <productName>GIRO TDK HIT BBB PEMERINTAH</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>16.337.324.026,00</balance>
                  <limit>0,00</limit>
                  <accType>1012</accType>
                  <subCat>0001</subCat>
                  <effectiveBalance>16.337.324.026,00</effectiveBalance>
                  <disburseAmount/>
                  <branchCode>0130</branchCode>
                  <flagIbank></flagIbank>
               </openAccountInfo>
               <openAccountInfo>
                  <accountNum>00000000296474176</accountNum>
                  <status>BUKA</status>
                  <accountTypeCode>DEP</accountTypeCode>
                  <productName>GIRO TDK HIT BBB PEMERINTAH</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>713.995.255.485,00</balance>
                  <limit>0,00</limit>
                  <accType>1012</accType>
                  <subCat>0001</subCat>
                  <effectiveBalance>713.995.255.485,00</effectiveBalance>
                  <disburseAmount/>
                  <branchCode>0063</branchCode>
                  <flagIbank>0</flagIbank>
               </openAccountInfo>
               <openAccountInfo>
                  <accountNum>00000000296474245</accountNum>
                  <status>BUKA</status>
                  <accountTypeCode>DEP</accountTypeCode>
                  <productName>GIRO TDK HIT BBB PEMERINTAH</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>1000000000002</balance>
                  <limit>0,00</limit>
                  <accType>1012</accType>
                  <subCat>0001</subCat>
                  <effectiveBalance>1000000000002</effectiveBalance>
                  <disburseAmount/>
                  <branchCode>0063</branchCode>
                  <flagIbank>0</flagIbank>
               </openAccountInfo>
               <openAccountInfo>
                  <accountNum>00000000296474369</accountNum>
                  <status>BUKA</status>
                  <accountTypeCode>DEP</accountTypeCode>
                  <productName>GIRO TDK HIT BBB PEMERINTAH</productName>
                  <currency>IDR</currency>
                  <ownership>OWN</ownership>
                  <balance>1000385561930</balance>
                  <limit>0,00</limit>
                  <accType>1012</accType>
                  <subCat>0001</subCat>
                  <effectiveBalance>1000385561930</effectiveBalance>
                  <disburseAmount/>
                  <branchCode>0063</branchCode>
                  <flagIbank>0</flagIbank>
               </openAccountInfo>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```