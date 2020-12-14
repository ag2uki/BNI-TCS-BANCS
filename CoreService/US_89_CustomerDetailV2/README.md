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
            <content xsi:type="bo:CustomerDetailV2Req">
               <accountNum>0116910930</accountNum>
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
               <coreJournal>574220</coreJournal>
            </header>
            <content xsi:type="bo:CustomerDetailV2Res">
               <flag>A1</flag>
               <jenisNasabah>01</jenisNasabah>
               <namaNasabah>STEVEN RAMA SI RAMAI RAMAI</namaNasabah>
               <gelar/>
               <titleCode>03</titleCode>
               <accountCurrency>IDR</accountCurrency>
               <tempatLahir>JAKARTA</tempatLahir>
               <tglLahir>1985-05-27</tglLahir>
               <alamatId>JALAN PANJANG HARI BARU</alamatId>
               <rt/>
               <rw/>
               <perum/>
               <kelurahan>Jati</kelurahan>
               <kecamatan>Sumbawa</kecamatan>
               <kodePos>84311</kodePos>
               <jalan2>JALAN PANJANG HARI BARU</jalan2>
               <rt2/>
               <rw2/>
               <perum2/>
               <kelurahan2>Jati</kelurahan2>
               <kecamatan2>Sumbawa</kecamatan2>
               <kodePos2>84311</kodePos2>
               <telpRumah/>
               <telpKantor/>
               <handPhone>085233333333</handPhone>
               <fax/>
               <email/>
               <npwp>NOT FOUND</npwp>
               <wargaCode>ID</wargaCode>
               <jenisId>0001</jenisId>
               <tempatId>JAKARTA</tempatId>
               <noId>3171055702880001</noId>
               <tglTerbit>-  -0</tglTerbit>
               <tglHabis>2025-10-31</tglHabis>
               <sumberInfo/>
               <maidenName>Nur</maidenName>
               <maritalIndikator>S</maritalIndikator>
               <jumlahAnak/>
               <religiCode>0</religiCode>
               <educationCode>00</educationCode>
               <jobCode>01</jobCode>
               <namaPerusahaan>wwqeqwe</namaPerusahaan>
               <alamatPerusahaan>wewqedsad                     asdasd</alamatPerusahaan>
               <postCodePerusahaan/>
               <startJobDate>0</startJobDate>
               <gaji>3</gaji>
               <namaAlias>BELA</namaAlias>
               <frekuensiGaji>M</frekuensiGaji>
               <gajiLain>000000000000000</gajiLain>
               <depositoCode>BNI TAPLUS</depositoCode>
               <depcode1>2000</depcode1>
               <depcode2>0001</depcode2>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0099 ** 003025900000001069490000000 0 I 0 000000 00000000116910930]

[ 1067 0983 0000 000000003025900000001069491288187000040320400 000000 03A101STEVEN RAMA SI RAMAI RAMAI 03IDRJAKARTA 27051985JALAN PANJANG HARI BARU Jati Sumbawa 84311 JALAN PANJANG HARI BARU Jati Sumbawa 84311 085233333333 00 NOT FOUND ID0001JAKARTA 3171055702880001 0 31102025 Nur S0000001wwqeqwe wewqedsad asdasd 0 03BELA M000000000000000 00000000116910930BNI TAPLUS 00000000000000000000000R1200000000755000000 000000000000000000 0000000910020870520000001 085233333333 ]
```