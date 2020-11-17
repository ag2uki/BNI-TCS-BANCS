Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" 
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" 
xmlns:bo="http://service.bni.co.id/core/bo" 
xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SPRINT</systemId>
            <content xsi:type="bo:AccountShortInquiryReq">
               <accountNum>114567288</accountNum>
               <options>8</options>
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
            <header/>
            <content xsi:type="bo:AccountShortInquiryRes">
               <d_accountNum>00000000114567288</d_accountNum>
               <d_currency>IDR</d_currency>
               <d_status>BUKA</d_status>
               <d_product>BNI TAPENAS</d_product>
               <d_homeBranch>0259</d_homeBranch>
               <d_cifNum>00000009100792053</d_cifNum>
               <d_name>SHINJI IKARI</d_name>
               <d_nameRek/>
               <d_currentBalance>0,00</d_currentBalance>
               <d_availableBalance>0,00</d_availableBalance>
               <d_openDate>2010-05-31</d_openDate>
               <d_address1>JALAN EVA</d_address1>
               <d_address2>0201</d_address2>
               <d_address3>Johar Baru</d_address3>
               <d_address4>Johar Baru         /Jakarta Pusat</d_address4>
               <d_postCode>10560</d_postCode>
               <d_homePhone>021.32574984</d_homePhone>
               <d_mobilePhone>082 26468465</d_mobilePhone>
               <d_address1AA>JALAN EVA</d_address1AA>
               <d_address2AA>0201</d_address2AA>
               <d_address3AA>Johar Baru</d_address3AA>
               <d_address4AA>Johar Baru         /Jakarta Pusat</d_address4AA>
               <d_postCodeAA>10560</d_postCodeAA>
               <d_homePhoneAA>021.32574984</d_homePhoneAA>
               <d_mobilePhoneAA>082.26468465</d_mobilePhoneAA>
               <accountProductType>TUA</accountProductType>
               <d_accType>2800</d_accType>
               <d_subCat>0001</d_subCat>
               <d_availableInterest>0,00</d_availableInterest>
               <d_lienBalance>0,00</d_lienBalance>
               <d_unclearBalance>0,00</d_unclearBalance>
               <d_interestRate>0,0000</d_interestRate>
               <d_term>0006</d_term>
               <d_termFlag>Y</d_termFlag>
               <d_investmentType>R</d_investmentType>
               <d_affiliateAccount>00000002019201908</d_affiliateAccount>
               <d_topupAmount>27.000.000,00</d_topupAmount>
               <d_additionalInsurance>30</d_additionalInsurance>
               <d_maturityDate>2010-12-05</d_maturityDate>
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

Bancs Format
```
[ 0100                    **            003098600100001069400000000     0  I  0 000000  000000001145672888]

[ 1067    0983            0000    000000003098600100001000400000000000040320600 000000  0300000000114567288IDRBUKA              BNI TAPENAS                   025900000009100792053 SHINJI IKARI                                                                                                                         0,00               0,00 31052010JALAN EVA                               0201                                    Johar Baru                              Johar Baru         /Jakarta Pusat       10560   021.32574984082.26468465JALAN EVA                               0201                                    Johar Baru                              Johar Baru         /Jakarta Pusat       10560   021.32574984082.26468465I28000001              0,00               0,00               0,00  0,00000006YR 00000002019201908     27.000.000,00 3005122010                                                            99999999                                                                                                                            05082 26468465            ]
```