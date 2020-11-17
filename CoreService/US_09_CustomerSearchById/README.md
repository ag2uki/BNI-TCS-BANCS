Sample SOAP Request
```
<soapenv:Envelope xmlns:q0="http://service.bni.co.id/core" xmlns:bo="http://service.bni.co.id/core/bo" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
   <soapenv:Body>
      <q0:transaction>
         <request>
            <systemId>KSEI</systemId>
            <content xsi:type="bo:CustomerSearchByIdReq">
               <numId>3579010807920001</numId>
               <idType>0001</idType>
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
               <coreJournal>318711</coreJournal>
            </header>
            <content xsi:type="bo:CustomerSearchByIdRes">
               <cif_number>915488349-4</cif_number>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```

Bancs Format
```
[ 0110                    **            003098700100001060465000000     0  I  0 000000  3579010807920001        0001]

[ 0564    0480            0000    000000003098700100001060465318711000040320000 000000  03  99   SATRIA                                   915488349-4                            SAMBRAMA                                                                        27051985       M           M        0003                                          11691386-2 DEP            11691387-3 DEP            11691388-4 DEP              11691389-5 DEP            11691523-6 DEP            11693339-0 DEP              11693340-3 DEP            11694776-7 DEP            11694786-9 DEP             126911904-8 DEP            12691190-9 DEP            12691191-0 DEP              11705350-8 DEP            11707116-3 DEP            11708664-6 DEP              11710907-5 LON            11444435-8 DEP            11445097-3 DEP              11445506-4 LON            11445800-9 DEP            11445805-4 DEP              11446359-6 LON            11447221-6 DEP            11447223-8 DEP              11447224-9 DEP            11447226-1 DEP            11447229-4 DEP              11447232-9 DEP            11447237-4 DEP            11447238-5 DEP              11447240-9 DEP            11447359-3 DEP            11447360-5 DEP              11447856-9 DEP            11448228-1 DEP           201988883-1 DEP              11449669-0 DEP            11450675-6 DEP            11457605-4 DEP              11457653-2 DEP            11458685-7 DEP            11459914-1 DEP              11474224-1 DEP            11474479-2 DEP            11474519-5 DEP              11474558-2 DEP            11474568-3 DEP            11474612-1 DEP              11479301-3 DEP            11479302-4 DEP                               TGLHR (        ) SEX ( ) MARITAL ( ) PEK  (    )      Create                    ]
```