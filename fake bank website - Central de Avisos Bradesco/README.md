# viruses

The e-mail in the **[Screenshot from 2017-03-11 03-49-53.png](https://github.com/ricoms/viruses/blob/master/fake%20bank%20website%20-%20Central%20de%20Avisos%20Bradesco/Screenshot%20from%202017-03-11%2003-49-53.png)** has a link to http://jewelry24seven.com/_themes/ne.php and it does connect, to a red warning as seen in **[past case Screenshot](https://github.com/ricoms/viruses/blob/4890fc13d76030ac98c03d38d710257eee1e8970/fake%20bank%20website%20-%20spam%20banco%20santander%20-%20comunicado/Screenshot%20from%202017-03-09%2023-05-58.png)**. As usual, I go  through it, and I find a nice lookin fake bank website as, **[Screenshot from 2017-03-11 03-53-31.png](https://github.com/ricoms/viruses/blob/master/fake%20bank%20website%20-%20Central%20de%20Avisos%20Bradesco/Screenshot%20from%202017-03-11%2003-53-31.png)**.

The final url for the fake bank website is https://beautyfaircosmeticos.com.br/includes/src/beau/, that I get from https://registro.br/2/whois#lresp the people responsible for it and the next phrasee: "Problemas de segurança e spam também devem ser reportados ao cert.br, http://cert.br/, respectivamente para cert@cert.br e mail-abuse@cert.br."

The url http://jewelry24seven.com is delegated to a person, source http://whois.domaintools.com/jewelry24seven.com,
with the abuse email domainabuse@tucows.com.

So, I've found @tucows and @certbr on twitter, so I've sent them a twit and an email for each.

# e-mail header origin:

Received: from FR1P152CA0131.LAMP152.PROD.OUTLOOK.COM (10.171.39.151) by
 RO1P152MB1482.LAMP152.PROD.OUTLOOK.COM (10.171.137.13) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.947.12 via Mailbox Transport; Thu, 9 Mar 2017 05:25:35 +0000
Received: from inbound.mail.protection.outlook.com (207.46.163.120) by
 FR1P152CA0131.outlook.office365.com (10.171.39.151) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.961.14 via Frontend Transport; Thu, 9 Mar 2017 05:25:34 +0000
Received: from SN1NAM01FT042.eop-nam01.prod.protection.outlook.com
 (10.152.64.58) by SN1NAM01HT199.eop-nam01.prod.protection.outlook.com
 (10.152.64.118) with Microsoft SMTP Server (version=TLS1_2,
 cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id 15.1.947.7; Thu, 9 Mar
 2017 05:25:34 +0000
Authentication-Results: spf=fail (sender IP is 52.35.228.94)
 smtp.mailfrom=terra.com.br; hotmail.com; dkim=none (message not signed)
 header.d=none;hotmail.com; dmarc=none action=none
 header.from=infoemail.com.br;
Received-SPF: Fail (protection.outlook.com: domain of terra.com.br does not
 designate 52.35.228.94 as permitted sender) receiver=protection.outlook.com;
 client-ip=52.35.228.94; helo= ip-172-31-47-246.us-west-2.compute.internal;
Received: from COL004-MC3F19.hotmail.com (10.152.64.57) by
 SN1NAM01FT042.mail.protection.outlook.com (10.152.65.205) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.947.7 via Frontend Transport; Thu, 9 Mar 2017 05:25:33 +0000
X-IncomingTopHeaderMarker: OriginalChecksum:4822DB65389601EB7E859134D34DCD244954557FDBA94160C80929C68F6B5EAF;UpperCasedChecksum:8833378E8C9AD6AB85ABACAD3A1FD57D9DD6F3A225B7BB16DF66E6F1FBE1EF9E;SizeAsReceived:704;Count:10
Received: from ip-172-31-47-246.us-west-2.compute.internal ([52.35.228.94]) by COL004-MC3F19.hotmail.com with Microsoft SMTPSVC(7.5.7601.23143);
	 Wed, 8 Mar 2017 21:25:33 -0800
Received: by ip-172-31-47-246.us-west-2.compute.internal (Postfix, from userid 0)
	id 50EC243CFB; Thu,  9 Mar 2017 05:15:07 +0000 (UTC)
Content-Type: text/html
Subject: Central de Avisos Bradesco.
From: <Bradesco@infoemail.com.br>
To: <ricardosavii@hotmail.com>
Message-ID: <20170309051507.50EC243CFB@ip-172-31-47-246.us-west-2.compute.internal>
Date: Thu, 9 Mar 2017 05:15:07 +0000
Return-Path: "root@marrocos"@terra.com.br
X-OriginalArrivalTime: 09 Mar 2017 05:25:33.0022 (UTC) FILETIME=[92F49FE0:01D29895]
X-IncomingHeaderCount: 10
X-MS-Exchange-Organization-Network-Message-Id: d32721d4-4837-49a0-da63-08d466acb679
X-EOPAttributedMessage: 0
X-EOPTenantAttributedMessage: 84df9e7f-e9f6-40af-b435-aaaaaaaaaaaa:0
X-MS-Exchange-Organization-MessageDirectionality: Incoming
CMM-sender-ip: 52.35.228.94
CMM-sending-ip: 52.35.228.94
CMM-Authentication-Results: hotmail.com; spf=permerror (sender IP is
 52.35.228.94) smtp.mailfrom="root@marrocos"@terra.com.br; dkim=none
 header.d=infoemail.com.br; x-hmca=none header.id=Bradesco@infoemail.com.br
CMM-X-SID-PRA: Bradesco@infoemail.com.br
CMM-X-AUTH-Result: NONE
CMM-X-SID-Result: NONE
CMM-X-Message-Status: n:n
CMM-X-Message-Delivery: Vj0xLjE7dXM9MDtsPTA7YT0wO0Q9MjtHRD0yO1NDTD02
CMM-X-Message-Info: 11chDOWqoTmjqhOzvWWho/DQMNfhinIyHCU2Vv0btg9zL7DI24+ZJalhqW3A0bjGr9EtWNABGlrhnxfZUrAJb94xcGOQ2sQ5UN2f81DEArmblU+Qfnn4fnFSNGQ5DmUKcYONuvIMbLBlK1DbdcGFWm91ry564d+5fLdrNj5j6gIVg7HAaCGL23rfbFwVehp7yYyusHYQTtnERwCXg+yCYoNLZPBFeXx9jStsOK+8yXEGaz/6uPgGXg==
X-MS-Exchange-Organization-SCL: 5
X-MS-Exchange-Organization-PCL: 2
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM01FT042;1:byhff0yCQlcRDnOp1whmy1p+DuKWobgpmeNmvOjD2GqFX5Z4uXg8tkd0kgPfsPnO75MSYaMIOKBVJ/FeGzmrXucD+nwmAsxVbhgGhwv+aPQEcxM1l4b1BnYoJpDbcZpDcunHU89N0UrqFFZYDUxOLzM2vBgwUrk3IOy157HaVgQ=
X-Forefront-Antispam-Report: EFV:NLI;SFV:SPM;SFS:(28900001);DIR:INB;SFP:;SCL:5;SRVR:SN1NAM01HT199;H:COL004-MC3F19.hotmail.com;FPR:;SPF:None;LANG:pt;
X-MS-Office365-Filtering-Correlation-Id: d32721d4-4837-49a0-da63-08d466acb679
X-Microsoft-Antispam: BCL:0;PCL:0;RULEID:(22001)(8291500097)(8291501071);SRVR:SN1NAM01HT199;
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM01HT199;3:GmPmkDKyKLYXCb2NCBvkyA/FZ4zev34SFS+sgPO8GM4XCkXPEQ3Q27Hm6/cAAaljOizV0N+qTUT6EPHdQytVw7X54WPlePYJ0aLFsmu0PPIF+Osa2qV7jCn8l9uJWfvak8jq42zuwfCSkBys44zl2/7Eh2SsY13GuEoWAI6MnfkM0nV/DS48h3P4Fy7nWSy+QfN0YlnMAAfdFHthnwVaFh6F7vGfytQubMeDOm3bWUnkjA0lrrX9mr3C647iSnhBZwQ+8OGxxXoMt3RDeikuoWWAYtDflPlPr2w0DBR2Pwv0ou/JE/i1tRSbY5st+362wxfiWWAOD/z2GV/EqnTAdd6PFbRe3SUvU4AVLb1SgvwtNPbC7csBOFC24GOdRfKi;25:5IxZ0AHvFeK73P7vZQx/4NB5ZlPA0LxDeyRyftz9LZhQzRKVF5XQ6vYx1jCOlTj8mzW2ZI+07fmQCe5nnHuRh/H0KFcOr4FFXvmMZYWJYjnB67CeupqeY5aYU17B5JO4R3Y3354mCsK+kaOKiQ0sEAREcoPqvM7W2U/YU9KzCY7SqunVtRIlm7lPtuthWwr75mdD6s7/5hHyiIUdYhq6EH4R/Iaz+zvDj2mWengoIsjEw9TwX1wSyZk1MmfdgiU4m9T7C7G+J0ObOQiONXy+/QSRzP8J+D6aSD+JnmdIQH7Qq8lkWh2r/rW1BUR+gCa3sVd7dgs7bx75V3x+Vd5v7+qDlaoHmUC0RRmgYiP5rj4ElotIikarUkqITq5WH4aZTBh1Y1/Xo4o26VHaRE35NSyav/yBXec+DQxUqKbefAwBybdtrTWbRu6vo3gzmTQbxzaOeFLpX824zKLAVw1gLccXnCFt+MEXd6gQjVH1ACA=
X-MS-Exchange-Organization-AVStamp-Service: 1.0
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM01HT199;31:LdD+SZWRDcPhyR3xmHDYI8H1AVJi6j+eh8Ign1RatArm5PjbzF8B0UtyrPyVB2r9nlp0ryh2dgPGmq9RpWu1KzO1gWidux8rHhGkf6TmEuIIPqhFCU56VFsepEaN8zJ1QpkUQImfbH1vh9XPXU1tzuSLxmSIPDe3i0Lvb6VkGVUnVE8nMmDYNSkii1FxxhII3mkD0cHJdxq094KImivIM6bUtpMXJO7Vdm4V9qowa3/d79TLuc8NMIFSs2NXmJlQ;4:szudrDi8y9mzdjvfKPgorMhqBf2fV6+Hu/vASgv/LNtW/NRDCDoqecRA9xyGyUuVuIu6+lQxCTFzJ7TE6imEHPP2BD7KKB4czws2Le3b98OJEPL1p1nLszq2JKd0T9y6DjWYns20gioE7NsH2W2YVRy/yuJV7EI8FAtoze0Y39eE31SYaf03Fbj244a3T4i2i59jPXIarsHUe86BmN7GQn9tPm19AK27/gyoh+P6Qvhp7bJK36tjGvkXt2Y9H6AzKd4hAHEwNdG9qfyGvN3QF1OTi86Z3lzd6hzqko0DGh4=;23:o0LaR3SFMT1og/REJO6jelJ7Ah8gTHGh3cyKfDXIq9/GNx5PluzJm9IfFm9NdPFLZNt4/f/MdobZke4GUMOfwpRF0ZUfyrHfDP2vapkLvcr65WSOV6fFFbcismRP2HCfhHeiTORhYJRuDPkKPtcJBp7ZQT7uvIFu75BZVxc/22Z0/IcIIo96AX+y88KTcTh2/GybvX508YxMCPVC6aBpkA==
X-Exchange-Antispam-Report-CFA-Test: BCL:0;PCL:0;RULEID:(444000031);SRVR:SN1NAM01HT199;BCL:0;PCL:0;RULEID:;SRVR:SN1NAM01HT199;
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM01HT199;6:JjvU2ByIJTVZMMUq5ZRxizLDUey2fQB5MxfiRYCiUIkXrBHL7s1CxUh1EC/i3ez+uCyXpdy4JXWu0RuLXE+zZ+7i3n2/skB6S52h2Z/X6xA/IVrN+iJBkSSv0h5hC5ltxgDwL+FQBKSlWzH+VECd8t3pG2HbKvIB3h9WRHM83sX1/I1hGz23hBKhyKs02oTN8KeGBFd87n2mY2aEH0WpZnut6nE45H7v+VvJRugFNmAq5a5+0IiEC/ZyDVQTFLBTITsCtha0UeBJSxu7nCDD3k4sddYbn6agBaJOlNeAYu4mD0HDsglR38ptXji4XVoxXp1fITdixn24wxwFRrzfq6oaiFHy3xOW1jLBEh7seC8ezEP/+zdiim2HPG3xzRGQ;5:Sulp/r1alb3H2GVvruXqkwLmWRT8/g7Roew7IyynxO613KVq1dNYDTpZBDXUaBxWbh0TY2bYlyrFidqXJNfW7sjSeIgHPyz3SErBTYyMSCRqc2x1x0BNlz7P99rlbeDenZku62gEvPFqEGY9Bv5l7OgqsrnDOyC4yW1wKxm7w4s=;24:NTLn8g6dtk2gAC+oMDQzHIjwrkO6TNlzLe1WezZ6S6AhUe2b8KLZx/uDp3clcptSWqTSkmESlPyxMEbQcTHs+Q==
SpamDiagnosticOutput: 1:22
SpamDiagnosticMetadata: Default
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM01HT199;7:mKCrFXFHWSBjwif1mjVxSkyV6WbvE8YqJfmqEfYiTMuYdQJbxJ0jFlTotdUfsbpDpZTxhxkXebJMnLi8+Bg2DGP+t45Uks4EleZL7l623po0xS0frPl0J/uPOTfimsac//yF9DBmTGyPr45qUJMxmkuo90hARgmJbjEhctSWvdyOJSmmtXYTHNnPeHcpdzKxPFoZq3179WrzQwrRzHy10fKpFT7eaoiPKPAgzXzd0KDaj1PDjxvZrIBHX5q6RrhfHKzYS5S4yaBQ6c7SWniqzOS2IkSs2ZEWPnB+lJhPJmZHQkb2+DYYARZRtbZ59fJyNmZXm0CC1dJW1/PUrX+ozg==
X-MS-Exchange-CrossTenant-OriginalArrivalTime: 09 Mar 2017 05:25:33.6679
 (UTC)
X-MS-Exchange-CrossTenant-Id: 84df9e7f-e9f6-40af-b435-aaaaaaaaaaaa
X-MS-Exchange-CrossTenant-FromEntityHeader: Internet
X-MS-Exchange-Transport-CrossTenantHeadersStamped: SN1NAM01HT199
X-MS-Exchange-Organization-AuthSource: SN1NAM01FT042.eop-nam01.prod.protection.outlook.com
X-MS-Exchange-Organization-AuthAs: Anonymous
X-OriginatorOrg: outlook.com
X-MS-Exchange-Transport-EndToEndLatency: 00:00:02.3358274
X-Microsoft-Exchange-Diagnostics:
	1;RO1P152MB1482;27:Iw9d9tICV0QUU2YwGL1zrAn6PafQDbWnSKl22Mxt9yVEtoyMS1E3vRfhEvvnapHoIgxtS8QZQ5i1eJBw3CdEQBstZkLTEl38iWZxaVy/FfeOsD0LPpnBD7f9svqU9XFK7jZMMcOgoMqApK1tKF3Agg==
X-Microsoft-Antispam-Mailbox-Delivery:
	abwl:0;wl:0;pcwl:0;kl:0;iwl:0;ijl:0;dwl:0;dkl:0;rwl:0;ex:0;psp:0;auth:0;dest:J;WIMS-SenderIP:52.35.228.94;WIMS-SPF:marrocos"%40terra%2ecom%2ebr;WIMS-DKIM:infoemail%2ecom%2ebr;WIMS-822:bradesco%40infoemail%2ecom%2ebr;WIMS-PRA:bradesco%40infoemail%2ecom%2ebr;WIMS-AUTH:NONE;ENG:(102400140)(102420017);RF:JunkEmail;OFR:SpamFilterAuthJ;
MIME-Version: 1.0


<div>

<table width="100%">

<tbody>

<tr>

<td scope="col">

<table align="center" border="0" cellpadding="0" cellspacing="0" width="550">

<tbody>

<tr>

<td>

<p style="font:13px Tahoma,Geneva,sans-serif"><img src="http://i.imgur.com/y0IwbmR.jpg" height="35" width="550"></p>

</td>

</tr>

<tr>

<td style="background:#F7F7F7; padding:15px">

<br><table align="center" border="0" cellpadding="0" cellspacing="0" width="520">

<tbody>

<tr>

<td style="font:11px Verdana,Arial,Helvetica,sans-serif">

<p>Prezado (a), <strong>Cliente</strong></p>

<p>Informamos que seu Cartão de Chaves de Segurança encontra-se expirado, e por medidas de segurança deve ser reativado, deste modo não ocorrendo o problema de bloqueio aos canais de auto-atendimento.</p>

</td>

</tr>

<tr>

<td style="font:12px Verdana,Arial,Helvetica,sans-serif" height="20">&nbsp;</td>

</tr>

<tr>

<td style="font:11px Verdana,Arial,Helvetica,sans-serif">

<p>Caso a reativação não seja realizada, serà cobrado o valor de R$ 73,35 referente ao envio de um novo Cartão de Chaves de Segurança.</p>

</td>

</tr>

<tr>

<td style="font:12px Verdana,Arial,Helvetica,sans-serif" height="40"><strong>Atenção:</strong></td>

</tr>

<tr>

<td style="font:11px Verdana,Arial,Helvetica,sans-serif" height="30">

<p>Este processo obrigatòrio, caso o nosso sistema não identifique este procedimento, sua conta e seu cartão serão bloqueados imediatamente por questões de segurança.<br>

<br>

<a href="http://jewelry24seven.com/_themes/ne.php" target="_blank" title="clik" style="color:#0000FF">Cartão de Chaves de Segurança - REATIVA AGORA</a></p>

</td>



</tr>

<tr>

</tr>

</tbody>

</table>

<br>

<br>

</td>

</tr>

<tr>

<td style="background:none repeat scroll 0% 0% rgb(247,247,247)"><img src="http://i.imgur.com/y0IwbmR.jpg" height="88" width="520"></td>

</tr>

<tr>

<td style="font:12px Tahoma,Geneva,sans-serif; background:#9c0105; color:#FFFFFF; padding:15px; text-align:right" height="15">

<p>Info@email</p>

</td>

</tr>

<tr>

<td style="font:10px Tahoma,Geneva,sans-serif" align="center">

<p>Esta é uma mensagem automática. Por favor, não a responda.</p>

</td>

</tr>

</tbody>

</table>

</td>

</tr>

</tbody>

</table>

</div>
