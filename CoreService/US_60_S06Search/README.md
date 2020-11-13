Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" 	xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema"	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body> 
		<q0:transaction>
			<request>
				<systemId>IREM</systemId>
				<content xsi:type="bo:S06SearchReq">
					<reffCorrespondent>190301AZ00026181</reffCorrespondent>
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
               <coreJournal>021692</coreJournal>
            </header>
            <content xsi:type="bo:CompiledS06SearchRes">
               <reffCorrespondent>190301AZ00026181</reffCorrespondent>
               <bicCover></bicCover>
               <poType></poType>
               <status>0</status>
               <page>1</page>
               <totalRecords>10</totalRecords>
               <s06Record>
                  <reffCorrespondent>190301AZ00026181</reffCorrespondent>
                  <bicCover>DEUTDEFFXXX</bicCover>
                  <refferenceNum>S06ITR2000287714</refferenceNum>
                  <counterAdvis>ITR000287</counterAdvis>
                  <poType>CRD</poType>
                  <poDate>2015-11-01</poDate>
                  <amountCurrency>IDR</amountCurrency>
                  <amount>10000.000</amount>
                  <senderName>DEKOETJING LTD.</senderName>
                  <beneficiaryName>1/OEKO-INSTITUT. INSTITUT FUER</beneficiaryName>
                  <status>0</status>
               </s06Record>
               <s06Record>
                  <reffCorrespondent>190301AZ00026181</reffCorrespondent>
                  <bicCover>DEUTDEFFXXX</bicCover>
                  <refferenceNum>S06ITR2000287715</refferenceNum>
                  <counterAdvis>ITR000287</counterAdvis>
                  <poType>CRD</poType>
                  <poDate>2015-11-01</poDate>
                  <amountCurrency>IDR</amountCurrency>
                  <amount>10000.000</amount>
                  <senderName>DEKOETJING LTD.</senderName>
                  <beneficiaryName>1/OEKO-INSTITUT. INSTITUT FUER</beneficiaryName>
                  <status>0</status>
               </s06Record>
               <s06Record>
                  <reffCorrespondent>190301AZ00026181</reffCorrespondent>
                  <bicCover>DEUTDEFFXXX</bicCover>
                  <refferenceNum>S06ITR2000287716</refferenceNum>
                  <counterAdvis>ITR000287</counterAdvis>
                  <poType>CRD</poType>
                  <poDate>2015-11-01</poDate>
                  <amountCurrency>IDR</amountCurrency>
                  <amount>10000.000</amount>
                  <senderName>DEKOETJING LTD.</senderName>
                  <beneficiaryName>1/OEKO-INSTITUT. INSTITUT FUER</beneficiaryName>
                  <status>0</status>
               </s06Record>
               <s06Record>
                  <reffCorrespondent>190301AZ00026181</reffCorrespondent>
                  <bicCover>DEUTDEFFXXX</bicCover>
                  <refferenceNum>S06ITR2000287717</refferenceNum>
                  <counterAdvis>ITR000287</counterAdvis>
                  <poType>CRD</poType>
                  <poDate>2015-11-01</poDate>
                  <amountCurrency>IDR</amountCurrency>
                  <amount>10000.000</amount>
                  <senderName>DEKOETJING LTD.</senderName>
                  <beneficiaryName>1/OEKO-INSTITUT. INSTITUT FUER</beneficiaryName>
                  <status>0</status>
               </s06Record>
               <s06Record>
                  <reffCorrespondent>190301AZ00026181</reffCorrespondent>
                  <bicCover>DEUTDEFFXXX</bicCover>
                  <refferenceNum>S06ITR2000387729</refferenceNum>
                  <counterAdvis>ITR000287</counterAdvis>
                  <poType>CRD</poType>
                  <poDate>2015-11-01</poDate>
                  <amountCurrency>IDR</amountCurrency>
                  <amount>10000.000</amount>
                  <senderName>DEKOETJING LTD.</senderName>
                  <beneficiaryName>1/OEKO-INSTITUT. INSTITUT FUER</beneficiaryName>
                  <status>1</status>
               </s06Record>
               <s06Record>
                  <reffCorrespondent>190301AZ00026181</reffCorrespondent>
                  <bicCover>DEUTDEFFXXX</bicCover>
                  <refferenceNum>S06ITR2000387716</refferenceNum>
                  <counterAdvis>ITR000287</counterAdvis>
                  <poType>CRD</poType>
                  <poDate>2015-11-01</poDate>
                  <amountCurrency>IDR</amountCurrency>
                  <amount>10000.000</amount>
                  <senderName>DEKOETJING LTD.</senderName>
                  <beneficiaryName>1/OEKO-INSTITUT. INSTITUT FUER</beneficiaryName>
                  <status>0</status>
               </s06Record>
               <s06Record>
                  <reffCorrespondent>190301AZ00026181</reffCorrespondent>
                  <bicCover>DEUTDEFFXXX</bicCover>
                  <refferenceNum>S06ITR2000387717</refferenceNum>
                  <counterAdvis>ITR000287</counterAdvis>
                  <poType>CRD</poType>
                  <poDate>2015-11-01</poDate>
                  <amountCurrency>IDR</amountCurrency>
                  <amount>10000.000</amount>
                  <senderName>DEKOETJING LTD.</senderName>
                  <beneficiaryName>1/OEKO-INSTITUT. INSTITUT FUER</beneficiaryName>
                  <status>0</status>
               </s06Record>
               <s06Record>
                  <reffCorrespondent>190301AZ00026181</reffCorrespondent>
                  <bicCover>DEUTDEFFXXX</bicCover>
                  <refferenceNum>S06ITR2000387718</refferenceNum>
                  <counterAdvis>ITR000287</counterAdvis>
                  <poType>CRD</poType>
                  <poDate>2015-11-01</poDate>
                  <amountCurrency>IDR</amountCurrency>
                  <amount>10000.000</amount>
                  <senderName>DEKOETJING LTD.</senderName>
                  <beneficiaryName>1/OEKO-INSTITUT. INSTITUT FUER</beneficiaryName>
                  <status>0</status>
               </s06Record>
               <s06Record>
                  <reffCorrespondent>190301AZ00026181</reffCorrespondent>
                  <bicCover>DEUTDEFFXXX</bicCover>
                  <refferenceNum>S06ITR2000387720</refferenceNum>
                  <counterAdvis>ITR000287</counterAdvis>
                  <poType>CRD</poType>
                  <poDate>2015-11-01</poDate>
                  <amountCurrency>IDR</amountCurrency>
                  <amount>10000.000</amount>
                  <senderName>DEKOETJING LTD.</senderName>
                  <beneficiaryName>1/OEKO-INSTITUT. INSTITUT FUER</beneficiaryName>
                  <status>1</status>
               </s06Record>
               <s06Record>
                  <reffCorrespondent>190301AZ00026181</reffCorrespondent>
                  <bicCover>DEUTDEFFXXX</bicCover>
                  <refferenceNum>S06ITR2000287718</refferenceNum>
                  <counterAdvis>ITR000287</counterAdvis>
                  <poType>CRD</poType>
                  <poDate>2015-11-01</poDate>
                  <amountCurrency>IDR</amountCurrency>
                  <amount>10000.000</amount>
                  <senderName>PT. NURINDO MANDIRI INTERNASIONAL</senderName>
                  <beneficiaryName>1/OEKO-INSTITUT. INSTITUT FUER</beneficiaryName>
                  <status>1</status>
               </s06Record>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```