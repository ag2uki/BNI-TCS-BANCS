## 1. Taplus ##
_SOAP Format_
```
Request :
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWMOBILE</systemId>
            <content xsi:type="bo:AccountShortInquiryReq">
               <accountNum>1000016569</accountNum>
               <options>8</options>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>

Response :
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header/>
            <content xsi:type="bo:AccountShortInquiryRes">
               <d_accountNum>00000001000016569</d_accountNum>
               <d_currency>IDR</d_currency>
               <d_status>BUKA</d_status>
               <d_product>BNI TAPLUS</d_product>
               <d_homeBranch>0259</d_homeBranch>
               <d_cifNum>00000009100763087</d_cifNum>
               <d_name>Bpk RASYID</d_name>
               <d_nameRek/>
               <d_currentBalance>0,00</d_currentBalance>
               <d_availableBalance>0,00</d_availableBalance>
               <d_openDate>2010-05-31</d_openDate>
               <d_address1>SURABAYA</d_address1>
               <d_address2>11</d_address2>
               <d_address3>Gebang Putih 1</d_address3>
               <d_address4>Sukolilo           /Surabaya</d_address4>
               <d_postCode>60117</d_postCode>
               <d_homePhone>031 12324355</d_homePhone>
               <d_mobilePhone>087812345678111</d_mobilePhone>
               <d_address1AA>SURABAYA</d_address1AA>
               <d_address2AA>11</d_address2AA>
               <d_address3AA>Gebang Putih 1</d_address3AA>
               <d_address4AA>Sukolilo           /Surabaya</d_address4AA>
               <d_postCodeAA>60117</d_postCodeAA>
               <d_homePhoneAA>031 12324355</d_homePhoneAA>
               <d_mobilePhoneAA>087812345678</d_mobilePhoneAA>
               <accountProductType>DEP</accountProductType>
               <d_accType>2000</d_accType>
               <d_subCat>0001</d_subCat>
               <d_availableInterest>0,00</d_availableInterest>
               <d_lienBalance>0,00</d_lienBalance>
               <d_unclearBalance>0,00</d_unclearBalance>
               <d_interestRate>0,0000</d_interestRate>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```
_Bancs Format_
```
Request :
[ 0100                    **            003099100100001069400000000     0  I  0 000000  000000010000165698]

Response :
[ 1067    0983            0000    000000003099100100001000400000000000040320600 000000  0300000001000016569IDRBUKA              BNI TAPLUS                    025900000009100763087Bpk RASYID                                                                                                                            0,00               0,00 31052010SURABAYA                                11                                      Gebang Putih 1                          Sukolilo           /Surabaya            60117   031 12324355087812345678SURABAYA                                11                                      Gebang Putih 1                          Sukolilo           /Surabaya            60117   031 12324355087812345678D20000001              0,00               0,00               0,00  0,0000                                                                                                                                                                                                                                                     05087812345678111         ]
```

