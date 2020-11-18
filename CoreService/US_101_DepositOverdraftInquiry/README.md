Sample SOAP Request
```
<soapenv:Envelope xmlns:bo="http://service.bni.co.id/core/bo" 
xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
xmlns:core="http://service.bni.co.id/core" 
xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
	<soapenv:Header/>
	<soapenv:Body>
		<core:transaction>
			<request>
				<systemId>BNIDIRECT</systemId>
				<content xsi:type="bo:DepositOverdraftInquiryReq">
					<accountNumber>224682965</accountNumber>
					<optionType>4</optionType>
					<recordDate>0000-00-00</recordDate>
				</content>
			</request>
		</core:transaction>
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
            <content xsi:type="bo:DepositOverdraftInquiryRes">
               <accountNumber>224682965</accountNumber>
               <limitType>1</limitType>
               <overDraftLimit1>100000000000</overDraftLimit1>
               <rate1>0</rate1>
               <rateType1>S</rateType1>
               <effectiveDate1>2011-07-11</effectiveDate1>
               <dueDate1>2050-07-11</dueDate1>
               <type1/>
               <value1/>
               <overDraftLimit2/>
               <rate2>0</rate2>
               <rateType2/>
               <effectiveDate2>0000-00-00</effectiveDate2>
               <dueDate2>0000-00-00</dueDate2>
               <type2/>
               <value2/>
               <overDraftLimit3/>
               <rate3>0</rate3>
               <rateType3/>
               <effectiveDate3>0000-00-00</effectiveDate3>
               <dueDate3>0000-00-00</dueDate3>
               <type3/>
               <value3/>
               <overDraftLimit4/>
               <rate4>0</rate4>
               <rateType4/>
               <effectiveDate4>0000-00-00</effectiveDate4>
               <dueDate4>0000-00-00</dueDate4>
               <type4/>
               <value4/>
               <kelebihan/>
               <dummy1>0</dummy1>
               <dummy2/>
               <dummy3>0</dummy3>
               <dummy4/>
               <marginPengurang>9999999999</marginPengurang>
               <kodeBungaDebit>R</kodeBungaDebit>
               <debitPemindahan/>
               <kodeKomitmen>R</kodeKomitmen>
               <pemindahanKomitmen/>
               <jenisOverdraftExpiryRate>I</jenisOverdraftExpiryRate>
               <overdraftExpiredRate>0</overdraftExpiredRate>
               <ratingPinjaman/>
               <fasilitas/>
               <jenisPembayaran/>
               <nominalAngsuranTetap>0</nominalAngsuranTetap>
               <hapusDetail/>
               <kodePromo/>
               <status1>6</status1>
               <status2/>
               <status3/>
               <status4/>
               <tujuan>101</tujuan>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0108                    **            003098900100001007050000000     0  I  0 000000  00000002019201908000000000]

[ 0889    0805            0000    000000003098900100001007000000000000040320600 000000  0300000002019201908000000091007920531234567516875430        0001 SHINJI IKARI                                               JALAN EVA                               0201                                    NJohar Baru                              ID Johar Baru         /Jakarta Pusat       10560   10100001   R                        04M 010                 000000      0002                    00000000000000000                 0                                                            31052010    03ZZZZBZZ            0259IDR00002100013100            010 0000000+0   N 00000000000000000                   000000000000              0006                    0001                              00000000425000000000000000000000000000                                                                              ]
```