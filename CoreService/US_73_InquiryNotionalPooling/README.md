Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>BNIDIRECT</systemId>
            <content xsi:type="bo:InquiryNotionalPoolingReq">
               <mainAccountNo>883</mainAccountNo>
               <currentPage></currentPage>
               <notPolID></notPolID>
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
               <coreJournal>237471</coreJournal>
            </header>
            <content xsi:type="bo:InquiryNotionalPoolingRes">
               <function>E</function>
               <companyName>test 123</companyName>
               <mainAccountNo>883</mainAccountNo>
               <status>1</status>
               <currentPage>1</currentPage>
               <totalPage>2</totalPage>
               <notPolID>NPLM01</notPolID>
               <notionalBalance>39842368448.000</notionalBalance>
               <thresholdAmt>500000.000</thresholdAmt>
               <accNo1>883</accNo1>
               <branchName1>PT Coba 123</branchName1>
               <balance1>39809172448.000</balance1>
               <limit1>39809172448.000</limit1>
               <status1>1</status1>
               <accNo2>800063</accNo2>
               <branchName2>detail 06</branchName2>
               <balance2>9601000.000</balance2>
               <limit2>9601000.000</limit2>
               <status2>1</status2>
               <accNo3>800074</accNo3>
               <branchName3>detail 05</branchName3>
               <balance3>5000000.000</balance3>
               <limit3>5000000.000</limit3>
               <status3>1</status3>
               <accNo4>800085</accNo4>
               <branchName4>detail 04</branchName4>
               <balance4>5000000.000</balance4>
               <limit4>5000000.000</limit4>
               <status4>1</status4>
               <accNo5>6547898</accNo5>
               <branchName5>pooling 01</branchName5>
               <balance5>5000000.000</balance5>
               <limit5>5500000.000</limit5>
               <status5>1</status5>
               <accNo6>7777558</accNo6>
               <branchName6>detail 02</branchName6>
               <balance6>1250000.000</balance6>
               <limit6>1400000.000</limit6>
               <status6>2</status6>
               <accNo7>81210683</accNo7>
               <branchName7>detail 03</branchName7>
               <balance7>3350000.000</balance7>
               <limit7>3350000.000</limit7>
               <status7>1</status7>
               <accNo8>117063731</accNo8>
               <branchName8>create no 9</branchName8>
               <balance8>20000.000</balance8>
               <limit8>20000.000</limit8>
               <status8>1</status8>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0199                    **            003098900100001060428000000     0  I  0 000000  E                                                00000000000000883 00000000      00000000000000000+00000000000000000+]

[ 1002    0918            0000    000000003098900100001060428237471000040320200 000000  03E        test 123                                00000000000000883100010002NPLM0100039842368448000+00000000500000000+00000000000000883PT Coba 123                             00039809172448000+00039809172448000+100000000000800063detail 06                               00000009601000000+00000009601000000+100000000000800074detail 05                               00000005000000000+00000005000000000+100000000000800085detail 04                               00000005000000000+00000005000000000+100000000006547898pooling 01                              00000005000000000+00000005500000000+100000000007777558detail 02                               00000001250000000+00000001400000000+200000000081210683detail 03                               00000003350000000+00000003350000000+100000000117063731create no 9                             00000000020000000+00000000020000000+1                                                 ]
```