## 2. Tapenas ##
_SOAP Format_
```
Request :
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWMOBILE</systemId>
            <content xsi:type="bo:AccountShortInquiryReq">
               <accountNum>1000016570</accountNum>
               <options>8</options>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>

Response :
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header/>
            <content xsi:type="bo:AccountShortInquiryRes">
               <d_accountNum>00000001000016570</d_accountNum>
               <d_currency>IDR</d_currency>
               <d_status>BUKA</d_status>
               <d_product>BNI TAPENAS</d_product>
               <d_homeBranch>0259</d_homeBranch>
               <d_cifNum>00000009100763087</d_cifNum>
               <d_name>Bpk RASYID</d_name>
               <d_nameRek/>
               <d_currentBalance>0,00</d_currentBalance>
               <d_availableBalance>0,00</d_availableBalance>
               <d_openDate>2010-05-31</d_openDate>
               <d_address1>SURABAYA</d_address1>
               <d_address2>11</d_address2>
               <d_address3>Gebang Putih 1</d_address3>
               <d_address4>Sukolilo           /Surabaya</d_address4>
               <d_postCode>60117</d_postCode>
               <d_homePhone>031 12324355</d_homePhone>
               <d_mobilePhone>087812345678111</d_mobilePhone>
               <d_address1AA>SURABAYA</d_address1AA>
               <d_address2AA>11</d_address2AA>
               <d_address3AA>Gebang Putih 1</d_address3AA>
               <d_address4AA>Sukolilo           /Surabaya</d_address4AA>
               <d_postCodeAA>60117</d_postCodeAA>
               <d_homePhoneAA>031 12324355</d_homePhoneAA>
               <d_mobilePhoneAA>087812345678</d_mobilePhoneAA>
               <accountProductType>TUA</accountProductType>
               <d_accType>2800</d_accType>
               <d_subCat>0001</d_subCat>
               <d_availableInterest>0,00</d_availableInterest>
               <d_lienBalance>0,00</d_lienBalance>
               <d_unclearBalance>0,00</d_unclearBalance>
               <d_interestRate>0,0000</d_interestRate>
               <d_term>0012</d_term>
               <d_termFlag>Y</d_termFlag>
               <d_investmentType>R</d_investmentType>
               <d_affiliateAccount>00000001000016569</d_affiliateAccount>
               <d_topupAmount>500.000,00</d_topupAmount>
               <d_additionalInsurance>00</d_additionalInsurance>
               <d_maturityDate>2011-06-05</d_maturityDate>
               <d_nomineeName/>
               <d_birthdate/>
               <d_nomineeAddress/>
               <d_familyRelationship/>
               <d_monthlyDebitingDate>05</d_monthlyDebitingDate>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```
_Bancs Format_
```
Request :
[ 0100                    **            003099100100001069400000000     0  I  0 000000  000000010000165708]

Response :
[ 1067    0983            0000    000000003099100100001000400000000000040320600 000000  0300000001000016570IDRBUKA              BNI TAPENAS                   025900000009100763087Bpk RASYID                                                                                                                            0,00               0,00 31052010SURABAYA                                11                                      Gebang Putih 1                          Sukolilo           /Surabaya            60117   031 12324355087812345678SURABAYA                                11                                      Gebang Putih 1                          Sukolilo           /Surabaya            60117   031 12324355087812345678I28000001              0,00               0,00               0,00  0,00000012YR 00000001000016569        500.000,00 0005062011                                                            99999999                                                                                                                            05087812345678111         ]
```

## 3. Deposito ##
_SOAP Format_
```
Request :
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWMOBILE</systemId>
            <content xsi:type="bo:AccountShortInquiryReq">
               <accountNum>114472294</accountNum>
               <options>8</options>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>

Response :
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header/>
            <content xsi:type="bo:AccountShortInquiryRes">
               <d_accountNum>00000000114472294</d_accountNum>
               <d_currency>IDR</d_currency>
               <d_status>BUKA</d_status>
               <d_product>DEPOSITO KAPITALISASI 3 IDR</d_product>
               <d_homeBranch>0100</d_homeBranch>
               <d_cifNum>00000009154883494</d_cifNum>
               <d_name>SATRIA SAMBRAMA</d_name>
               <d_nameRek/>
               <d_currentBalance>40.000.000,00</d_currentBalance>
               <d_availableBalance>40.000.000,00</d_availableBalance>
               <d_openDate>2010-05-31</d_openDate>
               <d_address1>JL. SETIABUDI</d_address1>
               <d_address2>35</d_address2>
               <d_address3>Setiabudi</d_address3>
               <d_address4>Setia Budi         /Jakarta Selatan</d_address4>
               <d_postCode>12910</d_postCode>
               <d_homePhone>021 11218292</d_homePhone>
               <d_mobilePhone>08561234567890</d_mobilePhone>
               <d_address1AA>JL. SETIABUDI</d_address1AA>
               <d_address2AA>35</d_address2AA>
               <d_address3AA>Setiabudi</d_address3AA>
               <d_address4AA>Setia Budi         /Jakarta Selatan</d_address4AA>
               <d_postCodeAA>12910</d_postCodeAA>
               <d_homePhoneAA>021 11218292</d_homePhoneAA>
               <d_mobilePhoneAA>085612345678</d_mobilePhoneAA>
               <accountProductType>TDA</accountProductType>
               <d_accType>3201</d_accType>
               <d_subCat>0002</d_subCat>
               <d_availableInterest>0,00</d_availableInterest>
               <d_lienBalance>0,00</d_lienBalance>
               <d_unclearBalance>0,00</d_unclearBalance>
               <d_interestRate>5,7500</d_interestRate>
               <d_term>0003</d_term>
               <d_termFlag>1</d_termFlag>
               <d_investmentType>R</d_investmentType>
               <d_affiliateAccount>00000000000000000</d_affiliateAccount>
               <d_maturityDate>2010-08-31</d_maturityDate>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```
