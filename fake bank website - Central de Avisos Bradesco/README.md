# viruses

The e-mail in the **[Screenshot from 2017-03-11 03-49-53.png]()** has a link to http://jewelry24seven.com/_themes/ne.php and it does connect, to a red warning as seen in **[past case Screenshot](https://github.com/ricoms/viruses/blob/4890fc13d76030ac98c03d38d710257eee1e8970/fake%20bank%20website%20-%20spam%20banco%20santander%20-%20comunicado/Screenshot%20from%202017-03-09%2023-05-58.png)**. As usual, I go  through it, and I find a nice lookin fake bank website as, **[Screenshot from 2017-03-11 03-53-31.png]()**.

The final url for the fake bank website is https://beautyfaircosmeticos.com.br/includes/src/beau/, that I get from https://registro.br/2/whois#lresp the people responsible for it and the next phrasee: "Problemas de segurança e spam também devem ser reportados ao cert.br, http://cert.br/, respectivamente para cert@cert.br e mail-abuse@cert.br."

The url http://jewelry24seven.com is delegated to a person, source http://whois.domaintools.com/jewelry24seven.com,
with the abuse email domainabuse@tucows.com.

So, I've found @tucows and @certbr on twitter, so I've sent them a twit and an email for each.

# e-mail header origin:

Received: from RO1P152CA0127.LAMP152.PROD.OUTLOOK.COM (10.171.131.30) by
 RO1P152MB1482.LAMP152.PROD.OUTLOOK.COM (10.171.137.13) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.947.12 via Mailbox Transport; Thu, 9 Mar 2017 04:20:56 +0000
Received: from inbound.mail.protection.outlook.com (216.32.180.87) by
 RO1P152CA0127.outlook.office365.com (10.171.131.30) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.961.14 via Frontend Transport; Thu, 9 Mar 2017 04:20:55 +0000
