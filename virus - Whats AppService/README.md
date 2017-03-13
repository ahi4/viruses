# viruses


The e-mail in the **[Screenshot from 2017-03-13 01-21-10.png](https://github.com/ricoms/viruses/blob/master/virus%20-%20Whats%20AppService/Screenshot%20from%202017-03-13%2001-21-10.png)** has the link: http://callalilywines.com/wp-content/themes/controllable.php into that "Play" button. I tried to see what is inside that url, but it just stays loading... and I got afraid of breakin my computer this time, so I stoped it.

http://callalilywines.com is a domain registered in Arizona, and a fast google search "whois callalilywines.com" returned, as 2nd result, a "Domains actively hosting malware", as seen in **[Screenshot from 2017-03-13 01-29-05.png](https://github.com/ricoms/viruses/blob/master/virus%20-%20Whats%20AppService/Screenshot%20from%202017-03-13%2001-29-05.png)**. And from http://www.statsinfinity.com/domain/sOw0tX-M7W1HEtvIz2xFdf0Hv6qPnX8T_info.html I got their tech email contact callalilywines.com@domainsbyproxy.com, but nothing like an @abuse email.
At DomainsByProxy.com website I see lots of information about Scams & Security, but no @abuse email neither found them on twitter.

The Sender IP of the email is 190.0.226.42 located in Costa Rica and an email contact cmoreno@CYBERFUEL.COM, information from https://myip.ms/info/whois/190.0.226.42. I did not find CyberFuel on twitter but they have this website: https://www.cyberfuel.com/

Case sent to their respective emails.

# email header origin:

Received: from FR1P152CA0129.LAMP152.PROD.OUTLOOK.COM (10.171.39.149) by
 RO1P152MB1482.LAMP152.PROD.OUTLOOK.COM (10.171.137.13) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.947.12 via Mailbox Transport; Mon, 13 Mar 2017 00:19:21 +0000
Received: from inbound.mail.protection.outlook.com (216.32.180.17) by
 FR1P152CA0129.outlook.office365.com (10.171.39.149) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.961.17 via Frontend Transport; Mon, 13 Mar 2017 00:19:20 +0000
Received: from SN1NAM02FT002.eop-nam02.prod.protection.outlook.com
 (10.152.72.57) by SN1NAM02HT055.eop-nam02.prod.protection.outlook.com
 (10.152.73.129) with Microsoft SMTP Server (version=TLS1_2,
 cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id 15.1.947.7; Mon, 13 Mar
 2017 00:19:18 +0000
Authentication-Results: spf=none (sender IP is 190.0.226.42)
 smtp.mailfrom=excite.co.uk; hotmail.com; dkim=none (message not signed)
 header.d=none;hotmail.com; dmarc=none action=none header.from=excite.co.uk;
Received-SPF: None (protection.outlook.com: excite.co.uk does not designate
 permitted sender hosts)
Received: from BAY004-MC2F50.hotmail.com (10.152.72.59) by
 SN1NAM02FT002.mail.protection.outlook.com (10.152.72.94) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.961.10 via Frontend Transport; Mon, 13 Mar 2017 00:19:18 +0000
X-IncomingTopHeaderMarker: OriginalChecksum:E2D80AACDFA80CE9C16A40C206A3247AA7360B4E8267D264759B40501A856458;UpperCasedChecksum:B1582CDE86A26F49FB965F104E588C4957F63192F6423968E3F8ADDCFFDD4A93;SizeAsReceived:727;Count:14
Received: from thalmanmusic.com ([190.0.226.42]) by BAY004-MC2F50.hotmail.com with Microsoft SMTPSVC(7.5.7601.23143);
	 Sun, 12 Mar 2017 17:19:17 -0700
From: Whats AppService <eggie2@excite.co.uk>
Necessitated-Ham-Exacerbating: DD2EAC8F41F2385A
Date: Sun, 12 Mar 2017 18:17:34 +0000
To: "ricardosavii@hotmail.com" <ricardosavii@hotmail.com>
Dominant-Budgeted: 8fa64ceb9ca85f
Subject: Missed voicemessage - 6:17PM
Content-Type: text/html; charset="UTF-8"
Message-ID: <a8254fee841eB2f7DecF8fED1BadFccCAfaeA8AF2b@excite.co.uk>
Content-Transfer-Encoding: 7bit
Deciphers-Vida: 9363
Return-Path: eggie2@excite.co.uk
X-OriginalArrivalTime: 13 Mar 2017 00:19:17.0951 (UTC) FILETIME=[74364CF0:01D29B8F]
X-IncomingHeaderCount: 14
X-MS-Exchange-Organization-Network-Message-Id: 0594fd39-ad18-404c-5be6-08d469a69757
X-EOPAttributedMessage: 0
X-EOPTenantAttributedMessage: 84df9e7f-e9f6-40af-b435-aaaaaaaaaaaa:0
X-MS-Exchange-Organization-MessageDirectionality: Incoming
CMM-sender-ip: 190.0.226.42
CMM-sending-ip: 190.0.226.42
CMM-Authentication-Results: hotmail.com; spf=none (sender IP is 190.0.226.42)
 smtp.mailfrom=eggie2@excite.co.uk; dkim=none header.d=excite.co.uk;
 x-hmca=none header.id=eggie2@excite.co.uk
CMM-X-SID-PRA: eggie2@excite.co.uk
CMM-X-AUTH-Result: NONE
CMM-X-SID-Result: NONE
CMM-X-Message-Status: n:n
CMM-X-Message-Delivery: Vj0xLjE7dXM9MDtsPTA7YT0wO0Q9MjtHRD0yO1NDTD02
CMM-X-Message-Info: 3c21WZ1hAltI9DuizMAEE41BI5AyVQJy5WKTrkRtozy7n8uROmdGq3/zf6xX1b5ieN79B32pH1ThMwRraCKW/VXWtlnuRWbt0yYU9nUtwKR4NRqwZWO7dnfaYCgUEZGliKlMFvl8ZmlR5skCdvXT57rnCc7EoLhKYjWniyFjVAWTtia2/E04Xq/Gf9hscN0du54dqvkmXG2liIJiJPsWmvOSFM1ka1GzdAVw9SmYzr4Yq+NE2ijdwg==
X-MS-Exchange-Organization-PCL: 2
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM02FT002;1:PDZmE5ADZNrbJ8MTAojeRQPG95A6Ck+eOehbFuUBK+L9C6A8LMyr3tP3wwvtc9EQqfxM4xPETYTPLgyL1kYSvV+QwuRiCWbRwGgAau7mC6Klk2W2pgUQbXrxUXBsCr/PhRMM7aPoBM9+rY7BsZ0qHtKPJiYR+BqVJpLTo5o+Vw4=
X-Forefront-Antispam-Report: EFV:NLI;SFV:SPM;SFS:(28900001);DIR:INB;SFP:;SCL:5;SRVR:SN1NAM02HT055;H:BAY004-MC2F50.hotmail.com;FPR:;SPF:None;LANG:en;
X-MS-Office365-Filtering-Correlation-Id: 0594fd39-ad18-404c-5be6-08d469a69757
X-Microsoft-Antispam: BCL:0;PCL:0;RULEID:(22001)(8291500097)(8291501071);SRVR:SN1NAM02HT055;
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM02HT055;3:9FcFmEYAx2PC7u6O9uYRm7dOcjb/GrwVKumzRafU5hfMraRF+x4S3GLUhbqRk6PGSkOfx1+aegGNILqLzCI0QeZru/AL0kVl1/n3forDjUSL05XrpA5RL59Isd8Lq9Q+CfxEVrci5/9kyqnJDyv+gWUpS7LBVhQD7eUklgej/6arrB/BVTQbLXoFnGjClBxeP0Hn94YOQw5OUeOVbBXd7EIxu6lSLjlevwZ16YI7QtDBXSihEuCFBLpm0Ir6ElgGBfLXv8dKsg9bro9FdZ0dl9BBGx0FnVCUwuQSx0MwKKVoZ5UUsGCDaPgutNzlLNMOjou9a2da8Ji8xFConXYwTFlpZmB0IQn+kdkBfjjIuu1h+Quox+Iq7vuRzUugIYYC
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM02HT055;25:OYr9P+pEy0JkTL08a75uX66iFms+TtLoGlI1lDCbNVr96p9Ti9FCRaCbBDIYlqaudARERRC87dKj3cXxHck0dSUmROJ2+p+WG2sezUweobK9qqNT1Ihc8YppPvuNUDXo30mjahEiB+B2EIaWyP05vGmjZAEfceIwfIADrzcW4uPUOwLVZFr/Zv2YS2aw04IN+jRC6k0paqWePOesRzg2gdFW6IYxDTExsaAiLm3ToEouVb6SzJDQW8I0As55ogj8Z8qH5PnqBn8U3mUs6OUgaZfN8xiNnnBuv059eYkd8nWXdI2gZzxwP/PFbxGU9Op6GPaPsCFm3IPBMJ4sVm4MhW554fx+J9mUzb4Ov3/6LsgcdIFVwm00nuIm45DuA2qhjj1OuZCoY7aTOUlAXxtU54mWU9pkBHsy2KXVC6384rlA7VSj3qt+n4PJudnRKshQ1o7LIPykNHogbnJjudF+6f+q0ZOpZaO5KFQluOwZePmY4e3aWeqaxH4DOtF5x3TPouysrF968GqGJmzyQJHB7ye64bwbbYr3lT32d7i2/CnHAF+VkWahlTXmwuYlLN64;31:Pl18QcTW2jTRY9bp1q09nYQ4bEIU8RuxA5ONJHPF/yFBPe4pbdHhKikS3p5kAMN2fr32z3BtgEv5eRG/K+ZfMQN2CM9oQwqK8lW03LdTsx6LoHaM6dzEYEXQfnhJ8xOOIEZ8rvmPJvlyHjkQzHPLBUk8e89Taz1trDF7+cSNjOkKKz3t0QWJ6GswOrUlLmEsdd7PYCyChAjcj8Skg3vv/vvrdKNWj6NGCK+ocSfdsstGZqAgywSo20x6ETcngGfBVX+ijhprlm7gM2blunQxNw==
X-MS-Exchange-Organization-AVStamp-Service: 1.0
X-Exchange-Antispam-Report-CFA-Test: BCL:0;PCL:0;RULEID:(444000031);SRVR:SN1NAM02HT055;BCL:0;PCL:0;RULEID:;SRVR:SN1NAM02HT055;
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM02HT055;4:j+ipKvYOlIvFauWgDeTcun9eFa7zlHpB1Uuj3RwnVZ76Uc3TW0cej/hOoVP/Co6IYo8CpAzCZ5J3qkEVNmR2XkeAbsKC40uhaiOnewpRZoyOEc/J6cG3XNFLPWQJeTdx8OeCcnHgNzLfI4sQDirgPzq8PwUnmWagsGkNTUGurYISQC4TDf0zVTPwkgYC5HIE2J7T5vFXSL8gFonNDuWADCUJYaVdEPbaVAq85V7XSQ7x1h4voKDEfuhORNt+7VbWqtp5sc9KrRArAql1IXiYW639NeEB+F1k6Ex8Mn64how=;23:VtVYPNtpYTuG20mfnSakbWF74Z74yT5yMZAGeulAhizdcrimzxlczSzW5/W1FlPZXZGKReW8pI7p9DSZV4JZXezKeE3xmxwxaibpiRGyxALVxPTmMbDcn5/z0IAYeozqucYzFUuJefStU391bPipoDWPaqO4IVLtUBZ/NlfxfRgMdFCP5r3pcuGmccdCcOlyJcVCmjs+zW6CiZU4yActqQ==;6:AxV8hEUsMyu2p0pWWFL0wX4QD0+qLeuxgKrolxc9i3bzpmCu9sJWNH/Ysmqst5VPcJtzENAM7njEFmw+6W5bal129dLxhZCCBqIrxSyIQCWeLX3NGqZb0ADy0ubXmLyLZNTGp6sOKSzeShqKTxgPHDQ/3dOLFEC7YUUQ+hHIznuyqcHl7LxRikFHKUJ34dBecO1nFRo3ubSTPo+GnTfd+ckI/vZmR1YoPu2LNR+TFrmRhRk7Oej8yP+laC48HbKRA8fs53qRBqFEW6GiQhCKURghvowvjs3t5qdls0xTwiH4vhsoOqWaNXFOKSx/89/Rt4XCgfYNlhgZExZQ5Zs8DdF5dUVDHzzPFbeXPqcJmPHEdmXBbfQMq2wH4vtpKCvmwHdE9q5X36cB/wqRv5riJA==
X-MS-Exchange-Organization-SCL: 5
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM02HT055;5:IqJnyXA2RbqzugYy6Jry3tJpVPCcfUtNWG/ixDsKcbsblW3nYE5cpOaQkJMWqCY+IXG++l37AMPGEajcBeZQqGkpS2v7wV5Drv5v7N+FrexQiCuhZzEKSYpXsys1sXmvG9cBvgVek6JaUUsARRbVqQ==;24:6LJ+jrlMUNa9bBH0GQXbgw3M/4Nbn7aV9pfnlXf4eYKee8Kaf/3R260b4/NOjjxLzMmMIhPCCJyoc/83JD973A==;7:DxaQk+QTsC89jzUTeM+hFzsUhTOK+rnXxLbvEqe24clA1pnWWXM9ICLL0Uvie2MKT1ztzYY9i/8mlgQS10nmUt3PrxfEDu2mzOUbuerImxON158A8lW2w55hNBMej08XQkxdtY5PvJVgwq9MwlWsTC2uMuXUUUBgp9OfibCBIqYbWoZ1x6wSsTxqyTzWB2WeIliW6kC8gqXPSoNZ1PctxCdLGdwR2NDZR9FMag1rtND5NjIli0ByIIHzWOpsnW2eVI+Nbt9yLjEvmb5qtvpMqleM81vKvTVinKOBL+TZzAU7kB2aJFzM+hLEq6Z+SY7qGHhIUjVJqWCENsixYYPxvA==
SpamDiagnosticOutput: 1:22
SpamDiagnosticMetadata: Default
X-MS-Exchange-CrossTenant-OriginalArrivalTime: 13 Mar 2017 00:19:18.1748
 (UTC)
X-MS-Exchange-CrossTenant-Id: 84df9e7f-e9f6-40af-b435-aaaaaaaaaaaa
X-MS-Exchange-CrossTenant-FromEntityHeader: Internet
X-MS-Exchange-Transport-CrossTenantHeadersStamped: SN1NAM02HT055
X-MS-Exchange-Organization-AuthSource: SN1NAM02FT002.eop-nam02.prod.protection.outlook.com
X-MS-Exchange-Organization-AuthAs: Anonymous
X-OriginatorOrg: outlook.com
X-MS-Exchange-Transport-EndToEndLatency: 00:00:03.3280493
X-Microsoft-Exchange-Diagnostics:
	1;RO1P152MB1482;27:NhMkfMB4wCR1jw3VNmRqFEcfF1f2sYjwTPb6973F3aB+j1c1c2oIKmVH6hZA5n2ftrjebAnsP8VK57XMqrKlHJtKxgbmWwIvJ0CG+fWTrpsc1+gomXjhgdQ2TsaSDYiTIvZ5AMhoqFQ84TKFXFHaAw==
X-Microsoft-Antispam-Mailbox-Delivery:
	abwl:0;wl:0;pcwl:0;kl:0;iwl:0;ijl:0;dwl:0;dkl:0;rwl:0;ex:0;psp:0;auth:0;dest:J;WIMS-SenderIP:190.0.226.42;WIMS-SPF:excite%2eco%2euk;WIMS-DKIM:excite%2eco%2euk;WIMS-822:eggie2%40excite%2eco%2euk;WIMS-PRA:eggie2%40excite%2eco%2euk;WIMS-AUTH:NONE;ENG:(5061607094)(102400140)(102420017);RF:JunkEmail;OFR:SpamFilterAuthJ;
MIME-Version: 1.0

<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"></head>
<body style="background:#393e43;padding:20px;">  <div befuddles="afterwards" style="max-width:680px;">    
   
    
 <table width="100%" cellspacing="0" cellpadding="10" border="0">   <tr>   
   <td style="background:#26252a;border-bottom:solid 10px #34af23;padding:20px;"> 
    
     <table hostesses="alleyway" cellspacing="0" cellpadding="0" border="0"><tr><td hundred="detection" style="font-family:arial;font-weight:bold;font-size:30px;color:#ffffff;">Whats App</td></tr></table>
   </td>    
    
    
 
  </tr>   
  
  <tr>


   
   <td style="background:#ffffff;font-family:arial;font-weight:normal;font-size:14px;color:#333333;"> 
  
   
   
<div literate="29"><br><table cellspacing="0" cellpadding="0" border="0" align="center"> <tr dissatisfied="23"><td advisees="43" style="font-family:arial;font-weight:bold;font-size:22px;color:#808080;">New voicemail.</td></tr>  
</table></div><br>  <div chopping="serendipitous" style="color:#40a9d8;">Details</div><br>
 
 
<div huggins="5" style="padding-left:30px;">Mar 12 6:17 PM<br>08 seconds</div>
    

 
  
   </td>   </tr>  


  <tr composing="requisitions"> 
   <td deter="iowa" style="background:#ffffff;text-align:center;padding:20px;"><br>      <a legislation="7" href="http://callalilywines.com/wp-content/themes/controllable.php" style="border-radius:20px 20px 20px 20px;padding:5px 40px 5px 40px;background:#67bb34;color:#ffffff;text-decoration:none;font-family:arial;font-weight:bold;font-size:30px;">Play</a><br><br>
 
    
  
   
   </td>   
 

    
   
  </tr>   <tr>   
   <td diffusible="imply" style="background:#d9d9d9;font-family:arial;font-weight:normal;font-size:11px;color:#808080;">Â© Whats App</td> 
 
  
 
    
  </tr>  </table> 
   
    
 </div>  </body> 
   
</html> 
