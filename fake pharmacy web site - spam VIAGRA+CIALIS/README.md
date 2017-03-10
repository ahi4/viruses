# viruses

The e-mail in the **[Screenshot from 2017-03-08 00-00-28.png](https://github.com/ricoms/viruses/blob/master/fake%20pharmacy%20web%20site%20-%20spam%20VIAGRA%2BCIALIS/Screenshot%20from%202017-03-08%2000-00-28.png)** has the link: http://afpke.realtopaweb.su/ as the address to get some legal drugs.

.su (from wikipedia) was assigned as the country code top-level domain (ccTLD) for the Soviet Union (USSR) on 19 September 1990. And by the guardian (https://www.theguardian.com/technology/2013/may/31/ussr-cybercriminals-su-domain-space) it's considered a cybercriminal haven.

The link sends us to a cool website as seen in **[Screenshot from 2017-03-08 00-05-26.png](https://github.com/ricoms/viruses/blob/master/fake%20pharmacy%20web%20site%20-%20spam%20VIAGRA%2BCIALIS/Screenshot%20from%202017-03-08%2000-05-26.png)**, even, it's in PORTUGUESE! mixed with spanish... but ok, good try.

That is probably a scam website, my drugs will never arrive. :'(

From the email source seen below I saw that sender IP is 51.140.104.67. From  https://www.robtex.com/?ip=151.255.3.1&whois=1 I've got the abuse@saudi.net.sa email. I sent them the email source, but later I received an email saying "Quota exceeded (mailbox for user is full)" as seen in **[Screenshot from 2017-03-08 00-34-55.png](https://github.com/ricoms/viruses/blob/master/fake%20pharmacy%20web%20site%20-%20spam%20VIAGRA%2BCIALIS/Screenshot%20from%202017-03-08%2000-34-55.png)**

Then, pinging the url afpke.realtopaweb.s I've got the IP 5.178.71.206, accessing that IP I got a blank website as just with the phrase seen in **[Screenshot from 2017-03-08 00-10-58.png](https://github.com/ricoms/viruses/blob/master/fake%20pharmacy%20web%20site%20-%20spam%20VIAGRA%2BCIALIS/Screenshot%20from%202017-03-08%2000-10-58.png)** ("Welcome to nginx!"). And a whois 5.178.71.206 got me to City of Dronten at Amsterdan where it recognized its Autonomous System Number (ASN) as 50673 - SERVERIUS-AS.

Looking for serverius I find the website: https://my.serverius.net/knowledgebase.php?action=displayarticle&id=29 that has this email contact: abuse@serverius.net

This last url also mentioned "(email address at the **ripe** database)". I didn't find serverius on twitter, so I just sent them an email.

# email header origin:

Received: from RO1P152CA0125.LAMP152.PROD.OUTLOOK.COM (10.171.131.28) by
 RO1P152MB1482.LAMP152.PROD.OUTLOOK.COM (10.171.137.13) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.947.12 via Mailbox Transport; Tue, 7 Mar 2017 23:21:53 +0000
Received: from inbound.mail.protection.outlook.com (216.32.180.16) by
 RO1P152CA0125.outlook.office365.com (10.171.131.28) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.961.14 via Frontend Transport; Tue, 7 Mar 2017 23:21:53 +0000
Received: from SN1NAM02FT064.eop-nam02.prod.protection.outlook.com
 (10.152.72.60) by SN1NAM02HT063.eop-nam02.prod.protection.outlook.com
 (10.152.72.203) with Microsoft SMTP Server (version=TLS1_2,
 cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id 15.1.947.7; Tue, 7 Mar
 2017 23:21:52 +0000
Authentication-Results: spf=softfail (sender IP is 51.140.104.67)
 smtp.mailfrom=live.com; hotmail.com; dkim=none (message not signed)
 header.d=none;hotmail.com; dmarc=fail action=none header.from=hotmail.com;
Received-SPF: SoftFail (protection.outlook.com: domain of transitioning
 live.com discourages use of 51.140.104.67 as permitted sender)
Received: from SNT004-MC7F17.hotmail.com (10.152.72.54) by
 SN1NAM02FT064.mail.protection.outlook.com (10.152.72.143) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.947.7 via Frontend Transport; Tue, 7 Mar 2017 23:21:51 +0000
X-IncomingTopHeaderMarker: OriginalChecksum:6FF0FDEF370615AB9C141AA95FBD835F6039F1FEB212AD8499D7692A0A80819F;UpperCasedChecksum:2EA0CFA3025153F165D752C6E114056CF4051EB3B12BCCDD9AB2BFA0C9A7AE6D;SizeAsReceived:846;Count:12
Received: from tsacmail.tsacmail.z2.internal.cloudapp.net ([51.140.104.67]) by SNT004-MC7F17.hotmail.com with Microsoft SMTPSVC(7.5.7601.23143);
	 Tue, 7 Mar 2017 15:21:50 -0800
Received: by tsacmail.tsacmail.z2.internal.cloudapp.net (Postfix, from userid 33)
	id 53BB2213B7; Tue,  7 Mar 2017 23:21:49 +0000 (UTC)
To: <ricardosavii@hotmail.com>
Subject: Santander - Smiles Gol - Você possui 120.000 mil pontos a expirar ! - [ 599434373900  ]
X-PHP-Originating-Script: 0:nilshwuqfpygnimotq.php
Content-Type: text/html; charset="iso-8859-1"
From: <ricardosavii@hotmail.com>
Message-ID: <20170307232149.53BB2213B7@tsacmail.tsacmail.z2.internal.cloudapp.net>
Date: Tue, 7 Mar 2017 23:21:49 +0000
Return-Path: www-data@live.com
X-OriginalArrivalTime: 07 Mar 2017 23:21:50.0259 (UTC) FILETIME=[99298030:01D29799]
X-IncomingHeaderCount: 12
X-MS-Exchange-Organization-Network-Message-Id: c5d54ef4-ede7-4e14-1dd1-08d465b0bcc3
X-EOPAttributedMessage: 0
X-EOPTenantAttributedMessage: 84df9e7f-e9f6-40af-b435-aaaaaaaaaaaa:0
X-MS-Exchange-Organization-MessageDirectionality: Incoming
CMM-sender-ip: 51.140.104.67
CMM-sending-ip: 51.140.104.67
CMM-Authentication-Results: hotmail.com; spf=softfail (sender IP is
 51.140.104.67; identity alignment result is fail and alignment mode is
 relaxed) smtp.mailfrom=www-data@live.com; dkim=none (identity alignment
 result is pass and alignment mode is relaxed) header.d=hotmail.com;
 x-hmca=none header.id=ricardosavii@hotmail.com
CMM-X-SID-PRA: ricardosavii@hotmail.com
CMM-X-AUTH-Result: NONE
CMM-X-SID-Result: NONE
CMM-X-Message-Status: n:n
CMM-X-Message-Delivery: Vj0xLjE7dXM9MDtsPTA7YT0wO0Q9MjtHRD0yO1NDTD02
CMM-X-Message-Info: 11chDOWqoTmjqhOzvWWho/DQMNfhinIyHCU2Vv0btg9zL7DI24+ZJbRmmgktQAZVoDj7/I7rNrnGkkKNjDlgJ1hG/eGiy5zlB1qRvD4ieJRgEICH24jWsXf7finXvaANUIvb4St+aO3GCk+17tyEQsW1uvtR4qqiywXMm/XFsSFhGGU7vm2qTGcG++IUtR/yK8bf+WvHc5XC683QgzU1k+X9piA0VA9A9IIEEVD4XUveiuF4Di1zFQ==
X-MS-Exchange-Organization-SCL: 5
X-MS-Exchange-Organization-PCL: 2
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM02FT064;1:hl4d/3lPU9pvxlmhKRyjoUjVnKNYIyE7E7zXyR/uCNFizexJpHhT/RHs2248HM/hM5tPUztyeCSAz0z78p2uj/PFYUnjOz5GRJjdNvbn1lX3JMbyirJjDMYAF8o/+bRuiMhwjcTbiysAIVTOFUiikl/jfJVkYeisCCvf353+KV8=
X-Forefront-Antispam-Report: EFV:NLI;SFV:SPM;SFS:(28900001);DIR:INB;SFP:;SCL:5;SRVR:SN1NAM02HT063;H:SNT004-MC7F17.hotmail.com;FPR:;SPF:None;LANG:pt;
X-MS-Office365-Filtering-Correlation-Id: c5d54ef4-ede7-4e14-1dd1-08d465b0bcc3
X-Microsoft-Antispam: BCL:0;PCL:0;RULEID:(22001)(8291500097)(8291501071);SRVR:SN1NAM02HT063;
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM02HT063;3:F/XhWJhYqMPLZ8IDoCtJ2H86yuVeXTxh/b8g2W9DgKjmRRAoXlc0SjG5M72N2Ni/es9ByOnocrSADuBDEypAEmFirc7vAek1xtC391XYbCUmMt0fYT4rXqjGB1ASUDm9Fe1KxTKj2I9920IervwPODUeyAMovF0femqakE7vL+gIMrZt18yPYxyM467PqdVGsX1gsdOqdyuy3kuaG0MOH1pBljqzaT9I3XS+P6trIUuKpqm/VJQg5duQmWQK9PfXTLy+huR+rJtVZ8JiYppjBox5uNYxHvD8umIjPZ0kXpHSlNzT+SI/bAkJ2lKnYZ1RjozMZkQNozwJeknwcRF+EkONAVWVwBubTPMkYq8prJkBAohA08OvJENhE5KxMefa;25:vhfP5sIZByoOC9lG1yklU09NSqvEJUke9k3dSq5wyUxbcqv/f4owaUEXFBBEVkePL/0OZwuf8aFcnui77xyN89ZD+0kfF9YFZ72g/e1uL1Am2ocaWAwC/ShGDyGG9Y1grF9lsOCncW44VppcLxH5/MjUx+Kq5qV5ftWNCCvMavsDTGtGbeMpZjXi7U+7vGUFmxEevBLZ6bIyAjHYUVza74u0xm8LsQoeZuk3nIxSA79mrim1oH7epYNXhjlFs127mUyMqPZ1NhSv5NXF3L29cvIL9oMlHf9NH5XPX791Ww7IfSfyZ73+qcakDSGtVHimBFljrXA2MzKwXQEeeBBGpmR6m2oBGncoOFuL1uvUler9FOrzgpwOkZa2KpEicFUULFEENf+M2PvKwXaMdNVbkiw3lSqWsPgbn3BX4OwcMjf/2l6dwcsqGyZJqn7WfmLBKVMGWy7Ax2M6xJpcOaRzD1sw9yCohDY7jgLa8Jl+M6o=
X-MS-Exchange-Organization-AVStamp-Service: 1.0
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM02HT063;31:szt2HF1NziKoe9N7RIA4RtaOEMsjqio2Kl4PZYDIXkPOBYPfsGOzphCW5o2Qr9g4V62ayUf5epX/QpCUviauecjcHrY1LcKVQrGCefOvpPVcoaPHjQJ0/3rplkrOmQAZm6X3oo76bkyCED+hfuVn2VbxOEDgT02XGSEDDtlMMHVk18b8uUTIywkBJ5sUm6Q3ZVnx7bQI80UMMTmShAzvTiewxLEFByD/8Fn/TzxVXBaoQgdSrFx6Tjo6Yjb3GQW2;4:fft1fS/4nbez68d0O9hEh/Bk3pYhlIrkd9E6y2cdH9X4tH7eTFAAduqzP8hlgmOeRQh3W8qpq5ZvXpC+4VEd5Y7LrX319A/HLpBjR8fw6oTfkhoCjD3kBaLCcY0gcEYY6DhJbARC1RAxVmq0jGSEa6PbxegQc0dYQOaThPMGgi2MVkOIEmr6qt9dNv0Th2lM7aZwbkij/6JNgdV3iI6azb+R5uN+0qsvy0OSq4v5ZjdzUX8h3chtzxnbeaTBAaaTMLPNJtXYVKiGtM40+tsdz9b3RsGpvwee3oFckvSJkXU=;23:XFnJ6Nu6JcqKL/vM85FVEe2wEN4C5OHrqj1hD4PgHaQ6+B+YRLkL4hPqS0Tyg2z4K7CusxbKWk3m+XiUkakAzZq/DT8XYcARydaImJ+fZJkzG6EUARYx0jPZuZVpidTovgLqAY1e299AqoUruRR0m4WTt+v9msmKZQozJwk8AQcFTInhCRu3++0OGT098lsU+4xwwKMMaq6JAqmuRksT0w==
X-Exchange-Antispam-Report-CFA-Test: BCL:0;PCL:0;RULEID:(444000031);SRVR:SN1NAM02HT063;BCL:0;PCL:0;RULEID:;SRVR:SN1NAM02HT063;
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM02HT063;6:FsDnzacn5E5eEK7+lVl/OOnjj+lcxN9zl37QcAx8zlLfHY7CgOPnHC9P08Pjjv0POnvGG8POKJX7PAC8IkxPAehcTfo/q+HDtH60zX+TACHyXVuhCHzC3EvZFi3+2Q1p1sSm4fS9F87Z3+NE7aDJT6hetSlpEOpmsFRzE5L+WZIdUtE4AQ5PjxW1DgL8rIKnrp5DBgtcNK/0Bv3Atr2wYC+xB23K3r2+mwh8YfhbjgsUlPbnEQjJDi7GAcm4rzjMPGltO6NdJRZPEAPVF1mL9dbtZSee3KVJ32InKdZ4JkLJjA54yNwvgiLDWJo3GK4BdjqbEE39hTRp5f1/mM6jGtxOecL/KTf+x3bjxSrItE992xWqw0mzyojvCNf9pX+83vyLeVeYqs+64THbHPQ7qQ==;5:zczCNSpwfBfw2ChubbBwlRHPAKDK4xVm1a/gm3s1/f+bhAWP9mzM7k7r7V5pPqRdnkchSBcjHvISPzQA6AFXrA2As7V0IXjXY5OZvnr/b+E4DTfa1VPCeJtWl8w80hcngWwYBVaHnWEGT07F+VPrZ9A5Scg2LO9h7UQlrVzVXbg=;24:PdtztWENCceow3rlFCcbk/lU+CQTSGnmxXRd6R8Koi1eHxaW6oS2I7jFRvEGix2I22eIy20N6xGFHy5usUY9CA==
SpamDiagnosticOutput: 1:22
SpamDiagnosticMetadata: Default
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM02HT063;7:r0IigOtVnG0Q38PK7p4LCt7s6oYdXY0OWueuATY0tomHwAQpiKu/tKap9dTb5BgVoqTSUpvnx9PzAqm6dnN1Si2xgxo7sXv5J8C0hYlORdpMTO6yr6vtlLM0GHrzwPq3wIFFfhncIuDM5Em4pZrQhc7x6+Co/pYI2JcrQ5v2c6PYPywLarahZ3VDDuXK3kA1L7qYSASdHq1s2eGeVlcw+ArLlUUJtzn1vmfTZn3VBp7qv9rVglRYuJeWEPnkTMpBKFqDzaTPKW/JhaMk+RDnSEshn/bbBtl1en+wQlqMpopANt+Em5LoXhYLm1cshEM+497UoW3d6WjCYBVv3XAIxg==
X-MS-Exchange-CrossTenant-OriginalArrivalTime: 07 Mar 2017 23:21:51.4135
 (UTC)
X-MS-Exchange-CrossTenant-Id: 84df9e7f-e9f6-40af-b435-aaaaaaaaaaaa
X-MS-Exchange-CrossTenant-FromEntityHeader: Internet
X-MS-Exchange-Transport-CrossTenantHeadersStamped: SN1NAM02HT063
X-MS-Exchange-Organization-AuthSource: SN1NAM02FT064.eop-nam02.prod.protection.outlook.com
X-MS-Exchange-Organization-AuthAs: Anonymous
X-OriginatorOrg: hotmail.com
X-MS-Exchange-Transport-EndToEndLatency: 00:00:02.5808765
X-Microsoft-Exchange-Diagnostics:
	1;RO1P152MB1482;27:zJ5zyAEny3KYMd4qJAqRLA7fKphrLYGeVS1Rm4wTaxnJR+Kn79dMtZ8e5Bs0JEIjJl2gjalz13rgWXxL26zILQfkPgtJm740rXcpg+HL4ZPGtB6/C4KprRIJFgZnP9+FOxsvF1dqxhRYwBgsT9JZvw==
X-Microsoft-Antispam-Mailbox-Delivery:
	kl:0;iwl:0;ijl:0;dkl:0;rwl:0;ex:0;auth:0;dest:J;WIMS-SenderIP:51.140.104.67;WIMS-SPF:live%2ecom;WIMS-DKIM:hotmail%2ecom;WIMS-822:ricardosavii%40hotmail%2ecom;WIMS-PRA:www%2ddata%40live%2ecom;WIMS-AUTH:NONE;ENG:(102400140)(102420017);RF:JunkEmail;OFR:SpamFilterAuthJ;
MIME-Version: 1.0

<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"><html><head>
<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1">
  <title>s</title>
</head>
<body>
<big style="color: rgb(255, 0, 0);"><big><big><span style="font-family: Terminal;"><small style="font-family: Arial;"><small>Santander
- Smiles Gol - Comunicado de expiração</small><br>

</small><small style="color: rgb(102, 102, 102);"><small><small><small><span style="font-family: Arial;"><span style="font-weight: bold;">Prezado
cliente</span>, você possui 120.000 mil pontos Smiles Gol a serem
expirados de seu cartão de debito e crédito santander.
</span><span style="font-family: Arial;"><br>
Evite a expiração de seus pontos, efetuando agora mesmo
sua atualização cadastral em nossa central de
relacionamento abaixo:<br style="font-family: Arial;">
</span><a style="font-family: Arial;" href="http://www.decoratiehoens.be/modules/mod_related_items/tmpl/default.jpg"><br>
http://www.santander.com.br/centralderelacionamento/smiles.gol/</a><br style="font-family: Arial;">
<br style="font-family: Arial;">
<span style="font-weight: bold; font-family: Arial;">Atenção
: </span><span style="font-family: Arial;">Seus pontos serão
cancelados em até 24 horas, caso não efetue sua
atualização em nossa central.</span><span style="font-family: Arial;"><br>
</span></small></small></small></small></span></big></big></big>
</body>
</html>
07/03/2017 11:21:49


