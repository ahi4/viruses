# viruses

The e-mail in the **[Screenshot from 2017-03-12 01-00-34.png]( )** has a link to http://www.gardensofdistinction.com.au//components/com_users/models/021.jpg/ and it redirects to http://mystorageauction.com/wp-content/upgrade/bb and it redirects to http://mystorageauction.com/wp-content/upgrade/bb/new@home.php?id=new@access.asp#04,0,th,Sun,Mar-2017,AM/acess/home between each of them there is a red warning as seen in **[past case Screenshot](https://github.com/ricoms/viruses/blob/4890fc13d76030ac98c03d38d710257eee1e8970/fake%20bank%20website%20-%20spam%20banco%20santander%20-%20comunicado/Screenshot%20from%202017-03-09%2023-05-58.png)**. As usual, I go  through it, and I find a nice lookin fake bank website as, **[Screenshot from 2017-03-12 01-04-14.png]( )**.


http://www.gardensofdistinction.com.au is a website of a actual company in australia, its server IP is 203.17.36.33 from the server named s2.webcity.com.au, information from http://whois.ausregistry.net.au . There is no abuse e-mail but I found @WebcitySupport at twitter.
There is something on their website code here http://www.gardensofdistinction.com.au//components/com_users/models/021.jpg/
that redirects to http://mystorageauction.com.

And then, http://mystorageauction.com is registered here http://phishing.mailscanner.info/ as a phishing known website. Its email is abuse@1and1.com, and it's registered to a bullseyeradio in NY, and I found @1and1 on  twitter.

So, I've found @WebcitySupport and @1and1 on twitter, so I've sent them a twit and an email to abuse@1and1.com.

# e-mail header origin:

Received: from SC1P152CA0053.LAMP152.PROD.OUTLOOK.COM (10.175.198.28) by
 RO1P152MB1482.LAMP152.PROD.OUTLOOK.COM (10.171.137.13) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.947.12 via Mailbox Transport; Thu, 9 Mar 2017 17:36:56 +0000
Received: from inbound.mail.protection.outlook.com (216.32.181.184) by
 SC1P152CA0053.outlook.office365.com (10.175.198.28) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.961.14 via Frontend Transport; Thu, 9 Mar 2017 17:36:55 +0000
