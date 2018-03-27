# CustomSignatures

I created or modified custom signature for McAfee NSP for me.
Please use them at your own risks.

My Threat Repo is below.<BR>
https://otx.alienvault.com/user/papa_anniekey/pulses

<HR>

<li>UDS-HTTPJavaScript obfuscated with jjencode detected.zip<BR>
https://github.com/papa-anniekey/CustomSignatures/raw/master/UDS-HTTPJavaScript%20obfuscated%20with%20jjencode%20detected.zip
 Original made by me(^^)<BR>
 JJENCODE is obfuscate technique for Javascript. This technique sometime use for Malicious activity like inject code to vulnerable web content. This signature is detect JJENCODEed test within HTTP stream. If you'd like to know the JJENCODE, see below.<br>
jjencode demo
http://utf-8.jp/public/jjencode.html<P>
  

<li>Javascript obfuscated with JSFUCK.zip<BR>
https://github.com/papa-anniekey/CustomSignatures/blob/master/Javascript%20obfuscated%20with%20JSFUCK.zip
 Original made by me(^^)<BR>
 JSFUCK is obfuscate technique for Javascript. Obfuscated HavaScript is sometime use for Malicious activity like inject code to vulnerable web content. This signature tested within HTTP stream. If you'd like to know the JSFUCK, see below.<br>
JSFuck
http://www.jsfuck.com/<P>

<li>CVE-2017-10271.zip<BR>
 https://github.com/papa-anniekey/CustomSignatures/raw/master/CVE-2017-10271.zip<br>
Original made by me(^^)<BR>
 Vulnerability in the Oracle WebLogic Server component of Oracle Fusion Middleware (subcomponent: WLS Security). Supported versions that are affected are 10.3.6.0.0, 12.1.3.0.0, 12.2.1.1.0 and 12.2.1.2.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via HTTP to compromise Oracle WebLogic Server. Successful attacks of this vulnerability can result in takeover of Oracle WebLogic Server. CVSS 3.0 Base Score 7.5 (Availability impacts). CVSS Vector: (CVSS:3.0/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:N/A:H).
 
McAfee provided signature is existing but that URI condition is limited so caused F/N. 


<li>malicious RTF Files include OLE2Link.zip<BR>
 https://github.com/papa-anniekey/CustomSignatures/blob/master/malicious%20RTF%20Files%20include%20OLE2Link.zip<br>
 Original made by me(^^)<BR>
 Malicious RTF is embedded code associated with OLELink2 and ActiveX.
 For example, CVE-2017-0199(Vulnerability in Windows API(Microsoft OLE URL Moniker) of Microsoft Office/Wordpad). 
 McAfee provided a signature could detect but the condition is a little limited.<BR>
 (Similer detection is "HTTP: Malformed Windows RTF File Transferring" by McAfee Original.)<P>
  
<li>CVE-2018-0101<BR>
https://github.com/papa-anniekey/CustomSignatures/raw/master/FOX-SRT%20-%20Suspicious%20-%20Possible%20Fragmented%20Cisco%20IKE.zip<br>
https://github.com/papa-anniekey/CustomSignatures/raw/master/FOX-SRT%20-%20Exploit%20-%20Possible%20Shellcode%20in%20Cisco%20IKE.zip<p>

 Original is made by FOX-IT and NCC Group.
 https://gist.github.com/fox-srt/09401dfdfc15652b22956b9cc59f71cb
 FOX-SRT - Suspicious - Possible Fragmented Cisco IKE.zip<br>
 FOX-SRT - Exploit - Possible Shellcode in Cisco IKE.zip<br>
I customised it(i.e. Add Severity as High) for McAfee NSP version 9.1 or 8.3.


If you will use my custom McAfee NSP's Signatures, please keep in mind "Use at Own Risks".
