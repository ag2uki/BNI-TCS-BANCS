Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>AGREGATOR</systemId>
            <content xsi:type="bo:UpdateUserDefinedCodeReq">
               <accntNumber1>116892513</accntNumber1>
               <TahunHaji>N</TahunHaji>
               <tutupOtomatis>1</tutupOtomatis>
               <kodeBagAnggaran>12</kodeBagAnggaran>
               <handlingCode>3</handlingCode>
               <defaultString1e>t</defaultString1e>
               <KodeDomain>X</KodeDomain>
               <KodeUser/>
               <defaultString2c/>
               <SalesCode>oenjil</SalesCode>
               <defaultString3b/>
               <defaultString4a/>
               <defaultString4b/>
               <defaultString4c/>
               <defaultString5a/>
               <defaultString5b/>
               <defaultString5c/>
               <defaultString6a>0</defaultString6a>
               <KodeKLN>69</KodeKLN>
               <defaultString6c/>
               <JenisGiro>0</JenisGiro>
               <tujuanSetoranJaminan>6</tujuanSetoranJaminan>
               <salesCodesGroup>U</salesCodesGroup>
               <CatInstKeuAkt>3</CatInstKeuAkt>
               <CatInstKeuPasv>5</CatInstKeuPasv>
               <Kualitas>5</Kualitas>
               <CadKerugianTrnNilai>2</CadKerugianTrnNilai>
               <BundlingCode>1</BundlingCode>
               <SkimPembayaran>2</SkimPembayaran>
               <AutoCloseDormant>1</AutoCloseDormant>
               <SatkerBankOps>0006</SatkerBankOps>
               <AccRestriction>002</AccRestriction>
               <Burekol>1</Burekol>
               <KodePenawaran>Y</KodePenawaran>
               <DefaultString8e/>
               <DefaultString9a/>
               <DefaultString9b/>
               <DefaultString9c/>
               <DefaultString9d>0</DefaultString9d>
               <KodeProgMarketing>A6</KodeProgMarketing>
               <DefaultString10a/>
               <DefaultString10b/>
               <DefaultString10c/>
               <DefaultString10d/>
               <DefaultString10e>1</DefaultString10e>
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
               <coreJournal>585875</coreJournal>
            </header>
            <content xsi:type="bo:OKMessage">
               <message>O.K.</message>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0600                    **            003099200100001007044000000     0  I  0 000000  00000000116892513N   112 3tX         oenjil                        0   69    06U355212100060021Y       0 A6         1REK MINOR - DIBUTUHKAN GUARDIAN         ************************************************************************************************************************************************************************************************************************************************************************************************************************************************************************ ]

[ 0162    0078            0000    000000003099200100001007044288208000040320200 000000  080000 O.K.                                                                     ]
```