_Bancs Format_
```
Request :
[ 0100                    **            003099100100001069400000000     0  I  0 000000  000000001144722948]

Response :
[ 1067    0983            0000    000000003099100100001000400000000000040320600 000000  0300000000114472294IDRBUKA              DEPOSITO KAPITALISASI 3 IDR   010000000009154883494 SATRIA SAMBRAMA                                                                                                             40.000.000,00      40.000.000,00 31052010JL. SETIABUDI                           35                                      Setiabudi                               Setia Budi         /Jakarta Selatan     12910   021 11218292085612345678JL. SETIABUDI                           35                                      Setiabudi                               Setia Budi         /Jakarta Selatan     12910   021 11218292085612345678T32010002              0,00               0,00               0,00  5,750000031R 0000000000000000031082010                                                                                                                                                                                                                     0508561234567890          ]
```

## 4. Tabungan Haji ##
_SOAP Format_
```
Request :
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWMOBILE</systemId>
            <content xsi:type="bo:AccountShortInquiryReq">
               <accountNum>1000016581</accountNum>
               <options>8</options>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>

Response :
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header/>
            <content xsi:type="bo:AccountShortInquiryRes">
               <d_accountNum>00000001000016581</d_accountNum>
               <d_currency>IDR</d_currency>
               <d_status>BUKA</d_status>
               <d_product>BNI HAJI</d_product>
               <d_homeBranch>0259</d_homeBranch>
               <d_cifNum>00000009100763087</d_cifNum>
               <d_name>Bpk RASYID</d_name>
               <d_nameRek/>
               <d_currentBalance>0,00</d_currentBalance>
               <d_availableBalance>0,00</d_availableBalance>
               <d_openDate>2010-05-31</d_openDate>
               <d_address1>SURABAYA</d_address1>
               <d_address2>11</d_address2>
               <d_address3>Gebang Putih 1</d_address3>
               <d_address4>Sukolilo           /Surabaya</d_address4>
               <d_postCode>60117</d_postCode>
               <d_homePhone>031 12324355</d_homePhone>
               <d_mobilePhone>087812345678111</d_mobilePhone>
               <d_address1AA>SURABAYA</d_address1AA>
               <d_address2AA>11</d_address2AA>
               <d_address3AA>Gebang Putih 1</d_address3AA>
               <d_address4AA>Sukolilo           /Surabaya</d_address4AA>
               <d_postCodeAA>60117</d_postCodeAA>
               <d_homePhoneAA>031 12324355</d_homePhoneAA>
               <d_mobilePhoneAA>087812345678</d_mobilePhoneAA>
               <accountProductType>DEP</accountProductType>
               <d_accType>2400</d_accType>
               <d_subCat>0001</d_subCat>
               <d_availableInterest>0,00</d_availableInterest>
               <d_lienBalance>0,00</d_lienBalance>
               <d_unclearBalance>0,00</d_unclearBalance>
               <d_interestRate>0,0000</d_interestRate>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```
_Bancs Format_
```
Request :
[ 0100                    **            003099100100001069400000000     0  I  0 000000  000000010000165818]

Response :
[ 1067    0983            0000    000000003099100100001000400000000000040320600 000000  0300000001000016581IDRBUKA              BNI HAJI                      025900000009100763087Bpk RASYID                                                                                                                            0,00               0,00 31052010SURABAYA                                11                                      Gebang Putih 1                          Sukolilo           /Surabaya            60117   031 12324355087812345678SURABAYA                                11                                      Gebang Putih 1                          Sukolilo           /Surabaya            60117   031 12324355087812345678D24000001              0,00               0,00               0,00  0,0000                                                                                                                                                                                                                                                     05087812345678111         ]
```

