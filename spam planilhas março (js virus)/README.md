# viruse Planilhas Março

I've received the email in the **[Screenshot from 2017-03-07 01-56-10.png](https://github.com/ricoms/viruses/blob/master/spam%20planilhas%20mar%C3%A7o%20(js%20virus)/Screenshot%20from%202017-03-07%2001-56-55.png)** image.

Cliking on it directly downloads the **Planilha_17_Março_001.zip** file that contains the **Planilha_17_Março_001.js**. The .js has a link to domain: https://1458555568.rsc.cdn77.org/ProcessPedefender.zip

And **the ProcessPedefender.zip** contains an .exe file that I did not have time to tinker.


Case sent to cdn77 twitter.

email header origin:

Received: from FR1P152CA0063.LAMP152.PROD.OUTLOOK.COM (10.167.134.35) by
 RO1P152MB1482.LAMP152.PROD.OUTLOOK.COM (10.171.137.13) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.947.12 via Mailbox Transport; Tue, 7 Mar 2017 04:20:06 +0000
Received: from inbound.mail.protection.outlook.com (216.32.181.55) by
 FR1P152CA0063.outlook.office365.com (10.167.134.35) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.947.12 via Frontend Transport; Tue, 7 Mar 2017 04:20:06 +0000
Received: from CO1NAM04FT019.eop-NAM04.prod.protection.outlook.com
 (10.152.90.52) by CO1NAM04HT232.eop-NAM04.prod.protection.outlook.com
 (10.152.91.84) with Microsoft SMTP Server (version=TLS1_2,
 cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id 15.1.933.11; Tue, 7 Mar
 2017 04:20:05 +0000
Authentication-Results: spf=none (sender IP is 35.157.150.123)
 smtp.mailfrom=ip-172-31-9-224.us-west-2.compute.internal; hotmail.com;
 dkim=none (message not signed) header.d=none;hotmail.com; dmarc=fail
 action=none header.from=hotmail.com;
Received-SPF: None (protection.outlook.com:
 ip-172-31-9-224.us-west-2.compute.internal does not designate permitted
 sender hosts)
Received: from SNT004-MC11F4.hotmail.com (10.152.90.56) by
 CO1NAM04FT019.mail.protection.outlook.com (10.152.90.93) with Microsoft SMTP
 Server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_AES_256_CBC_SHA384_P384) id
 15.1.947.7 via Frontend Transport; Tue, 7 Mar 2017 04:20:04 +0000
X-IncomingTopHeaderMarker: OriginalChecksum:168F6ABEF8A392F43C3489DB302A9E4422741BE09B1DAE5A1B97688BB53252D5;UpperCasedChecksum:ECBEC9FD795EA1DBE7411AA186A01C50FD905DEEE4CA9AECCA82F198CF0CB577;SizeAsReceived:831;Count:12
Received: from ip-172-31-9-224.us-west-2.compute.internal ([35.157.150.123]) by SNT004-MC11F4.hotmail.com with Microsoft SMTPSVC(7.5.7601.23143);
	 Mon, 6 Mar 2017 20:19:59 -0800
Received: by ip-172-31-9-224.us-west-2.compute.internal (Postfix, from userid 33)
	id A7CF235069; Tue,  7 Mar 2017 03:58:49 +0000 (UTC)
To: <ricardosavii@hotmail.com>
Subject: Planilhas Março W4723948723      07/03/2017 12:58:49
X-PHP-Originating-Script: 0:ita.php
Content-Type: text/html; charset="iso-8859-1"
From: <ricardosavii@hotmail.com>
Message-ID: <20170307035849.A7CF235069@ip-172-31-9-224.us-west-2.compute.internal>
Date: Tue, 7 Mar 2017 03:58:49 +0000
Return-Path: www-data@ip-172-31-9-224.us-west-2.compute.internal
X-OriginalArrivalTime: 07 Mar 2017 04:19:59.0561 (UTC) FILETIME=[159A9B90:01D296FA]
X-IncomingHeaderCount: 12
X-MS-Exchange-Organization-Network-Message-Id: 2349ccae-053f-4fa3-fa47-08d465113bbe
X-EOPAttributedMessage: 0
X-EOPTenantAttributedMessage: 84df9e7f-e9f6-40af-b435-aaaaaaaaaaaa:0
X-MS-Exchange-Organization-MessageDirectionality: Incoming
CMM-sender-ip: 35.157.150.123
CMM-sending-ip: 35.157.150.123
CMM-Authentication-Results: hotmail.com; spf=none (sender IP is
 35.157.150.123; identity alignment result is fail and alignment mode is
 relaxed) smtp.mailfrom=www-data@ip-172-31-9-224.us-west-2.compute.internal;
 dkim=none (identity alignment result is pass and alignment mode is relaxed)
 header.d=hotmail.com; x-hmca=none header.id=ricardosavii@hotmail.com
