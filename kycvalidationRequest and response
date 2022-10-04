curl -X POST \
  https://XXXXXXX:8022/pullremittance/validatekyc \
  -H 'Accept: */*' \
  -H 'Cache-Control: no-cache' \
  -H 'Connection: keep-alive' \
  -H 'Content-Type: text/xml' \
  -H 'Host: 127.0.0.1:8022' \
  -H 'Postman-Token: 4d7299ce-b927-41c5-b922-13a289827f3e,7676adc6-97c5-4153-a797-f68b2644b929' \
  -H 'User-Agent: PostmanRuntime/7.13.0' \
  -H 'accept-encoding: gzip, deflate' \
  -H 'cache-control: no-cache' \
  -H 'content-length: 824' \
  -d '<?xml version="1.0" encoding="UTF-8"?>
<request>
   <systemInfo>
      <userName>Bkash</userName>
      <password>Bkash123!</password>
      <timestamp>2020-05-01 00:00:00</timestamp>
   </systemInfo>
   <recipientInfo>
      <msisdn>+8801823077387</msisdn>
      <idDocument>
         <idNumber>1823077423</idNumber>
 		 <idType>01</idType>
         <issueDate>23122006</issueDate>
         <expiryDate>23122045</expiryDate>
      </idDocument>
   </recipientInfo>
 <channelCode>01</channelCode>
 <txnReference>w40</txnReference>
   <thirdPPInfo>
      <thirdPPName>WU</thirdPPName>
      <additionalInfo>
         <info key="agentMsisdn" value="01987554322"/>
         <info key="key2" value="val2" />
         <info key="key3" value="val3" />
      </additionalInfo>
   </thirdPPInfo>
</request>'

Response:
<?xml version="1.0" encoding="UTF-8" standalone="yes"?>
<response>
    <status>
        <responseCode>4500</responseCode>
        <responseMessage>kyc verification successful</responseMessage>
    </status>
</response>