## 5. Pinjaman Fleksi ##
_SOAP Format_
```
Request :
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWMOBILE</systemId>
            <content xsi:type="bo:AccountShortInquiryReq">
               <accountNum>1000015577</accountNum>
               <options>8</options>
            </content>
         </request>
      </q0:transaction>
   </soapenv:Body>
</soapenv:Envelope>

Response :
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header/>
            <content xsi:type="bo:AccountShortInquiryRes">
               <l_accountNum>00000001000015577</l_accountNum>
               <l_currency>IDR</l_currency>
               <l_status>SELURUHNYA</l_status>
               <l_product>BNI FLEKSI IND FLAT IDR</l_product>
               <l_homeBranch>0718</l_homeBranch>
               <l_cifNum>00000009100988669</l_cifNum>
               <l_name>Bpk JEMZ SUZURA GINTING</l_name>
               <l_nameRek/>
               <l_currentBalance>416.666,00</l_currentBalance>
               <l_availableBalance>416.666,00</l_availableBalance>
               <l_openDate>2010-05-31</l_openDate>
               <l_address1>KOMP. CITRA DAMAI 2 BLOK D NO.3</l_address1>
               <l_address2>041008</l_address2>
               <l_address3>Bukit Sangkal</l_address3>
               <l_address4>Kalidoni           /Palembang</l_address4>
               <l_postCode>30114</l_postCode>
               <l_homePhone>0711820159</l_homePhone>
               <l_mobilePhone>081369693910</l_mobilePhone>
               <l_address1AA>KOMP. CITRA DAMAI 2 BLOK D NO.3</l_address1AA>
               <l_address2AA>041008</l_address2AA>
               <l_address3AA>Bukit Sangkal</l_address3AA>
               <l_address4AA>Kalidoni           /Palembang</l_address4AA>
               <l_postCodeAA>30114</l_postCodeAA>
               <l_homePhoneAA>0711820159</l_homePhoneAA>
               <l_mobilePhoneAA>081369693910</l_mobilePhoneAA>
               <accountProductType>LON</accountProductType>
               <l_accType>3610</l_accType>
               <l_subCat>0101</l_subCat>
               <l_interestRate>15,0000</l_interestRate>
               <l_term>006</l_term>
               <l_affiliateAccount>00000000230519965</l_affiliateAccount>
               <l_maturityDate>2010-11-29</l_maturityDate>
               <l_approvedDate>2010-05-31</l_approvedDate>
               <l_approved>650.000,00</l_approved>
               <l_advanced>500.000,00</l_advanced>
               <l_installmentAmount>138.125,00</l_installmentAmount>
               <l_overdueAmount>0,00</l_overdueAmount>
               <l_balance>0000000000000000000</l_balance>
               <l_principalOverdue>0,00</l_principalOverdue>
               <l_remRepayment>005</l_remRepayment>
               <l_nextInstallmentDueDate>31</l_nextInstallmentDueDate>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```
_Bancs Format_
```
Request :
[ 0100                    **            003099100100001069400000000     0  I  0 000000  000000010000155778]

Response :
[ 0914    0830            0000    000000003099100100001010400000000000040320600 000000  0300000001000015577IDRSELURUHNYA        BNI FLEKSI IND FLAT IDR       071800000009100988669Bpk JEMZ SUZURA GINTING                                                                                                         416.666,00         416.666,00 31052010KOMP. CITRA DAMAI 2 BLOK D NO.3         041008                                  Bukit Sangkal                           Kalidoni           /Palembang           30114   0711820159  081369693910KOMP. CITRA DAMAI 2 BLOK D NO.3         041008                                  Bukit Sangkal                           Kalidoni           /Palembang           30114   0711820159  081369693910B3610010115,0000006000000002305199652911201031052010        650.000,00         500.000,00         138.125,00               0,00 0000000000000000000              0,00 00531081369693910        ]
```