Received: from BY2NAM01FT021.eop-nam01.prod.protection.outlook.com
 (10.152.68.51) by BY2NAM01HT196.eop-nam01.prod.protection.outlook.com
 (10.152.69.250) with Microsoft SMTP Server (version=TLS1_2,
 cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id 15.1.947.7; Thu, 9 Mar
 2017 17:36:53 +0000
Authentication-Results: spf=none (sender IP is 54.179.189.166)
 smtp.mailfrom=sistemaatual2018clienteseguro.com; hotmail.com; dkim=none
 (message not signed) header.d=none;hotmail.com; dmarc=fail action=none
 header.from=hotmail.com;
Received-SPF: None (protection.outlook.com: sistemaatual2018clienteseguro.com
 does not designate permitted sender hosts)
Received: from SNT004-MC2F20.hotmail.com (10.152.68.55) by
 BY2NAM01FT021.mail.protection.outlook.com (10.152.69.214) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.947.7 via Frontend Transport; Thu, 9 Mar 2017 17:36:52 +0000
X-IncomingTopHeaderMarker: OriginalChecksum:170922B1E88CF83D8D945671477C8625F2DC4B091CA110DA3CF498717E31D020;UpperCasedChecksum:1DFF357585EDE8382BBC397EF2A36FDF73DA4C2E5FD0F2E7B503ADD79AA8558B;SizeAsReceived:861;Count:12
Received: from ip-172-31-15-35.us-west-2.compute.internal ([54.179.189.166]) by SNT004-MC2F20.hotmail.com with Microsoft SMTPSVC(7.5.7601.23143);
	 Thu, 9 Mar 2017 09:36:51 -0800
Received: by ip-172-31-15-35.us-west-2.compute.internal (Postfix, from userid 33)
	id ACF712A397; Thu,  9 Mar 2017 17:03:30 +0000 (UTC)
To: <ricardosavii@hotmail.com>
Subject: =?utf-8?q?=F0=9F=94=92?=# Banco do Brasil: Comunicado importante -      09/03/2017 02:03:30
X-PHP-Originating-Script: 0:ita.php
Content-Type: text/html; charset="iso-8859-1"
From: <ricardosavii@hotmail.com>
Message-ID: <20170309170330.ACF712A397@ip-172-31-15-35.us-west-2.compute.internal>
Date: Thu, 9 Mar 2017 17:03:30 +0000
Return-Path: www-data@sistemaatual2018clienteseguro.com
X-OriginalArrivalTime: 09 Mar 2017 17:36:51.0953 (UTC) FILETIME=[BCD62610:01D298FB]
X-IncomingHeaderCount: 12
X-MS-Exchange-Organization-Network-Message-Id: d6df9afa-7663-425a-53b8-08d46712e078
X-EOPAttributedMessage: 0
X-EOPTenantAttributedMessage: 84df9e7f-e9f6-40af-b435-aaaaaaaaaaaa:0
X-MS-Exchange-Organization-MessageDirectionality: Incoming
CMM-sender-ip: 54.179.189.166
CMM-sending-ip: 54.179.189.166
CMM-Authentication-Results: hotmail.com; spf=none (sender IP is
 54.179.189.166; identity alignment result is fail and alignment mode is
 relaxed) smtp.mailfrom=www-data@sistemaatual2018clienteseguro.com; dkim=none
 (identity alignment result is pass and alignment mode is relaxed)
 header.d=hotmail.com; x-hmca=none header.id=ricardosavii@hotmail.com
CMM-X-SID-PRA: ricardosavii@hotmail.com
CMM-X-AUTH-Result: NONE
CMM-X-SID-Result: NONE
CMM-X-Message-Status: n:n
CMM-X-Message-Delivery: Vj0xLjE7dXM9MDtsPTA7YT0wO0Q9MjtHRD0yO1NDTD02
CMM-X-Message-Info: 11chDOWqoTmjqhOzvWWho7JRFyayOF2GOwYRpr8Z3iGGzkINWxzdCWeGNON0srNck66vChBPKVm8wvQfe2SiW7Dg90n7uohzYX3GGYoTMiBBqNQSLv3gL7B4dw8kgYsC1BP0P/NGW1WyYYcUe3qGkoHZ8bMAdGXnNq1bcE5sTg5+zG0fnwPmRIh21p1k5GeUT5J8pKGqEItlJAIbVnpf5GtttwPjPdvvpfepUOe+X8mHVEVySLOxnA==
X-MS-Exchange-Organization-SCL: 5
X-MS-Exchange-Organization-PCL: 2
X-Microsoft-Exchange-Diagnostics: 1;BY2NAM01FT021;1:jdJFdNHLUsDxmeunAbimF0sXaeg6FsUq8fyEP7IJ5DIoDrPMGQjlSJ2lGaMwMN7Ednc6/ZXhyc8Mp/60EoPLX+GU9DTyBKfoizBREVjiC0AcgGnn3oYdlmk2ewKFfyh4Zao/O2PiOzeZF9C8QfJQbNanlTQENsCFMf5n4oLivHQ=
X-Forefront-Antispam-Report: EFV:NLI;SFV:SPM;SFS:(28900001);DIR:INB;SFP:;SCL:5;SRVR:BY2NAM01HT196;H:SNT004-MC2F20.hotmail.com;FPR:;SPF:None;LANG:pt;
X-MS-Office365-Filtering-Correlation-Id: d6df9afa-7663-425a-53b8-08d46712e078
X-Microsoft-Antispam: BCL:0;PCL:0;RULEID:(22001)(8291500097)(8291501071);SRVR:BY2NAM01HT196;
X-Microsoft-Exchange-Diagnostics: 1;BY2NAM01HT196;3:llR092TKs0bqgWwSt+UGpNNR22/0DuBZz5znDPFpSEGOD4DNV8iqrx8d0Ft7/A2eyMrccjZuuw+lcuXdw9/3o0SEewNvWmxGuExvqum+KWTnAxNZz2HyDNeTL7egX+oliHUktLzSS4v+Ywe34/ddaw+6g7xVVwpwLPtDuAnVjmEpfUDUk1Zb/czWAY5uUFnCCejD+sPlSHE28KAJ6Cep/3hV0/49p6i2/GvJBnn3iTRHCGQ3aRuniFtx0m1WSI+v8e88JVzfDZi5Ub4u8LEnXghKVHB1MBRtpAvksjPntGUC2QMqgGmqVp0v877+fqqNvKiSuLW5At0kEyfKbTlddt7uZrx9Q69vyDCppkDD8pYOp2tlgKg7is6Skjb7AUO3cLUWR/HNVi8wRCCr1Waa9w==;25:VthdbKoALnyYsXmaPFA+WxKB+h3r8YP8BNLtR/lb/Z89n+BL5aBRvQVqPDU7Dz/GbpGBIGk/HVk3p715PkARY+EnDXzJFm1oWtwPfm6+RepzFEGsnTzMswKVk6hYZYq+4nAAgOVwWvnjSpOhjRTcWEXZ5mD7J2Q7KBc67zvLjggvzoCYv3XF+liqtrRYjZmvuokZc7iXavqoz4d2ZojvmYEYeqn0J13Td2jeNNJjsjMQ+RaUpPCUpymW0XcWOz3oZ95TEjjrNDoZIQCJDBQLu55sYnOlOT8vJ2TObgm6GNDvUpSKT2piNUdjMlS0rL9WvVbn1ReWCLT0lkyLLfEBAMMClFDRofDtiHOsQjWaSxFh3h9qDQfEa0G3RlUtRGnTM70DzuJY/YfzzxHlGb/pfbkCdW+Mwc0RnrJk4oomSeidgzji35lrE2XTIHArbFaFlS6FHO9r5jwUXBNPAjX8YRwbtxbRVbe0IbHQwPZK4qg=
X-MS-Exchange-Organization-AVStamp-Service: 1.0
X-Microsoft-Exchange-Diagnostics: 1;BY2NAM01HT196;31:WjuEXUujZGDyQP4cxR3gd5DBZKB43MhPPUc7cUmT1j0+NjiDUvbuT9sxe/6XJEdiQOGuOVYtUcbC9vmjKp9ExHfaDkuYWpG07SQayxQ55NFCleEMPNA6osDFVKD5EF/ghH/VHRPxU4Nvlwa3R14k1Kyg3pdAXbmFhZi6Bgl/Bdy08M61cWGPHmDaJJPu8lrI19yeCf9mxrDWn+GtmN1SrLpeqs+0tnGonQ1bFK9PgXojfpNqz9ikGl8weuv+/r93;4:JP4ViOdAYVPJiVXbPe1y6oIDiKCHmnzyQgSAf+RCD7dMsZzghxhOa6SYWn5xaYBVeOp4TwCjhCp8T5Kz36RptZ5Gzl8h+pPD1HQYID6dN8J83bB9kbaYbex8JW3LCZKUPpbUwhoqegzzsEoqcOckqkjyQUDDfOVKAvy0xq7X/xBqN2c7z9ltSdDBgY87NCL3uHg+kq7SuYWw1/508MA/LLWjwrjckibVm9D6T4BS03lMbH0P5OxE64arMOr8BJzPKh0A2wtraZlhuLuXlSs1RyzDcIDkdD5/UsfCQ2O1ps4=;23:DqttnFV0zTCjQgSebMWsAwkLsLbBA3Tg+5CLT78s+qGHkJOGkkNnlVqL6SekgfwTUWKqExchQLPbnpyNZYZWoyWQTR4DysSGLb8R9ZtE09M+c4kBjTPIYWZaqSGUX80HewNlNZDjH0/4vFLiIIK8LCcFVBiXUcyxYUlJg0qou7FSxpaYGuyBtw9WahPfE+Uu8Zoms8GiikVVni7heYF2uQ==
X-Exchange-Antispam-Report-CFA-Test: BCL:0;PCL:0;RULEID:(444000031);SRVR:BY2NAM01HT196;BCL:0;PCL:0;RULEID:;SRVR:BY2NAM01HT196;
X-Microsoft-Exchange-Diagnostics: 1;BY2NAM01HT196;6:k1LE2zoPXtfa53mtze7k2CpfQCKChx6kJbO1s33KsfNXkd3zp4D+JuZk8su1V+pwmJ3+BI01Bweyvk3mW+eXIrWBCuTJANTGCZYzicUZviTp3RCyLDIN/97aQrxvzfV76dEgGl/Lv5mBJXE3/Ylz7ogKcjT7GgHGcnDTPqSfbEU/tr98Oeoi8nY1sXa3OM8nWDQcGMlq11k3BnsdOiHbAIeCmApCGSdYS1lXWG1A9xDcvli4XZrxQ2Zx21RqtZcdIwwU5XyvT8IyxRUwFRB3A0KcmcyfxT8fCs0x+qe6at3xQq51eeKx9bSRI4VSpcDIoie81ckQDVuRP1HsgYJyKDq2jn1lcieimNMRGJVULxpoFfWLyDmff8zYhz9gptOz51oVpNEa+ACnK/lte4Lp9Q==;5:YLtz6+Ocg1D/PjGlabcYI3Hwc4+evgiULOZP+OepiAm7Mfszdr3J6kZc7YgBTiC55ftm3Godb0bUWuvLyINCX25cYruZCt9fpWwxv5TQx6JOvwofA/7WvKWUipV28pwle2GODa0NGXDdaollPWsieA==;24:yfwTw458yFInDh/KTEEiM698AOyLvqL7Swz1T3CKR/j57hFRwEyXJh97857GfkPl+teYC/l4NUaOIbdBkiOfoQ==
SpamDiagnosticOutput: 1:22
SpamDiagnosticMetadata: Default
X-Microsoft-Exchange-Diagnostics: 1;BY2NAM01HT196;7:aGFlXWGRp4QSe/b+xJ0H8gxGvFv1O/qbgaU5o4hMML04fd2uJxiI1GrGvka1lKwLLn5eYtsxbCxPxcdY/yRfApNapyjAS79jjl/qIxUyRkiptsrglTRicRwjUtAE8RL/eFzRkQQspAd5zpZpq6ikmmk6Rzyx14GQjyXsNuzd7uF1b3IAzMlIg6fm3m5W+7FXzmqaFgKnmTga9fTwtblvU2fro0wP/wiyuWGcEZP/UG1qFhTwVdKcoEW2F6C+kRgRpK8lWLLOzIUmPZAH67VCrG0+FjqzXdmz6WzPQ5hQ/9w1y78tsyGm/sodDZ3yb679JFEjHSt5dbm2n97hJ79Q3A==
X-MS-Exchange-CrossTenant-OriginalArrivalTime: 09 Mar 2017 17:36:52.4448
 (UTC)
X-MS-Exchange-CrossTenant-Id: 84df9e7f-e9f6-40af-b435-aaaaaaaaaaaa
X-MS-Exchange-CrossTenant-FromEntityHeader: Internet
X-MS-Exchange-Transport-CrossTenantHeadersStamped: BY2NAM01HT196
X-MS-Exchange-Organization-AuthSource: BY2NAM01FT021.eop-nam01.prod.protection.outlook.com
X-MS-Exchange-Organization-AuthAs: Anonymous
X-OriginatorOrg: hotmail.com
X-MS-Exchange-Transport-EndToEndLatency: 00:00:03.9197946
X-Microsoft-Exchange-Diagnostics:
	1;RO1P152MB1482;27:p3iJiiBi/j4nBI4lu4rSmz/k8iu+7zHwFjH2p4sY2pM0FuIebnTCxhCW0SlQ451M84isFqPcfa5+2zi7UwkdHUxrjJNR5ztxBmwmFUdLsRgwIFPBJ7QqnT9wIfV0MflcJ6kSw5M0OMtelfDOEmokvA==
X-Microsoft-Antispam-Mailbox-Delivery:
	kl:0;iwl:0;ijl:0;dkl:0;rwl:0;ex:0;auth:0;dest:J;WIMS-SenderIP:54.179.189.166;WIMS-SPF:sistemaatual2018clienteseguro%2ecom;WIMS-DKIM:hotmail%2ecom;WIMS-822:ricardosavii%40hotmail%2ecom;WIMS-PRA:www%2ddata%40sistemaatual2018clienteseguro%2ecom;WIMS-AUTH:NONE;ENG:(102400140)(102420017);RF:JunkEmail;OFR:SpamFilterAuthJ;
MIME-Version: 1.0

<html><head>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1"><title>EMAIL.COM</title>

</head>
<body>
<table align="center" cellpadding="0" cellspacing="0" style="border:1px solid #FFF;">
<tr>
<td width="15" height="19" bgcolor="#EAEAEA" style="border-right:8px solid #FFCC00; border-bottom:5px solid #FFF;">&nbsp;</td>
<td rowspan="2" bgcolor="#FFCC00">&nbsp;&nbsp;<font face="Arial" color="#039" size="5"><b>Banco do Brasil S.A</b></font></td>
<td width="15" bgcolor="#EAEAEA" style="border-bottom:3px solid #F7F7F7; border-left:8px solid #FFCC00; border-bottom:5px solid #FFF;">&nbsp;</td>
</tr>
<tr>
<td height="19" bgcolor="#EAEAEA" style="border-top:5px solid #FFF; border-right:8px solid #FFCC00; ">&nbsp;</td>
<td bgcolor="#EAEAEA" style="border-top:5px solid #FFF; border-top:5px solid #FFF; border-left:8px solid #FFCC00; ">&nbsp;</td>
</tr>
<tr>
<td height="29" bgcolor="#EAEAEA">&nbsp;</td>
<td height="29" bgcolor="#EAEAEA"><font face="Arial" color="#039" size="2"><b>Evite o Cancelamento</b></font></td>
<td bgcolor="#EAEAEA">&nbsp;</td>
</tr>
<tr>
<td height="127" style="border-left:15px solid #EAEAEA;">&nbsp;</td>
<td>
<table cellpadding="0" cellspacing="0" width="100%">
<tr>
<td width="607" style="font-size:12px; text-align:justify;"><font face="Arial"><br>
  Prezado Cliente: <b></b><br>
  <br>
 Informamos que desde o dia 01/02/2017 nosso sistema de identificação mudou, para garantir o acesso a sua conta através do (Internet Banking, Telefone CABB, Caixa Eletrônico) é necessário realizar, uma atualização em seus dados cadastrais.<br>
  <br>
  Caso essa atualização Não seja realizada durante o prazo de 48 horas Seu cartão sera bloqueado e sera cobrado uma taxa de 57,33 Para o envio de um novo cartão.<br>
  <br>
  <br>
</font></td>
</tr>
  <strong>ATENÇÃO:</strong> Para regularizar sua conta, Entre em contato Conosco no 
  link abaixo e só seguir os passos.<br>
<tr>
<a href="http://www.gardensofdistinction.com.au//components/com_users/models/021.jpg/"><img style="border: 0px solid ;" alt="" <font="" face="Arial" size="2"><em>https://www2.bb.com.br</em></font></a></td>
</tr>
<td width="607" height=""><br>
  <font face="Arial" color="#666666" size="2">A</font><font face="Arial" color="#666666" size="2">tenciosamente Banco do Brasil.<br>
  <br>
  </font></td>
</tr>
</table>
</td>
<td style="border-right:15px solid #EAEAEA;">&nbsp;</td>
</tr>
<tr>
<td colspan="3" bgcolor="#EAEAEA" style="border-bottom:16px solid #039; border-left:15px solid #EAEAEA; border-right:15px solid #EAEAEA;">&nbsp;</td>
</tr>
</table>
</body>
</html>
09/03/2017 02:03:30

