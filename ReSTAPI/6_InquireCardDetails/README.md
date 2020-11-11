# 37440

Transaction code 37440 is known as DebitCardDetails

Sample SOAP request:
```xml
<soapenv:Envelope
	xmlns:q0="http://service.bni.co.id/core"
	xmlns:bo="http://service.bni.co.id/core/bo"
	xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
	xmlns:xsd="http://www.w3.org/2001/XMLSchema"
	xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
	<soapenv:Body>
		<q0:transaction>
			<request>
				<systemId>BCC_IVR</systemId>
				<content xsi:type="bo:DebitCardDetailsReq">
					<cardNum>1946900600000125</cardNum>
				</content>
			</request>
		</q0:transaction>
	</soapenv:Body>
</soapenv:Envelope>
```

Sample SOAP response:
```xml
<soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:soapenc="http://schemas.xmlsoap.org/soap/encoding/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:dpss0="bons">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transactionResponse xmlns:bo="http://service.bni.co.id/core/bo" xmlns:core="http://service.bni.co.id/core">
         <response>
            <header>
               <coreJournal>251256</coreJournal>
            </header>
            <content xsi:type="bo:DebitCardDetailsRes">
               <cardNum>1946900600000125</cardNum>
               <cardName1>Bpk   M FAISAL JAZULI</cardName1>
               <cardName2/>
               <accountNum1>00000000116905975</accountNum1>
               <cardDescription>BNI PRIVATE LABEL</cardDescription>
               <accountNum2/>
               <accountNum3/>
               <cardStatus1>Active</cardStatus1>
               <cardStatus2>Normal</cardStatus2>
               <maidenName>OK BANGET</maidenName>
               <cifNum>9154882071</cifNum>
               <namaNasabah>Bpk   M FAISAL JAZULI</namaNasabah>
               <validFrom>2016-04-03</validFrom>
               <alamatNasabah>JAWA TENGAH</alamatNasabah>
               <validTo>2021-04-30</validTo>
               <alamatNasabah2>0101</alamatNasabah2>
               <kelurahan>Banjaranyar</kelurahan>
               <tglDibuat>2016-04-03</tglDibuat>
               <kecamatan>Brebes             /Brebes</kecamatan>
               <tglDiemboss>0000-00-00</tglDiemboss>
               <kodePos>52216</kodePos>
               <pickupBranch>259</pickupBranch>
               <telpRumah>021 82428320</telpRumah>
               <tglTerbit>2016-04-03</tglTerbit>
               <telpKantor/>
               <nomorTerbit>1</nomorTerbit>
               <limitHarian>0</limitHarian>
               <sisaLimitHarian>0</sisaLimitHarian>
               <limitMingguan>0</limitMingguan>
               <sisaLimitMingguan>0</sisaLimitMingguan>
               <stopDeskripsi/>
               <foto>N</foto>
               <tglLahir>1991-04-01</tglLahir>
               <handPhone>081297212753</handPhone>
               <cardType>Kartu Debit BNI Indonesia Seja</cardType>
               <subBranch/>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs formated message:
```
[ 0102                    **            003076899900001037440000000     0  I  0 000000  00001946900600000125]

[ 0974    0890            0000    000000003076899900001037441301743000040320600 000000  031946900600000125    Bpk   M FAISAL JAZULI                                       00000001  00000000116905975   BNI PRIVATE LABEL             00000000
             00000000                      Not-ActiveWarm
         OK BANGET                               9154882071          Bpk
 M FAISAL JAZULI                   03042016  JAWA TENGAH
           30042021  0101                                    Banjaranyar
                           03042016  Brebes             /Brebes
             52216     0259      021 82428320        03042016
   0001  00000000000000000+  00000000000000000+                   00000000000000000+  00000000000000000+         04112020                      00000000  00001     Arrears                       0000000000+N01041991081297212753Kartu Debit BNI Indonesia Seja0000]
```