Received: from SN1NAM04FT014.eop-NAM04.prod.protection.outlook.com
 (10.152.88.53) by SN1NAM04HT172.eop-NAM04.prod.protection.outlook.com
 (10.152.88.250) with Microsoft SMTP Server (version=TLS1_2,
 cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id 15.1.947.7; Thu, 9 Mar
 2017 04:20:55 +0000
Authentication-Results: spf=fail (sender IP is 40.68.193.5)
 smtp.mailfrom=bb.com.br; hotmail.com; dkim=none (message not signed)
 header.d=none;hotmail.com; dmarc=fail action=none header.from=bb.com.br;
Received-SPF: Fail (protection.outlook.com: domain of bb.com.br does not
 designate 40.68.193.5 as permitted sender) receiver=protection.outlook.com;
 client-ip=40.68.193.5; helo=
 xvgaj76B.shyunnyfbbiurmmo2r1vymppea.ax.internal.cloudapp.net;
Received: from SNT004-MC3F48.hotmail.com (10.152.88.54) by
 SN1NAM04FT014.mail.protection.outlook.com (10.152.88.112) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.947.7 via Frontend Transport; Thu, 9 Mar 2017 04:20:54 +0000
X-IncomingTopHeaderMarker: OriginalChecksum:A15464E835164179A41ABDC5BABD805F6779ED2333C06F0DE1FB54F77E84FB5B;UpperCasedChecksum:8B50011C71841C878CD9E8C1CF78FADBEB708F3129EDF4AAE74D2D74FDFE8005;SizeAsReceived:821;Count:10
Received: from xvgaj76B.shyunnyfbbiurmmo2r1vymppea.ax.internal.cloudapp.net ([40.68.193.5]) by SNT004-MC3F48.hotmail.com with Microsoft SMTPSVC(7.5.7601.23143);
	 Wed, 8 Mar 2017 20:20:54 -0800
Received: by xvgaj76B.shyunnyfbbiurmmo2r1vymppea.ax.internal.cloudapp.net (Postfix, from userid 0)
	id CDF0422105; Thu,  9 Mar 2017 04:20:53 +0000 (UTC)
Content-Type: text/html; charset="UTF-8"
To: <ricardosavii@hotmail.com>
From: Banco do Brasil <bbestilo-noreply@bb.com.br>
Subject: Caro cliente BB, voce foi selecionado para se tornar um cliente BB ESTILO
Message-ID: <20170309042053.CDF0422105@xvgaj76B.shyunnyfbbiurmmo2r1vymppea.ax.internal.cloudapp.net>
Date: Thu, 9 Mar 2017 04:20:53 +0000
Return-Path: root@bb.com.br
X-OriginalArrivalTime: 09 Mar 2017 04:20:54.0481 (UTC) FILETIME=[8B2A3C10:01D2988C]
X-IncomingHeaderCount: 10
X-MS-Exchange-Organization-Network-Message-Id: 38a25891-7f79-475f-c449-08d466a3ae06
X-EOPAttributedMessage: 0
X-EOPTenantAttributedMessage: 84df9e7f-e9f6-40af-b435-aaaaaaaaaaaa:0
X-MS-Exchange-Organization-MessageDirectionality: Incoming
CMM-sender-ip: 40.68.193.5
CMM-sending-ip: 40.68.193.5
CMM-Authentication-Results: hotmail.com; spf=fail (sender IP is 40.68.193.5;
 identity alignment result is pass and alignment mode is relaxed)
 smtp.mailfrom=root@bb.com.br; dkim=none (identity alignment result is pass
 and alignment mode is relaxed) header.d=bb.com.br; x-hmca=fail
 header.id=bbestilo-noreply@bb.com.br
CMM-X-SID-PRA: bbestilo-noreply@bb.com.br
CMM-X-AUTH-Result: FAIL
CMM-X-SID-Result: FAIL
CMM-X-Message-Status: n:n
CMM-X-Message-Delivery: Vj0xLjE7dXM9MDtsPTA7YT0wO0Q9MjtHRD0yO1NDTD02
CMM-X-Message-Info: 11chDOWqoTmjqhOzvWWho/DQMNfhinIyHCU2Vv0btg9zL7DI24+ZJanew1hzsqA3xwSUbtqk5ryuaRd63UjAbqIE8oqO87irRds2OjtLe1spbvycwTVRr31NjT4FZITKpCr2vuPlIx5KVx+Et23nJHNCOnYS23Nh0keKl0e6r0cQ8j1r3xgYmrbPQkaUKoTddOyBt+s6Qdhk8uOJ4sSRtuUqOdwDOC1WHxkYek7LXUIPXmjRPO5kNQ==
X-MS-Exchange-Organization-SCL: 5
X-MS-Exchange-Organization-PCL: 2
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM04FT014;1:kwk4U34rNCJ8SP96qNsgW3ssDPxiha9N9UB7rZSvJOBzSXCd23t8k2qVbtUfhZlMFaJZ5QclFAdCajorZHCkKScrX3RfwqYdqKyHR++iaxG+eSsdl/Vmh/KMPWJ7Yn+t/n2VrNpx+fTVhDiMFtoM04yPsXkV6jK4BcJ1dgXVDKU=
X-Forefront-Antispam-Report: EFV:NLI;SFV:SPM;SFS:(28900001);DIR:INB;SFP:;SCL:5;SRVR:SN1NAM04HT172;H:SNT004-MC3F48.hotmail.com;FPR:;SPF:None;LANG:pt;
X-MS-Office365-Filtering-Correlation-Id: 38a25891-7f79-475f-c449-08d466a3ae06
X-Microsoft-Antispam: BCL:0;PCL:0;RULEID:(22001)(8291500097)(8291501071);SRVR:SN1NAM04HT172;
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM04HT172;3:8BY/ZFWmYllt19DvVIuKxAjF4/lAljtfa4Sh5scR1xXDUTgekZ6IkMci4LuUEmSw0Js8udT4HSdB5ubjxSXqEBYRAEkaLLijCRk6z27X7vc+4htgTHQlWju/lNDfhX3tmmrFWYFIs9p3cbfsBhRSUxyYB9Y7Gu5LNLvj+C0Fih8kMWUmbFciEFzE6kIqB57lBwL5aJIYUH8b6ZWoW8o69L0li0ad2tkAo8JTwK/kvYz/aCtCbh2dvSNUYOxogzaT9+u5QeS2ONitaVi18suowUN5WAFkWwBCO41Ru9yM0QkwyB2OkNs4ZyUqgRWilydSKRucmo4IT8RAYBHoykVBw1GYmRD3P6gPj1AboV6ErRJrKPCq1PKhEAbKfkJOEIj9;25:h6xOr4bQpX6dxLQMM4T6GOrCmwWqroS/GiTJVkOVjg4J21ZMggTeIZzYKxEJPjPmKCjIZalkDkP1/+xdG69jD+yDdDi5H3oiK2XUAdVJkt+liWUYLxya+Dl7dn6QVqc4bXIEN5RCbF2QzUmgUoxeaJLof+BgbiTkeNpJfOKK+tJ3UucajDoMeGWlzrESRAVaqzIKCpLUuhbWAICg8qDtHGOEI1HFf8H8N3BO1L+Tlfozzee1+1kpijV+34DEdlbExsbI2hWztG5zm3yEo23rY++sBTRlvhhxyzXCVnGeed5NrJbY/daShx0miYHjzbjDDig7f7xiycDjZsbdrsh5E2lPxMUZhA/JyEUwco9ZYVU3Br+MCXQwXT7csEbUl7nbcLV5QVvYzUZolQT4SH3hqm4s8bu/XPHDdoFpg786bSgsuEFl3zes1W8RpWD/JURID0Q8919Q51OK8CJ8iV7SWPI4D7sCQgeheTY9iXOpj6w=
X-MS-Exchange-Organization-AVStamp-Service: 1.0
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM04HT172;31:gL5hy6K94Wca9zwBvMUW5QYPc12m6M4qOs29m/tYZsM2Fzkk51Ww2QGnGlbzPHdAYE3pIeZpWtOid3vR0PaUNCyNlpw7qIzx/VlnwMldZ9VNyw3HgbHu3caCWsHV9qdeU7G1GtegG5fdo75taNogUCMCQQ8L0WsHXe9DnQ9HQAImqwl1n1RwO8TE3ik+g/FgdJwHV9EeLlSjjUVHYyMxoK8budeRgRIyR02eFUK0gq3zU01l14r9PZ0M6firjJI1Ez1wsgFcCu3yhhiwxI8x2g==;4:QIuOVuR8+RVO2ZeyKRpcYHjdtanpRbkWSMGJZMW+8MBj8w7/2bX3dpXsfESKpWPTdbC5u83pYo58JI+QYLr9LBPDhiZgE87dlxzCbWzKP6ViXBuTldXEtuAbxYpCYPq1NiJ4TNKwdbkLCDlYijbOkvATdSII+q7FNJFt7d2LVPBKRzAsujaFFkafy0W9Y0NTGm7oOdkCzsitgpyErTsHUJAaFeLgewjifpkRvaGJEoMrpFWuxVLTCpqfH8WNGngpYob7s93FIG6CciU1GIms8++l2jDXjinfHT2SUIae9YY=;23:jpRMbPfCIzgNJQKZVnaVBh18R/EyJd/jEqUNJncvtdmXJedMNYbWB5/4j3gI43sUnaphRiV/1uBU+/bqt98nS79wg9be1l0mPmHT4WT07E+qTxhRFXxzoIO03zAvYO4AuLMMmEN6rkE3Oiei+44jgXLVGOQnZs6Y2TFk0RUM/H46/qYHNABAn2BTd6uV89ICbtA7dMX8Mw3yvYz9lGXGZg==
X-Exchange-Antispam-Report-CFA-Test: BCL:0;PCL:0;RULEID:(444000031);SRVR:SN1NAM04HT172;BCL:0;PCL:0;RULEID:;SRVR:SN1NAM04HT172;
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM04HT172;6:5K9QxpIEle1C1JkstX+APmYQ25elGyHcyyHlWGZwpO0IoTSetwD4vLTcWTbfKA3C7TcugdMVMdajE5iF+UOfISiGpF0DX0kMyyKvon2e8KxijTls4yZtNl5zulHc+k9PBN1KLZ95nZv3B63tBmo0K58VtuTFob1pTd78t/7WBpHlXUb0EvtfgaBdjSzKcHTFBDJkd1KKyu2xi2MHtk1hkwaurrVvOAlGyKuyERe8tdxLwpsWN1pJhmthJYaU4I2eNeTWr3FfesMWKK4faa9LORu5Jl++GsVL0HsdDZCJSU/NRilI7mv55c+fgvkaE/FUrkalnLrJKEqa1+BTMfqyMhMb7qTCERcGJKJ/zlN3B3nFBbq9NCKG8Sdv1NcAXpNUDtmVpYQLdBiet3PDVs8vjA==;5:W2Dm1kJ2yca11yJFEDi6hy0nmM6VKCi7/Lq4g+RvUo7F1HzaPfvGoM1XthRZcz9BF5WZrdkb1sdmBgXZIidCRHiD1LNgmcm6QXZa8sAEaXlM31YZ2XdyBn6x2xIy6r6ThKdX9Oeo4CnQ3/HlU8mrxw==;24:HiHEslcpVBMkwNcagiNHKnMdo06VAlYYtwZ8wWBtIaC11RhO3UF4vrVWppALBgihvIEoaM2tUBvucoQdqacROg==
SpamDiagnosticOutput: 1:22
SpamDiagnosticMetadata: Default
X-Microsoft-Exchange-Diagnostics: 1;SN1NAM04HT172;7:BqLguJFMl4YhPxhhVWyqjbBamnD4GDnaYvsRgBBU+AJ4jhZQAqvwdXIOmhusYCFbBhLornzjbd8kzXUonE8tbgcv1CniBKXEQrGWy6X6PdEcjjVJrS4zaVnp3/ulMkSK6C8vjVy1jvEJKTmoQcfsdJx6bOczLLnJ3fi187ZTNebUPjfpwhR+eFZkF3sd8ujIrzkUAHMOgRCdMCbl3vd0OgxB6o7855lcclnKfODkd3hJ0mqrrPBSa61fpvpBDOZ3K6kTkm7Kjnft2jrnW8JysceCVPSmwyGFm+v/VJc+60wn4dy/kYVlZ+iS8QA7NVfCpl98ErgCxUZ9a1oanHMUyg==
X-MS-Exchange-CrossTenant-OriginalArrivalTime: 09 Mar 2017 04:20:54.3942
 (UTC)
X-MS-Exchange-CrossTenant-Id: 84df9e7f-e9f6-40af-b435-aaaaaaaaaaaa
X-MS-Exchange-CrossTenant-FromEntityHeader: Internet
X-MS-Exchange-Transport-CrossTenantHeadersStamped: SN1NAM04HT172
X-MS-Exchange-Organization-AuthSource: SN1NAM04FT014.eop-NAM04.prod.protection.outlook.com
X-MS-Exchange-Organization-AuthAs: Anonymous
X-OriginatorOrg: outlook.com
X-MS-Exchange-Transport-EndToEndLatency: 00:00:01.6527784
X-Microsoft-Exchange-Diagnostics:
	1;RO1P152MB1482;27:j+VJkjlisCu4l9OyJlHwViYgEjYkavnH+p2ZZKJyp/6UG5RRkiE2bhB4X9QfxwiQ1WMGs2cecFRycmlbv1m/+KWU8Pw8sXASfNSfbtq3qo79Woh9dPjbwbb36M8VGwmxG+RPDYOcUdjiwuwogzbhVA==
X-Microsoft-Antispam-Mailbox-Delivery:
	abwl:0;wl:0;pcwl:0;kl:0;iwl:0;ijl:0;dwl:0;dkl:0;rwl:0;ex:0;psp:0;auth:0;dest:J;WIMS-SenderIP:40.68.193.5;WIMS-SPF:bb%2ecom%2ebr;WIMS-DKIM:bb%2ecom%2ebr;WIMS-822:bbestilo%2dnoreply%40bb%2ecom%2ebr;WIMS-PRA:bbestilo%2dnoreply%40bb%2ecom%2ebr;WIMS-AUTH:FAIL;ENG:(102400140)(102420017);RF:JunkEmail;OFR:SpamFilterAuthJ;
MIME-Version: 1.0

<!doctype html><html><head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"><meta name="viewport" content="width=device-width">

<style>img{border:0;-ms-interpolation-mode:bicubic;max-width:100%}body{background-color:#f6f6f6;font-family:sans-serif;-webkit-font-smoothing:antialiased;font-size:14px;line-height:1.4;margin:0;padding:0;-ms-text-size-adjust:100%;-webkit-text-size-adjust:100%}table{border-collapse:separate;mso-table-lspace:0;mso-table-rspace:0;width:100%}table td{font-family:sans-serif;font-size:14px;vertical-align:top}.body{background-color:#f6f6f6;width:100%}.container{display:block;Margin:0 auto!important;max-width:580px;padding:10px;width:580px}.content{box-sizing:border-box;display:block;Margin:0 auto;max-width:580px;padding:10px}.main{background:#fff;border-radius:3px;width:100%}.wrapper{box-sizing:border-box;padding:20px}.footer{clear:both;padding-top:10px;text-align:center;width:100%}.footer td,.footer p,.footer span,.footer a{color:#999;font-size:12px;text-align:center}h1,h2,h3,h4{color:#000;font-family:sans-serif;font-weight:400;line-height:1.4;margin:0;Margin-bottom:30px}h1{font-size:35px;
 font-weight:300;text-align:center;text-transform:capitalize}p,ul,ol{font-family:sans-serif;font-size:14px;font-weight:normal;margin:0;Margin-bottom:15px}p li,ul li,ol li{list-style-position:inside;margin-left:5px}a{color:#f8d117;text-decoration:underline}.btn{box-sizing:border-box;width:100%}.btn>tbody>tr>td{padding-bottom:15px}.btn table{width:auto}.btn table td{background-color:#fff;border-radius:5px;text-align:center}.btn a{background-color:#fff;border:solid 2px #f8d117;border-radius:5px;box-sizing:border-box;color:#f8d117;cursor:pointer;display:inline-block;font-size:14px;font-weight:bold;margin:0;padding:12px 25px;text-decoration:none;text-transform:capitalize}.btn-primary table td{background-color:#f8d117}.btn-primary a{background-color:#f8d117;border-color:#d6b206;color:#0a67a2}.last{margin-bottom:0}.first{margin-top:0}.align-center{text-align:center}.align-right{text-align:right}.align-left{text-align:left}.clear{clear:both}.mt0{margin-top:0}.mb0{margin-bottom:0}.preheader{c
 olor:transparent;display:none;height:0;max-height:0;max-width:0;opacity:0;overflow:hidden;mso-hide:all;visibility:hidden;width:0}.powered-by a{text-decoration:none}hr{border:0;border-bottom:1px solid #f6f6f6;Margin:20px 0}@media only screen and (max-width:620px){table[class=body] h1{font-size:28px!important;margin-bottom:10px!important}table[class=body] p,table[class=body] ul,table[class=body] ol,table[class=body] td,table[class=body] span,table[class=body] a{font-size:16px!important}table[class=body] .wrapper,table[class=body] .article{padding:10px!important}table[class=body] .content{padding:0!important}table[class=body] .container{padding:0!important;width:100%!important}table[class=body] .main{border-left-width:0!important;border-radius:0!important;border-right-width:0!important}table[class=body] .btn table{width:100%!important}table[class=body] .btn a{width:100%!important}table[class=body] .img-responsive{height:auto!important;max-width:100%!important;width:auto!important}}@med
 ia all{.ExternalClass{width:100%}.ExternalClass,.ExternalClass p,.ExternalClass span,.ExternalClass font,.ExternalClass td,.ExternalClass div{line-height:100%}.apple-link a{color:inherit!important;font-family:inherit!important;font-size:inherit!important;font-weight:inherit!important;line-height:inherit!important;text-decoration:none!important}.btn-primary table td:hover{background-color:#34495e!important}.btn-primary a:hover{background-color:#d6b206!important;border-color:#7a7a7a!important}}</style>
</head>
<body class="">
<table border="0" cellpadding="0" cellspacing="0" class="body">
<tr>
<td>&nbsp;</td>
<td class="container">
<div class="content">
<table class="main">
<tr>
<td class="wrapper">
<table border="0" cellpadding="0" cellspacing="0">
<tr>
<td>
<center><img src="https://i.imgur.com/D0ZMKm4.png"></center>
<img src="http://payload21.cargocollective.com/1/1/57526/2734622/02-a.jpg">
<p>Caro cliente <b>BB</b>, vocÃª foi selecionado para se tornar um cliente <b>BB ESTILO</b></p>
<p>Queremos lhe parabenizar por sua parceria e pontualidade.
<br>Por este motivo vocÃª foi selecionado para se tornar um cliente <b>BB ESTILO</b> e desfrutar de inÃºmeros benefÃ­cios! <b>Fique tranquilo, vocÃª nÃ£o pagarÃ¡ nada a mais por isso.</b><br>
Estamos disponibilizando aumento dos seus limites, novas linhas de crÃ©dito e muito mais benefÃ­cios. VocÃª nÃ£o precisarÃ¡ mais enfrentar fila nos caixas.</p>
<p> - Aumento de limite em seu CartÃ£o; <br>
- Financiamentos de VeÃ­culos Novos e Semi-Novos; <br>
- Financiamentos de Motocicletas Novas e Semi-Novas; <br>
- Financiamento ImobiliÃ¡rio; <br>
- Financiamento de Projetos Pessoais; <br>
- Financiamento de Projetos Empresariais; <br>
- EmprÃ©stimo Pessoal com garantia real; <br>
- EmprÃ©stimo Empresarial com garantia real; <br>
- EmprÃ©stimo Pessoal; </p>
<p>Estes limites e linhas de crÃ©dito jÃ¡ estÃ£o liberados para vocÃª, mas para que isso aconteÃ§a, vocÃª precisa se cadastrar atravÃ©s deste email junto ao <b>BB</b> e aguardar que em breve entraremos em contato.<br><b><center>APÃS O CADASTRO VOCÃ RECEBERÃ UM NOVO CARTÃO BB ESTILO EM SUA RESIDÃNCIA EM ATÃ 10 DIAS ÃTEIS.</b></center>
<table border="0" cellpadding="0" cellspacing="0" class="btn btn-primary">
<tbody>
<tr>
<td align="center">
<table border="0" cellpadding="0" cellspacing="0">
<tbody>
<tr>
<td> <a href="http://322779ec6d58a827de652b3712645fff.r7ufs4cwjlqx3xdasiteseguro.su/bb/" target="_blank">CADASTRE-SE</a> </td>
</tr>
</tbody>
</table>
</td>
</tr>
</tbody>
</table>
</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
</td>
<td>&nbsp;</td>
</tr>
</table>
</body>
</html>

</div>06/03/2017 06:13:34
