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

