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