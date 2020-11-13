Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>NEWIBANK-CORE</systemId>
            <content xsi:type="bo:CustomerDetailReq">
               <accountNum>00000000116896595</accountNum>
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
               <coreJournal>238277</coreJournal>
            </header>
            <content xsi:type="bo:CustomerDetailRes">
               <flag>A1</flag>
               <jenisNasabah>01</jenisNasabah>
               <namaNasabah>EDWARD VAN DER KAATSEN</namaNasabah>
               <gelar/>
               <titleCode>99</titleCode>
               <accountCurrency>IDR</accountCurrency>
               <tempatLahir>bali</tempatLahir>
               <tglLahir>1991-11-19</tglLahir>
               <alamatId>JL. BUNTU NO. 00</alamatId>
               <rt>010</rt>
               <rw>5</rw>
               <perum/>
               <kelurahan>Cipaku</kelurahan>
               <kecamatan>Bogor SltnBogor</kecamatan>
               <kodePos>16133</kodePos>
               <jalan2>JL. BUNTU NO. 00</jalan2>
               <rt2>010</rt2>
               <rw2>5</rw2>
               <perum2/>
               <kelurahan2>Cipaku</kelurahan2>
               <kecamatan2>Bogor SltnBogor</kecamatan2>
               <kodePos2>16133</kodePos2>
               <telpRumah>02518234567</telpRumah>
               <telpKantor/>
               <handPhone>081283218838</handPhone>
               <fax/>
               <email>Setyanto.Anggara@bni.co.id</email>
               <npwp>213213213321312</npwp>
               <wargaCode>ID</wargaCode>
               <jenisId>0001</jenisId>
               <tempatId>dfsdfsdfsd</tempatId>
               <noId>3423423432423555</noId>
               <tglTerbit>-  -0</tglTerbit>
               <tglHabis>2019-06-30</tglHabis>
               <sumberInfo/>
               <maidenName>Mariana Philips</maidenName>
               <maritalIndikator>S</maritalIndikator>
               <jumlahAnak/>
               <religiCode>2</religiCode>
               <educationCode>06</educationCode>
               <jobCode>01</jobCode>
               <namaPerusahaan>Bos</namaPerusahaan>
               <alamatPerusahaan>bali                          bali</alamatPerusahaan>
               <postCodePerusahaan/>
               <startJobDate>0</startJobDate>
               <gaji>4</gaji>
               <namaAlias>VAN DER KAATSEN</namaAlias>
               <frekuensiGaji>M</frekuensiGaji>
               <gajiLain>000000000000000</gajiLain>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```