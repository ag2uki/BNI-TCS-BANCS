Sample SOAP Request
```
<soap:Envelope xmlns:soap="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xsd="http://www.w3.org/2001/XMLSchema">
   <soap:Body>
      <transaction xmlns="http://service.bni.co.id/core">
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="q1:CreateTopUpAccountReq" xmlns:q1="http://service.bni.co.id/core/bo">
               <cifNum>9154879806</cifNum>
               <customerName>EDWARD VAN DER KAATSEN</customerName>
               <address1>JL. BUNTU NO. 00</address1>
               <address2>0105</address2>
               <npwp>Y</npwp>
               <address3>Cipaku</address3>
               <nationality>ID</nationality>
               <address4>Bogor Sltn Kota /Bogor</address4>
               <postalCode>16133</postalCode>
               <accountType>2800</accountType>
               <subCategory>0001</subCategory>
               <interestPayMethod>R</interestPayMethod>
               <interestRateVar>0</interestRateVar>
               <day/>
               <unsigned08>0</unsigned08>
               <domesticRisk>18</domesticRisk>
               <crossRisk>ZZ</crossRisk>
               <openDate>0000-00-00</openDate>
               <appropriateRate>0</appropriateRate>
               <tprRate>0</tprRate>
               <openAcctRes>2</openAcctRes>
               <srcOfFund>3</srcOfFund>
               <srcOfFund1/>
               <projDep>0</projDep>
               <projWdl>0</projWdl>
               <acctRatio>0</acctRatio>
               <bicLimit>0</bicLimit>
               <insuTerm>12</insuTerm>
               <autoClose>Y</autoClose>
               <autoPremium>Y</autoPremium>
               <monthPay>100000</monthPay>
               <addCover>0</addCover>
               <affiAcctNo>0114470525</affiAcctNo>
               <princArrears>0</princArrears>
               <premcArrears>0</premcArrears>
               <addSkim>2</addSkim>
               <sourceAccount>0114470525</sourceAccount>
            </content>
         </request>
      </transaction>
   </soap:Body>
</soap:Envelope>
```

Sample SOAP Response
```
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header>
               <coreJournal>464512</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>O.K. 003 11460063-5 0996 001 00001 00000000000000000+ 000000</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 1055                    **            003099600100001002085000000     0  I  0 000000  0000000000000000000000009154879806                        0000EDWARD VAN DER KAATSEN                                      JL. BUNTU NO. 00                        0105                                    YCipaku                                  ID Bogor Sltn Kota    /Bogor               16133   28000001   R   00000000000000000000004  01000000000000000000000000      0000000000000000       000000000000000000                       000000000000000                 0000 00000000000000000+            18ZZZZBZZ                                     00000000000 0000000+0     00000000000000000                   000000000000          00000002                    0003                              000000000000000000000000000000000000000000000000000000000000000000000000012YY00000000100000000+00000000001144705250000000000000000000000000000000000+00000000000000000+2                                                                                                   00000000114470525]

[ 0162    0078            0000    000000003099600100001002085464512000040320200 000000  080000 O.K. 003         11460063-5 0996 001 00001 00000000000000000+ 00000000000]
```