CMM-X-SID-PRA: ricardosavii@hotmail.com
CMM-X-AUTH-Result: NONE
CMM-X-SID-Result: NONE
CMM-X-Message-Status: n:n
CMM-X-Message-Delivery: Vj0xLjE7dXM9MDtsPTA7YT0wO0Q9MjtHRD0yO1NDTD02
CMM-X-Message-Info: 11chDOWqoTmjqhOzvWWho/vK8oL2x1FIoEm0Tn+r3D4Vy8IHo2wUnh7Hfo3OG0wcOHd/Ij3sRMnJuYdLVW/wFHqhbUh9uSdu9taepYGwaRD4M6jM0+bIw5zVjfwCBuOPaD6gPS8BQRkyXiQ9r5NewxRgtgyl8zqGl7EyKXwbrXhOF708DZPQnU5wK9/r7ylyIx5RZrtqQxnUvZYZlq0QM0K3Xng+pD5/A3BH2Plwc4EIK68IuJfn9A==
X-MS-Exchange-Organization-SCL: 5
X-MS-Exchange-Organization-PCL: 2
X-Microsoft-Exchange-Diagnostics: 1;CO1NAM04FT019;1:lX8TzAZdkeklPORzws7BhOCMojp3CvwzqBqNHyXjQmCubHNa1b7GszPLkbY0yl1jWWkCLtzlb2VYkFzZWAPgl1g4KSeNHFdhufxsq3rwhrWJ+ZAbuFQqCpAZdBfjXGoPJiETiap5YxuPExShkS6LdwlaAVQOGblXYRMjqIQfNZw=
X-Forefront-Antispam-Report: EFV:NLI;SFV:SPM;SFS:(28900001);DIR:INB;SFP:;SCL:5;SRVR:CO1NAM04HT232;H:SNT004-MC11F4.hotmail.com;FPR:;SPF:None;LANG:pt;
X-MS-Office365-Filtering-Correlation-Id: 2349ccae-053f-4fa3-fa47-08d465113bbe
X-Microsoft-Antispam: BCL:0;PCL:0;RULEID:(22001)(8291500097)(8291501071);SRVR:CO1NAM04HT232;
X-Microsoft-Exchange-Diagnostics: 1;CO1NAM04HT232;3:nF0sCc36PBUI5RLn2ps0ixEpEgaBdpFHBXJHiXKdeZRV0wyezjkCsIz27IEF+0Wexbydwh7W8hdQNfrCCnJ2CNVL99K8wOim4qgLpyT28jFjL3DcRqY+4Dz8IaGztSm1TCDohF5TdYCrO/6Ko7iDnk1njmE3LePMhhyWPuO8rhwJ8Ye6uT/MW/K9fIETsTr/PODB7SFeKemXa020/xRgmqPTlr2lBXYTObp16oKbZq7LI5AwYLJPFwz8kRjorC2A4scTACl2B2vHTU5mr7T0a84YeXnOdh6QrXkNY37UCIwNSgPqfkt/uZFX71QFDVPvFgi5FPC9x3Sz0Oou+DQ1x6HjQHDRZ06Fm/P1kEXi1DwxE7RRAztJc4saV8FfSuRGS7n1IYyYkH2OuuirhBrGIw==;25:fQeBvZid6yvW7B8irLkp7p6Yt6PPGjh8Fj60MYWaQ31IPsoeR4do31AcxGhri0Q1tM4dCzu+YxNFylCLvorDijFQijtFy6KnIf4YXb0HZGKas5UecE421EO1JZQCjGvC38buOB2fg0vanf0hYwWSO2K7OHYRXdxfVM5ZXyefGHtVieI6R2FtZQz9z6ZEeNePxEmWdJ1Vw/1c3b/knjnX5zQaZbKgr1gm+/BSqisy27I/zhKGTePjADSRx0xkhn0pdN5PTHdqDGwb/ijOPFT37Jl2EiBw8LqGh54tC180u8FnqzvwTQSuzXLxcbSvHyXog+9EOlbbTgU8Y++njIxbHrsV16MO0asvi7507asRMnJZQsRVLSW7UqXYpzBIGv3VX+B7tYfJTfm2fwrTyslusU2DRrECiNwbESyMrfzqIUVcM/GfOTWd8BPq8lLwpv2wQnxqWtG5ojGXf/tCCr20HKSN41ODYVsywRTsTWX6ACo=
X-MS-Exchange-Organization-AVStamp-Service: 1.0
X-Microsoft-Exchange-Diagnostics: 1;CO1NAM04HT232;31:9/9ueJezkQq4tDuW2pD6XiZ6Sd3TaQG1lO0btf3zItTRA1q9pmdwfHi4O7WS9YOuECbidziQgl3I5bcDqcbJt205W09Wt3R4whnN/6pbPmtq6AFVpyS3ivzPEu/WyeIdk9SuzEm4e5fcHXW1eA/WFYXxeJwAmby4RUPN20ynnVFPMaWc9rVqYp5tY9N6EGAJIGQ5fvfahYzyC7ZrRmn4qXqBuIs6RfGRn80nNt+BF/Rz8SSGFKOkrjkCUXRIWbjy;4:ggCaI9cAIYtiMXOczs4eqQTeLOHpmppmSgLXQDo4c3kyG4/MpPqIVTeebuTJMKyQ0uLgEyIRmVEF5U616NEy/vD2Ijy9hLaDqd7oEh5r7O/4fuWS+SJrjo6SbOZm3OfylvvwGQWnL3ACSB38jpokAxHSuP4elKW7qUU5atv0baQJMbZAMDNdDu+KbanbWuug1xDz9U1t3cXdfH+qL6ergvR0svRy3/iw7VUE84T31C+KVqaOyzL1d31sYDOoZQl/arqPgPw4Qw61L7iGHfgnZM3ZEfyJq+ZdmpA0RqrNySk=;23:2zoKEvXX8pePthOo6tD59E3SInQL5FrtqiuSN8lJZYEEEHd1QbzwLVyCRZNX9PrjmVfNE7J6r2hHI2XXkrAVF4h5u5uXLTO/a5rH9Pd5Ub4ivL/unZ1NISLddmTt6qSy8ezguXx1rwVBgMi/txNw/5L5Yhb9Vj69YLUa/xyEo9f7AQny6tcexJbaDqRGPganDHPfAGnRkhoLnak6x90TuA==
X-Exchange-Antispam-Report-CFA-Test: BCL:0;PCL:0;RULEID:(444000031);SRVR:CO1NAM04HT232;BCL:0;PCL:0;RULEID:;SRVR:CO1NAM04HT232;
X-Microsoft-Exchange-Diagnostics: 1;CO1NAM04HT232;6:47dLC1Im9gmM0WP2WDYljGPmoAKUY9Xiw7t9qhEe126bxlHqgAZxGycoynmT5wDL4/qifT+kCcC9o+HAapugM17TcBjOAwy/UJI/qTzTutgPZGdh6ROlQ7t8E37KmKlh/jj1nUQEF4600rFZQ5U/AwH3lfQU5X+Lk4i1fx+J9pfViDZs4cECN/EFUzmyW1G4FVHWtPVzgyqxQrgaDvHTnd84xYO+eJ5gn81avS43MmI5hrVgHKweVOV62Yp2WP3yiNy6zStEN9nweM67Q+YpFd47fM3hRO6GXUTTbkLApn7BMfZpf+aDEtNGiuPm4SOQzIYvWC+rz2wMptG3FTgLRdorc/zdUFuM8mfHC4TmnbB4oWSq6eKdBdtEZg3GeywN3Kvkyx/yqFF3dDRaOVAFpQ==;5:Zs7hvWii3T9eCtouBXjlsDXnanfeCaJ0jqSOFSMibJVAezt041KbsbjARAjN2TREN3/nX1BLh8Ffqu2DbNzPTg4TcPgv4BvU2tCtrJIdwb5sjSdmuIZGwqQtKkBoOg4kmC+/zbJ81uTlKWbhRVbA1g==;24:TaHhEPk/bu8b0IFD0n56zemfh62B2r5NmUjJidPpBCf2Bhj+7AF/RAkDhYj8/lyYBYLPkbigriqXjV2gL2CLcA==
SpamDiagnosticOutput: 1:22
SpamDiagnosticMetadata: Default
X-Microsoft-Exchange-Diagnostics: 1;CO1NAM04HT232;7:BVVO/jnaRbwLJlcIHvvPTnXBQ6MmxyO0qX5l80IpboRpVkFxEY3lvvg2UWynWR6Z3+7ped4KN7A3nRoazBSwUaNRjF6uMjMsWZ8kkFiDPtna4trAXcsy24s5Ph8dIUhmxVY9RI+JG05X9rv3WorFx3Cmk+FTRAyFiZsYuffKSOr3kInKahZaW+vmu3yFEoCGgWZhwq+pBFee5hX01s1xo6fiLlkOfFhmFn1utgYancUbMXyjvNyYdagPn7CQuJxGIs9pcHpuQUOiMmHAfg9ihfBis4cqivXo5kbZkQIYYN/qTTZeW4VehqKjRTzp3khPmFiXa7G7t9omQb6ByuiHAQ==
X-MS-Exchange-CrossTenant-OriginalArrivalTime: 07 Mar 2017 04:20:04.7928
 (UTC)
