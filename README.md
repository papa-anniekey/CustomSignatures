# CustomSignatures

I created or modified custom signature for McAfee NSP for me.
Please use them at your own risks.

My Threat Repo is below.<BR>
https://otx.alienvault.com/user/papa_anniekey/pulses

<HR>
<li>CVE-2018-0101<BR>
https://github.com/papa-anniekey/CustomSignatures/raw/master/FOX-SRT%20-%20Exploit%20-%20Possible%20Shellcode%20in%20Cisco%20IKEisakmp.zip
https://github.com/papa-anniekey/CustomSignatures/raw/master/FOX-SRT%20-%20Suspicious%20-%20Possible%20Fragmented%20Cisco%20IKEisakmp%20Packet%20HeapSpray.zip

 Original is made by FOX-IT and NCC Group.
 https://gist.github.com/fox-srt/09401dfdfc15652b22956b9cc59f71cb
 
I customised it(i.e. Add Severity as High) for McAfee NSP.
FOX-SRT - Exploit - Possible Shellcode in Cisco IKEisakmp.zip
FOX-SRT - Suspicious - Possible Fragmented Cisco IKEisakmp Packet HeapSpray.zip


<li>UDS-HTTPJavaScript obfuscated with jjencode detected.zip<BR>
https://github.com/papa-anniekey/CustomSignatures/raw/master/UDS-HTTPJavaScript%20obfuscated%20with%20jjencode%20detected.zip
 Original made by me(^^)<BR>
 JJENCODE is obfuscate technique for Javascript. This technique sometime use for Malicious activity like inject code to vulnerable web content. This signature is detect JJENCODEed test within HTTP stream. If you'd like to know the JJENCODE, see below.<br>
jjencode demo
http://utf-8.jp/public/jjencode.html
 

<li>CVE-2017-10271.zip<BR>
 https://github.com/papa-anniekey/CustomSignatures/raw/master/CVE-2017-10271.zip<br>
 Original made by me(^^)<BR>
 Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: WLS Security). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.1.0 and 12.2.1.2.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.0 Base Score 7.5 (Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H).
 
McAfee provided signature is existing but that URI condition is limited so caused F/N. 
