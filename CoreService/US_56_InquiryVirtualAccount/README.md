Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>H2HSERVICE</systemId>
            <content xsi:type="bo:InquiryVirtualAccountReq">
               <virtualAccountType>8</virtualAccountType>
               <companyCode>697</companyCode>
               <virtualAccountNum>8697190430092710</virtualAccountNum>
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
               <coreJournal>396600</coreJournal>
            </header>
            <content xsi:type="bo:InquiryVirtualAccountRes">
               <virtualAccountType>8</virtualAccountType>
               <companyCode>697</companyCode>
               <virtualAccountNum>8697190430092710</virtualAccountNum>
               <accountNum>114484120</accountNum>
               <companyName>KUCING BELANG TIGA</companyName>
               <accountStatus>1</accountStatus>
               <virtualAccountName>Test SIT</virtualAccountName>
               <virtualAccountStatus>1</virtualAccountStatus>
               <virtualAccountTrxType>8</virtualAccountTrxType>
               <billAmount>-50000.000</billAmount>
               <handphoneNumber/>
               <chargesAmount>500.000</chargesAmount>
               <var1Amount>0</var1Amount>
               <var2Amount>0</var2Amount>
               <date1>20062020</date1>
               <exptime>01272900</exptime>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0116                    **            003098700300002031992000000     0  I  0 000000  E        0080069708697190430092710]

[ 0375    0291            0000    000000003098700300002031993396600000040320600 000000  03E        008006970869719043009271000000000114484120KUCING BELANG TIGA                      1Test SIT                                                                        1800000000050000000-                    00000000000500000+00000000000000000+00000000000000000+2006202001272900         ]
```