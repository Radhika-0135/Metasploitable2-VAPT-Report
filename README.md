# Metasploitable2-VAPT-Report
Comprehensive VAPT report on Metasploitable 2 lab environment covering enumeration, exploitation, 22 severity-mapped findings, and technical remediation.

# Metasploitable 2 - Network Vulnerability Assessment & Penetration Testing (VAPT) Report

An industry-grade security assessment and penetration testing project targeting a simulated Metasploitable 2 lab environment. This repository documents a complete, end-to-end security audit demonstrating manual enumeration, vector analysis, and controlled exploitation workflows.

### Executive Summary & Scope
* Assessment Type: Network Vulnerability Assessment and Penetration Testing (VAPT).
* Total Findings: 22 vulnerabilities thoroughly analyzed and documented.
* Risk Breakdown: 11 Critical | 8 High | 3 Medium.
* Environment: Controlled Virtual Lab (Kali Linux & Oracle VirtualBox).

### Core Attack Vectors & Exploitation Highlights
* Unauthenticated Backdoors: Exploited hardcoded and backdoor vulnerabilities in vsftpd 2.3.4, UnrealIRCd, and the ingreslock listener (Port 1524) for direct root-level execution.
* Legacy Cleartext Protocols: Audited and abused insecure remote administration services including Telnet, rlogin, and rsh.
* Web & Application Exploitation: Executed remote code execution (RCE) via PHP CGI argument injection (CVE-2012-1823) and mapped exposed administrative endpoints via directory enumeration.
* Service Misconfigurations: Assessed wildcard NFS exports, outdated database releases (MySQL, PostgreSQL), and weak cryptographic configurations.

### Professional Deliverables
* Proof of Concept (PoC): Detailed technical evidence, command outputs, and terminal logs for every verified finding.
* Actionable Remediation Roadmap: Comprehensive hardening strategies and defense-in-depth recommendations structured by severity level.
