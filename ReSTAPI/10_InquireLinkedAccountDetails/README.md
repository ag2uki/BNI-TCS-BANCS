# 060583

This transaction code is known as 4 services:
- OpenAccountList (060583 with option set to 01)
- OpenLoanAccountList (060583 with option set to 02)
- OpenDepositAccountList (060583 with option set to 03)
- OpenDepositAccListByBalance (060583 with option set to 06)

## OpenAccountList
OpenAccountList is a service to get all kind of account that owned by a CIF.
SOAP Request:
```xml
<soapenv:Envelope
	xmlns:q0="http://service.bni.co.id/core"
	xmlns:bo="http://service.bni.co.id/core/bo"  
	xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
	xmlns:xsd="http://www.w3.org/2001/XMLSchema"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body> 
<q0:transaction>
  <request>
    <systemId>NEWIBANK-CORE</systemId>
  <content xsi:type="bo:OpenAccountListReq">
    <cifNum>9100208705</cifNum>    
  </content>
  </request>
</q0:transaction>
</soapenv:Body>
</soapenv:Envelope>
```
SOAP Response:
```xml
response :
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/"
xmlns:xsd="http://www.w3.org/2001/XMLSchema"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xmlns:dpss0="bons">
  <soapenv:Header />
  <soapenv:Body>
    <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo"
    xmlns:core="http://service.bni.co.id/core">
      <response>
        <header>
          <coreJournal>669257</coreJournal>
        </header>
        <content xsi:type="bo:CompiledOpenAccountListRes">
          <cifNum>00000009100208705</cifNum>
          <openAccountInfo>
            <accountNum>00000000115332732</accountNum>
            <status>BARU</status>
            <accountTypeCode>LON</accountTypeCode>
            <productName>KMK BNI EFEKTIF IDR</productName>
            <currency>IDR</currency>
            <ownership>OWN</ownership>
            <balance>0,00</balance>
            <limit>0,00</limit>
            <accType>1000</accType>
            <subCat>0701</subCat>
            <effectiveBalance>0,00</effectiveBalance>
            <disburseAmount>0,00</disburseAmount>
            <branchCode>0259</branchCode>
          </openAccountInfo>
          <openAccountInfo>
            <accountNum>00000000115324517</accountNum>
            <status>BUKA</status>
            <accountTypeCode>DEP</accountTypeCode>
            <productName>KARTU TANDA MHS (KTM)</productName>
            <currency>IDR</currency>
            <ownership>OWN</ownership>
            <balance>0,00</balance>
            <limit>0,00</limit>
            <accType>2100</accType>
            <subCat>0001</subCat>
            <effectiveBalance>7.797.500,00</effectiveBalance>
            <disburseAmount></disburseAmount>
            <branchCode>0259</branchCode>
          </openAccountInfo>
          <openAccountInfo>
            <accountNum>00000000115331614</accountNum>
            <status>BUKA</status>
            <accountTypeCode>DEP</accountTypeCode>
            <productName>TABUNGAN PLUS (TAPLUS)</productName>
            <currency>IDR</currency>
            <ownership>OWN</ownership>
            <balance>0,00</balance>
            <limit>0,00</limit>
            <accType>2000</accType>
            <subCat>0001</subCat>
            <effectiveBalance>40.581.000,00</effectiveBalance>
            <disburseAmount></disburseAmount>
            <branchCode>0259</branchCode>
          </openAccountInfo>
          <openAccountInfo>
            <accountNum>00000000115310504</accountNum>
            <status>DORM</status>
            <accountTypeCode>DEP</accountTypeCode>
            <productName>TABUNGAN PLUS (TAPLUS)</productName>
            <currency>IDR</currency>
            <ownership>OWN</ownership>
            <balance>0,00</balance>
            <limit>0,00</limit>
            <accType>2000</accType>
            <subCat>0001</subCat>
            <effectiveBalance>4.482.000,00</effectiveBalance>
            <disburseAmount></disburseAmount>
            <branchCode>0259</branchCode>
          </openAccountInfo>
        </content>
      </response>
    </core:transactionResponse>
  </soapenv:Body>
</soapenv:Envelope>
``` 

## OpenLoanAccountList
OpenLoanAccountList is a service to get all of loan account that owned by a CIF.
SOAP Request: 
```xml
<soapenv:Envelope
	xmlns:q0="http://service.bni.co.id/core"
	xmlns:bo="http://service.bni.co.id/core/bo"  
	xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
	xmlns:xsd="http://www.w3.org/2001/XMLSchema"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body> 
		<q0:transaction>
  			<request>
   				 <systemId>NEWIBANK-CORE</systemId>
 				 <content xsi:type="bo:OpenLoanAccountListReq">
    					<cifNum>9100132631</cifNum>	
 				 </content>
 			 </request>
		</q0:transaction>
	</soapenv:Body>
</soapenv:Envelope>
```

