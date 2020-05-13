# Apache-Struts-2.5-2.5.12---REST-Plugin-XStream-Remote-Code-Execution
## EDB-ID:42627    CVE:2017-9805

`CVE-2017-9805` is a vulnerability in Apache Struts related to using the Struts REST plugin with XStream handler to handle XML payloads. If exploited it allows a remote unauthenticated attacker to run malicious code on the application server to either take over the machine or launch further attacks from it.
Attackers can execute arbitrary code remotely by exploiting this vulnerability.
While the attackers are not privileged, they have access to plenty of interesting files on the local file system and can also potentially be leveraged for privilege escalation. 
Attackers can get an interactive command line of the remote target machine and they basically have control over it.
You will get realize, that it really isn't  hard to take control of this server using this exploit, so you should definitely figure out if you are running this software and if you are get it patched as soon as possible,  because of this is definitely a critical vulnerability.
