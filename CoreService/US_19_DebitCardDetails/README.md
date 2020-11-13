Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>PHONEBANKING</systemId>
            <content xsi:type="bo:DebitCardDetailsReq">
               <cardNum>6010041002001443</cardNum>
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
               <coreJournal>396468</coreJournal>
            </header>
            <content xsi:type="bo:DebitCardDetailsRes">
               <cardNum>6010041002001443</cardNum>
               <cardName1>Sdr I</cardName1>
               <cardName2/>
               <accountNum1>00000000114448749</accountNum1>
               <cardDescription>BNI DEBIT CARD</cardDescription>
               <accountNum2/>
               <accountNum3/>
               <cardStatus1>Active</cardStatus1>
               <cardStatus2>Normal</cardStatus2>
               <maidenName/>
               <cifNum>9100208705</cifNum>
               <namaNasabah>Sdr STEVEN RAMA SI RAMAI RAMAI</namaNasabah>
               <validFrom>2018-07-05</validFrom>
               <alamatNasabah>TES2</alamatNasabah>
               <validTo>2023-07-31</validTo>
               <alamatNasabah2/>
               <kelurahan>TES2</kelurahan>
               <tglDibuat>2018-07-05</tglDibuat>
               <kecamatan>Setia Budi</kecamatan>
               <tglDiemboss>0000-00-00</tglDiemboss>
               <kodePos>12910</kodePos>
               <pickupBranch>100</pickupBranch>
               <telpRumah>083082038</telpRumah>
               <tglTerbit>2018-07-05</tglTerbit>
               <telpKantor/>
               <nomorTerbit>1</nomorTerbit>
               <limitHarian>0</limitHarian>
               <sisaLimitHarian>0</sisaLimitHarian>
               <limitMingguan>0</limitMingguan>
               <sisaLimitMingguan>-60000.00</sisaLimitMingguan>
               <stopDeskripsi/>
               <foto>N</foto>
               <tglLahir>1985-05-27</tglLahir>
               <handPhone>087888888</handPhone>
               <cardType>PT ANGKASA PURA II</cardType>
               <subBranch/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```