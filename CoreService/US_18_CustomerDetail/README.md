Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" 
xmlns:bo="http://service.bni.co.id/core/bo" 
xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" 
xmlns:xsd="http://www.w3.org/2001/XMLSchema" 
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:CustomerDetailReq">
               <accountNum>0115471119</accountNum>
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
               <coreJournal>298671</coreJournal>
            </header>
            <content xsi:type="bo:CustomerDetailRes">
               <flag>A1</flag>
               <jenisNasabah>01</jenisNasabah>
               <namaNasabah>JONOMADE MADEMADEMADEMADE IMAMADE</namaNasabah>
               <gelar>S.KOM</gelar>
               <titleCode>01</titleCode>
               <accountCurrency>IDR</accountCurrency>
               <tempatLahir>erwrwrwerewr</tempatLahir>
               <tglLahir>1985-05-27</tglLahir>
               <alamatId>BENDI VII NO 14</alamatId>
               <rt/>
               <rw/>
               <perum/>
               <kelurahan>kebayoran</kelurahan>
               <kecamatan>Kebayoran</kecamatan>
               <kodePos>12120</kodePos>
               <jalan2>BENDI VII NO 14</jalan2>
               <rt2/>
               <rw2/>
               <perum2/>
               <kelurahan2>kebayoran</kelurahan2>
               <kecamatan2>Kebayoran</kecamatan2>
               <kodePos2>12120</kodePos2>
               <telpRumah/>
               <telpKantor/>
               <fax/>
               <email/>
               <npwp>123456789012345</npwp>
               <wargaCode>ID</wargaCode>
               <jenisId>0001</jenisId>
               <tempatId>JAKARTA</tempatId>
               <noId>3205040810881234</noId>
               <tglTerbit>-  -0</tglTerbit>
               <tglHabis>2026-11-05</tglHabis>
               <sumberInfo/>
               <maidenName>raika</maidenName>
               <maritalIndikator>S</maritalIndikator>
               <jumlahAnak/>
               <religiCode>0</religiCode>
               <educationCode>00</educationCode>
               <jobCode>01</jobCode>
               <namaPerusahaan>ewrew</namaPerusahaan>
               <alamatPerusahaan>wrerwer                       werwer</alamatPerusahaan>
               <postCodePerusahaan/>
               <startJobDate>0</startJobDate>
               <gaji>2</gaji>
               <namaAlias>IMAMADE</namaAlias>
               <frekuensiGaji>M</frekuensiGaji>
               <gajiLain>000000000000000</gajiLain>
               <handPhone>000000001154</handPhone>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0099                    **            003099600100001069490000000     0  I  0 000000  00000000115471119]

[ 1067    0983            0000    000000003099600100001069491298671000040320400 000000  03A101JONOMADE MADEMADEMADEMADE IMAMADE                           S.KOM   01IDRerwrwrwerewr                  27051985BENDI VII NO 14                                                                 kebayoran           Kebayoran           12120   BENDI VII NO 14                                                                 kebayoran           Kebayoran           12120                           089534641949            00                                           123456789012345 ID0001JAKARTA                       3205040810881234    0       05112026 raika                                   S0000001ewrew                                                       wrerwer                       werwer                                0       02IMAMADE          M000000000000000            00000000115471119TAPLUS BISNIS PERORANGAN    00000000000000000000000R1600000000004000000   000000000000000000                                                             0000000914478236323000001    089534641949                            ]
```