SOAP Response:
```
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/"
xmlns:xsd="http://www.w3.org/2001/XMLSchema"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
xmlns:dpss0="bons">
  <soapenv:Header />
  <soapenv:Body>
    <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo"
    xmlns:core="http://service.bni.co.id/core">
      <response>
        <header>
          <coreJournal>687882</coreJournal>
        </header>
        <content xsi:type="bo:CompiledOpenLoanAccountListRes">
          <cifNum>00000009100132631</cifNum>
          <customerName>Sdr ALI ALI MAHMUD</customerName>
          <keyPerson></keyPerson>
          <noDIN></noDIN>
          <noHP></noHP>
          <openLoanAccountInfo>
            <accountNum>00000000115230093</accountNum>
            <accountStatus>BARU</accountStatus>
            <accountTypeCode></accountTypeCode>
            <productName>BNI UMG IDR</productName>
            <currency>IDR</currency>
            <ownership>OWN</ownership>
            <approveAmount>0,00</approveAmount>
            <outsatndingAmount>-8.805.825,00</outsatndingAmount>
            <collectability>03</collectability>
            <maturityDate>2011-05-30</maturityDate>
            <arrear>-8.805.825,00</arrear>
            <arrDate />
            <accType>3940</accType>
            <subCat>0401</subCat>
            <effectiveBalance>-8.805.825,00</effectiveBalance>
            <disburseAmount>0,00</disburseAmount>
            <branchCode>0718</branchCode>
            <flagIbank></flagIbank>
          </openLoanAccountInfo>
          <openLoanAccountInfo>
            <accountNum>00000000115230139</accountNum>
            <accountStatus>SEBA</accountStatus>
            <accountTypeCode></accountTypeCode>
            <productName>BNI UMG IDR</productName>
            <currency>IDR</currency>
            <ownership>OWN</ownership>
            <approveAmount>100.000.000,00</approveAmount>
            <outsatndingAmount>91.194.175,00</outsatndingAmount>
            <collectability>03</collectability>
            <maturityDate>2011-05-30</maturityDate>
            <arrear>-6.987.643,00</arrear>
            <arrDate />
            <accType>3940</accType>
            <subCat>0401</subCat>
            <effectiveBalance>91.194.175,00</effectiveBalance>
            <disburseAmount>0,00</disburseAmount>
            <branchCode>0718</branchCode>
            <flagIbank></flagIbank>
          </openLoanAccountInfo>
          <openLoanAccountInfo>
            <accountNum>00000000115230151</accountNum>
            <accountStatus>SEBA</accountStatus>
            <accountTypeCode></accountTypeCode>
            <productName>BNI UMG IDR</productName>
            <currency>IDR</currency>
            <ownership>OWN</ownership>
            <approveAmount>500.000.000,00</approveAmount>
            <outsatndingAmount>490.194.175,00</outsatndingAmount>
            <collectability>03</collectability>
            <maturityDate>2013-05-31</maturityDate>
            <arrear>-8.805.825,00</arrear>
            <arrDate />
            <accType>3940</accType>
            <subCat>0401</subCat>
            <effectiveBalance>490.194.175,00</effectiveBalance>
            <disburseAmount>0,00</disburseAmount>
            <branchCode>0718</branchCode>
            <flagIbank></flagIbank>
          </openLoanAccountInfo>
          <openLoanAccountInfo>
            <accountNum>00000000115230195</accountNum>
            <accountStatus>BARU</accountStatus>
            <accountTypeCode></accountTypeCode>
            <productName>BNI UMG IDR</productName>
            <currency>IDR</currency>
            <ownership>OWN</ownership>
            <approveAmount>0,00</approveAmount>
            <outsatndingAmount>-8.805.825,00</outsatndingAmount>
            <collectability>03</collectability>
            <maturityDate>2011-05-30</maturityDate>
            <arrear>-8.805.825,00</arrear>
            <arrDate />
            <accType>3940</accType>
            <subCat>0401</subCat>
            <effectiveBalance>-8.805.825,00</effectiveBalance>
            <disburseAmount>0,00</disburseAmount>
            <branchCode>0259</branchCode>
            <flagIbank></flagIbank>
          </openLoanAccountInfo>
          <curr>IDR</curr>
          <totAprvAmt>600.000.000,00</totAprvAmt>
          <totOutstd>563.776.700,00</totOutstd>
          <totArrear>-33.405.118,00</totArrear>
        </content>
      </response>
    </core:transactionResponse>
  </soapenv:Body>
</soapenv:Envelope>
```
## OpenDepositAccountList 
OpenDepositAccountList is a service to get all of deposit account that owned by a CIF.
SOAP Request:
```xml
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core"
xmlns:bo="http://service.bni.co.id/core/bo"
xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
xmlns:xsd="http://www.w3.org/2001/XMLSchema"
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
  <soapenv:Body>
    <q0:transaction>
      <request>
        <systemId>NEWIBANK-CORE</systemId>
        <content xsi:type="bo:OpenDepositAccountListReq">
          <cifNum>9100132631</cifNum>
        </content>
      </request>
    </q0:transaction>
  </soapenv:Body>
</soapenv:Envelope>
```
## OpenDepositAccListByBalance 
OpenDepositAccListByBalance is similar to OpenDepositAccountList, but sorted by account's balance.
SOAP Request:
```xml
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SMS</systemId>
            <content xsi:type="bo:OpenDepositAccListByBalanceReq">
               <cifNum>9100131831</cifNum>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs format message:
```
[ 0101                    **
         003099600100001060583000000     0  I  0 000000  0000000915487980601]
```
