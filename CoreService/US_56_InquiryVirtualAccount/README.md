Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>SYARIAH</systemId>
            <customHeader>
               <teller>00001</teller>
               <branch>0259</branch>
               <overrideFlag>I</overrideFlag>
            </customHeader>
            <content xsi:type="bo:InquiryVirtualAccountReq">
               <virtualAccountType>988</virtualAccountType>
               <companyCode>244</companyCode>
               <virtualAccountNum>9880024408522120</virtualAccountNum>
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
               <coreJournal>565520</coreJournal>
            </header>
            <content xsi:type="bo:InquiryVirtualAccountRes">
               <virtualAccountType>988</virtualAccountType>
               <companyCode>244</companyCode>
               <virtualAccountNum>9880024408522120</virtualAccountNum>
               <accountNum>883</accountNum>
               <companyName>Pegadaian 988</companyName>
               <accountStatus>1</accountStatus>
               <virtualAccountName>Pegadaian 120</virtualAccountName>
               <virtualAccountStatus>1</virtualAccountStatus>
               <virtualAccountTrxType>7</virtualAccountTrxType>
               <billAmount>0</billAmount>
               <handphoneNumber/>
               <chargesAmount>0</chargesAmount>
               <var1Amount>0</var1Amount>
               <var2Amount>0</var2Amount>
               <date1>99999999</date1>
               <exptime>00000000</exptime>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0116 ** 003099900100027031992000000 0 I 0 000000 E 9886001109886001120091503]

[ 0375 0291 0000 000000003099900100027031993252384000040320600 000000 03E 988600110988600112009150300000000114484120PT MENCARI CINTA SEJATI 1Test TAP 1100000000000000000+ 00000000000500000+00000000000000000+00000000000000000+0611202106494400 ]
```