X-MS-Exchange-CrossTenant-Id: 84df9e7f-e9f6-40af-b435-aaaaaaaaaaaa
X-MS-Exchange-CrossTenant-FromEntityHeader: Internet
X-MS-Exchange-Transport-CrossTenantHeadersStamped: CO1NAM04HT232
X-MS-Exchange-Organization-AuthSource: CO1NAM04FT019.eop-NAM04.prod.protection.outlook.com
X-MS-Exchange-Organization-AuthAs: Anonymous
X-OriginatorOrg: hotmail.com
X-MS-Exchange-Transport-EndToEndLatency: 00:00:02.1391209
X-Microsoft-Exchange-Diagnostics:
	1;RO1P152MB1482;27:4WjBxsrndGXZuazcKKN5v8/cr9tnJB9TOwBKOOBTfbWgzhRq8Qz3rxmrAthFIfXqoHYDM2VmrTtCc3sZWhzL5Ug50xMfIOwZQAu0XPEblpK9ADCwu3idfdBF4iQ1d/7Rk4Ull7gumiulCzcwBHAs4Q==
X-Microsoft-Antispam-Mailbox-Delivery:
	kl:0;iwl:0;ijl:0;dkl:0;rwl:0;ex:0;auth:0;dest:J;WIMS-SenderIP:35.157.150.123;WIMS-SPF:ip%2d172%2d31%2d9%2d224%2eus%2dwest%2d2%2ecompute%2einternal;WIMS-DKIM:hotmail%2ecom;WIMS-822:ricardosavii%40hotmail%2ecom;WIMS-PRA:www%2ddata%40ip%2d172%2d31%2d9%2d224%2eus%2dwest%2d2%2ecompute%2einternal;WIMS-AUTH:NONE;ENG:(102400140)(102420017);RF:JunkEmail;OFR:SpamFilterAuthJ;
MIME-Version: 1.0

<meta http-equiv="Content-Type" content="text/html; charset=iso-8859-1"><title>Planilhas Web</title>
</head>

<body>
<a href="http://planilhas-brasil-core.com.br/novas"><img src="http://i.imgur.com/AXFRkLu.jpg" width="967" height="388"></a>
</body>
</html>
07/03/2017 12:58:49
