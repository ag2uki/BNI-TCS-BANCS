Sample SOAP Request
```
<soapenv:Envelope xmlns:bo="http://service.bni.co.id/core/bo" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:core="http://service.bni.co.id/core" xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/">
   <soapenv:Header/>
   <soapenv:Body>
      <core:transaction>
         <request>
            <systemId>GLOBS</systemId>
            <content xsi:type="bo:MultiTransferReq">
               <EntriesType/>
               <RateType>1</RateType>
               <Narative1>MULTI TTRANSFER</Narative1>
               <Narative2>XXX</Narative2>
               <Narative3>YYY</Narative3>
               <HighestAmount>985500</HighestAmount>
               <TranType1_1>1</TranType1_1>
               <EntrySetNum_1>1</EntrySetNum_1>
               <CashFlag_1/>
               <AccountNum_1>000000114479721</AccountNum_1>
               <TxnType_1>D</TxnType_1>
               <Amount_1>650000</Amount_1>
               <TranType1_2>1</TranType1_2>
               <EntrySetNum_2>1</EntrySetNum_2>
               <CashFlag_2/>
               <AccountNum_2>000000000555021</AccountNum_2>
               <TxnType_2>C</TxnType_2>
               <Amount_2>500000</Amount_2>
               <TranType1_3>1</TranType1_3>
               <EntrySetNum_3>1</EntrySetNum_3>
               <CashFlag_3/>
               <AccountNum_3>000000115569466</AccountNum_3>
               <TxnType_3>C</TxnType_3>
               <Amount_3>150000</Amount_3>
               <NetTotal>1300000</NetTotal>
               <CreditTotal>650000</CreditTotal>
               <DebitTotal>650000</DebitTotal>
               <EntrySetControl>1</EntrySetControl>
               <DetailRecordControl>3</DetailRecordControl>
            </content>
         </request>
      </core:transaction>
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
            <header xmlns:ns0="bons">
               <coreJournal>901729</coreJournal>
            </header>
            <content xsi:type="bo:MultiTransferRes" xmlns:ns0="bons">
               <Result>0</Result>
               <JournalNum>901729</JournalNum>
               <ResponseDate>31052010</ResponseDate>
               <ResponseTime>14:36:34</ResponseTime>
               <ErrorCode/>
               <ErrorDescription/>
               <Account_1>114479721</Account_1>
               <AccountName_1>Bpk FAJAR  NURCAHYO</AccountName_1>
               <HomeBranch_1>63</HomeBranch_1>
               <Account_2>555021</Account_2>
               <AccountName_2>Ibu MAHATMA  DANDI</AccountName_2>
               <HomeBranch_2>718</HomeBranch_2>
               <Account_3>115569466</Account_3>
               <AccountName_3>Bpk TESTA  TESTB</AccountName_3>
               <HomeBranch_3>718</HomeBranch_3>
               <Account_4/>
               <AccountName_4/>
               <HomeBranch_4/>
               <Account_5/>
               <AccountName_5/>
               <HomeBranch_5/>
               <Account_6/>
               <AccountName_6/>
               <HomeBranch_6/>
               <Account_7/>
               <AccountName_7/>
               <HomeBranch_7/>
               <Account_8/>
               <AccountName_8/>
               <HomeBranch_8/>
               <Account_9/>
               <AccountName_9/>
               <HomeBranch_9/>
               <Account_10/>
               <AccountName_10/>
               <HomeBranch_10/>
               <Account_11/>
               <AccountName_11/>
               <HomeBranch_11/>
               <Account_12/>
               <AccountName_12/>
               <HomeBranch_12/>
               <Account_13/>
               <AccountName_13/>
               <HomeBranch_13/>
               <Account_14/>
               <AccountName_14/>
               <HomeBranch_14/>
               <Account_15/>
               <AccountName_15/>
               <HomeBranch_15/>
               <Account_16/>
               <AccountName_16/>
               <HomeBranch_16/>
               <Account_17/>
               <AccountName_17/>
               <HomeBranch_17/>
               <Account_18/>
               <AccountName_18/>
               <HomeBranch_18/>
               <Account_19/>
               <AccountName_19/>
               <HomeBranch_19/>
               <Account_20/>
               <AccountName_20/>
               <HomeBranch_20/>
               <Account_21/>
               <AccountName_21/>
               <HomeBranch_21/>
               <Account_22/>
               <AccountName_22/>
               <HomeBranch_22/>
               <ResponseCount>3</ResponseCount>
            </content>
         </response>
      </core:transactionResponse>
   </soapenv:Body>
</soapenv:Envelope>
```