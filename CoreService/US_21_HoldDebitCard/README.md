Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:HoldDebitCardReq">
               <cardNum>5264222330108796</cardNum>
               <description>BNI CARD SILVER</description>
               <cifNum>9021096442</cifNum>
               <name>RI HANDAYANI JER BASUKI MOWO B</name>
               <status1>Active</status1>
               <status2>Normal</status2>
               <address1>ADD1</address1>
               <address2>. 2</address2>
               <address3>ADD3</address3>
               <address4>2 X 11 Enam Lingkung</address4>
               <postCode>25584</postCode>
               <cardName1>DEWI NOVITASARI</cardName1>
               <cardName2/>
               <registeredDate>2011-07-25</registeredDate>
               <validTo>2014-03-31</validTo>
               <reason>Restricted</reason>
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
               <coreJournal>463368</coreJournal>
            </header>
            <content xsi:type="bo:HoldDebitCardRes">
               <message>O.K.</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0532                    **            003099600100001037273000000     0  I  0 000000  00005264222330108796BNI CARD SILVER               00000009021096442             RI HANDAYANI JER BASUKI MOWO B          Active              Normal                        ADD1                                    . 2                                     ADD3                                    2 X 11 Enam Lingkung                    25584     DEWI NOVITASARI                                             25072011  31032014  Restricted                    ]

[ 1067    0983            0000    000000003099600100001037273463368000040320600 000000  71     O.K.                                                    00  04    003099600100001037273463368    0**         N00 0                Y  I0 000005264222330108796BNI CARD SILVER               00000009021096442             RI HANDAYANI JER BASUKI MOWO B          Active              Normal                        ADD1                                    . 2                                     ADD3                                    2 X 11 Enam Lingkung                    25584     DEWI NOVITASARI                                             25072011  31032014  Restricted                                        31052010  Normal                              000010996                                                                                                                                                                                                                                                                                                                            ]
```