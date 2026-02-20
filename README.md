# The Security Prompt OS
## 200+ AI Prompts for Pentesters & Bug Hunters

![Security Prompt OS](https://img.shields.io/badge/Version-2.0-blue)
![ChatGPT-Claude-Gemini](https://img.shields.io/badge/Supports-ChatGPT%20%7C%20Claude%20%7C%20Gemini-green)

---

## Welcome to the Security Prompt OS

This is the most comprehensive AI prompt collection for security professionals. Whether you're a bug bounty hunter, penetration tester, red teamer, or security researcher, these prompts will 10x your workflow.

### What You Get

- **200+ Curated Prompts** across 8 categories
- **Multi-Model Support** - Works with ChatGPT, Claude, and Gemini
- **Workflow Chains** - Complete end-to-end engagement workflows
- **Notion-Ready** - Import directly into your workspace
- **Real Examples** - Based on actual bug bounty findings

---

## Table of Contents

1. [Reconnaissance](#reconnaissance)
2. [Vulnerability Discovery](#vulnerability-discovery)
3. [Exploitation](#exploitation)
4. [Report Writing](#report-writing)
5. [Code Review](#code-review)
6. [Red Team](#red-team)
7. [CTF](#ctf)
8. [Workflow Chains](#workflow-chains)

---

## Category 1: RECONNAISSANCE PROMPTS

### 1.1 Subdomain Enumeration Strategy

> Act as an expert bug bounty hunter with 10+ years of experience in reconnaissance. Generate a comprehensive subdomain enumeration strategy for [TARGET]. Include: 1) Passive enumeration sources (Certificate Transparency logs, DNS aggregators, search engines) 2) Active enumeration techniques (DNS bruteforce, alteration attacks, DNS zone transfers) 3) Tools to use with optimal parameters 4) Priority order for efficiency 5) Common pitfalls to avoid. Format the output as a step-by-step checklist.

### 1.2 Port Scanning Analysis

> You are a penetration tester analyzing nmap scan results. Analyze the following nmap output: [PASTE NMAP RESULTS]. For each open port, identify: 1) Service version and potential vulnerabilities 2) Misconfigurations to exploit 3) Quick wins (default credentials, verbose vs anonymous access) 4) Priority attack path. Format as a vulnerability report with CVSS estimates.

### 1.3 JavaScript File Extraction

> As a senior web security consultant, provide a systematic approach to extract and analyze JavaScript files from [TARGET URL]. Include: 1) Tools and techniques for JS extraction 2) Patterns to search for (API endpoints, hardcoded secrets, interesting comments) 3) How to automate analysis 4) CommonJS vs ES6 module analysis 5) Dynamic vs static analysis. Provide specific regex patterns for finding sensitive data.

### 1.4 API Endpoint Discovery

> Act as an API security expert. Generate a comprehensive API recon methodology for discovering hidden API endpoints including: 1) Passive endpoints (Swagger, OpenAPI, GraphQL introspection) 2) Active fuzzing wordlists specific to APIs 3) Parameter discovery techniques 4) Version detection methods 5) Rate limiting bypass for enumeration. Include tool recommendations with specific command examples.

### 1.5 GitHub Reconnaissance

> You are an OSINT specialist focusing on GitHub recon. Create a thorough methodology for finding sensitive data in GitHub repositories including: 1) Dorks for finding credentials, keys, and secrets 2) Historical commit analysis 3) GitHub code search strategies 4) Organization enumeration 5) Gist and secret scanning 6) CI/CD pipeline analysis. Provide exact search queries that work.

### 1.6 DNS Enumeration Deep Dive

> As a DNS security expert, provide advanced DNS enumeration techniques for bug bounty hunting. Cover: 1) Zone transfer testing 2) DNS wildcard handling 3) Subdomain Takeover detection 4) CAA/SPF/DMARC analysis 5) DNS over HTTPS enumeration 6) Fast-flux detection. Include Python scripts for automation.

### 1.7 S3 Bucket Hunting

> Act as a cloud security specialist. Generate an S3 bucket enumeration methodology including: 1) Bucket naming pattern generation 2) Tools for automated checking 3) Common misconfiguration checks 4) Bucket takeover testing 5) Automated exploitation scripts. Provide real examples of vulnerable bucket patterns.

### 1.8 Shodan/Censys Queries

> You are an IoT security researcher. Create optimized search queries for Shodan and Censys to find: 1) Vulnerable services 2) Default credentials 3) Exposed dashboards 4) Database servers 5) Industrial control systems 6) CCTV cameras. Include specific dorks and filters for each category.

### 1.9 WayBack Machine Recon

> As an OSINT analyst, provide a comprehensive approach to using the WayBack Machine for reconnaissance: 1) Historical URL discovery 2) Parameter mining 3) JavaScript archive analysis 4) Old endpoint identification 5) Version detection. Include tools like waybackurls, gau, and gospider.

### 1.10 Technology Fingerprinting

> Act as a web application security tester. Create a methodology for identifying web technologies including: 1) Header analysis 2) HTML source inspection 3) JavaScript framework detection 4) Server identification 5) CMS detection 6) WAF identification. Include tools and specific detection methods.

### 1.11 Email Reconnaissance

> As an OSINT specialist, provide email enumeration techniques for bug bounty: 1) Email format discovery 2) Breached database lookup 3) Social media enumeration 4) Company directory analysis 5) Email pattern guessing. Include tools like theHarvester, Hunter.io alternatives.

### 1.12 Employee Identification

> You are a social engineering specialist. Generate a methodology for identifying key employees at [TARGET COMPANY] including: 1) LinkedIn enumeration 2) Twitter/X reconnaissance 3) Conference talk analysis 4) GitHub contributor analysis 5) Blog/technical writing identification. Include tools and automation techniques.

### 1.13 WAF Identification & Bypass

> Act as a web application penetration tester. Create a comprehensive WAF identification and bypass guide: 1) WAF detection techniques 2) Common bypass methods for major WAFs 3) Payload encoding strategies 4) Protocol-level bypasses 5) Tools for automated bypass attempts. Include real bypass techniques.

### 1.14 SSL/TLS Analysis

> As a network security consultant, provide SSL/TLS analysis methodology: 1) Certificate inspection 2) Weak cipher detection 3) TLS version analysis 4) Certificate transparency logs 5) Heartbleed/other TLS vulnerabilities. Include tools and specific test cases.

### 1.15 Content Discovery

> Act as a web security tester. Generate a content discovery methodology: 1) Directory enumeration 2) File extension fuzzing 3) Backup file hunting 4) Log file discovery 5) Configuration file finding. Include wordlists and tool recommendations.

### 1.16 Cloud Asset Discovery

> You are a cloud security specialist. Provide methodology for discovering cloud assets: 1) AWS enumeration (S3, EC2, Lambda) 2) Azure resource discovery 3) GCP asset identification 4) DigitalOcean/other cloud providers 5) Cloud metadata service exploitation. Include specific tools and techniques.

### 1.17 Passive Reconnaissance Summary

> As an expert OSINT analyst, create a comprehensive passive reconnaissance workflow that: 1) Starts with minimal target information 2) Uses only passive sources (no direct interaction) 3) Builds a complete target profile 4) Identifies all external attack surfaces 5) Documents findings systematically. Include toolchain and priority ordering.

### 1.18 Active Scanning Strategy

> Act as a penetration tester. Design an active scanning strategy that: 1) Minimizes detection 2) Maximizes coverage 3) Handles rate limiting 4) Manages scope carefully 5) Extracts maximum information. Include specific tool configurations.

### 1.19 Network Mapping

> You are a network penetration tester. Create a methodology for comprehensive network mapping: 1) Internal vs external perspectives 2) Network topology discovery 3) Identifying critical assets 4) Segmentation analysis 5) Trust relationship mapping. Include visualization techniques.

### 1.20 Mobile App Recon

> Act as a mobile security specialist. Provide mobile app reconnaissance: 1) APK/JAAT analysis 2) Traffic interception setup 3) Static analysis methodology 4) Dynamic testing approach 5) Backend API discovery. Include tools and Frida scripts.

### 1.21 OAuth/SSO Reconnaissance

> As an authentication security expert, provide OAuth and SSO reconnaissance: 1) OAuth flow analysis 2) SSO provider enumeration 3) Token analysis 4) Misconfiguration detection 5) Implementation weakness finding. Include specific vulnerable patterns.

### 1.22 CDN Bypass Techniques

> You are a security researcher specializing in CDN bypass. Create a methodology for CDN reconnaissance: 1) CDN identification 2) Origin server discovery 3) DNS record analysis 4) SSL certificate hunting 5) Web cache deception attacks. Include specific tools and real examples.

### 1.23 Internet Archive Analysis

> As an OSINT specialist, provide Internet Archive analysis for security testing: 1) Historical website analysis 2) Deleted content recovery 3) Configuration leak discovery 4) Version identification 5) Backup file hunting. Include specific queries and tools.

### 1.24 DNS Zone Transfer Testing

> Act as a network security consultant. Generate DNS zone transfer testing methodology: 1) Manual zone transfer attempts 2) Automated tools 3) Alternative DNS record enumeration 4) DNS reputation analysis 5) Wildcard DNS handling. Include specific commands and tools.

### 1.25 Vulnerability Scanner Optimization

> You are a professional penetration tester. Create optimized vulnerability scanning methodology: 1) Nmap NSE scripts selection 2) Nuclei template tuning 3) Custom exploit development 4) False positive reduction 5) Reporting automation. Include specific configurations for maximum efficiency.

---

## Category 2: VULNERABILITY DISCOVERY PROMPTS

### 2.1 XSS Discovery & Testing

> Act as an expert XSS hunter. Generate a comprehensive XSS testing methodology including: 1) Context-based payload selection 2) DOM XSS vs Reflected vs Stored testing 3) WAF bypass techniques 4) Filter evasion 5) Blind XSS testing 6) Advanced PoC development. Include specific payloads organized by context.

### 2.2 SQL Injection Patterns

> As a database security specialist, provide SQL injection discovery patterns: 1) Error-based detection 2) Boolean-based blind injection 3) Time-based blind injection 4) Union-based injection 5) Second-order injection 6) Out-of-band injection. Include payloads for MySQL, PostgreSQL, MSSQL, Oracle.

### 2.3 IDOR Discovery

> Act as a web application security tester. Create IDOR vulnerability discovery methodology: 1) Horizontal privilege escalation testing 2) Vertical privilege escalation 3) Parameter manipulation techniques 4) HTTP method manipulation 5) API parameter analysis. Include real bug bounty examples.

### 2.4 Business Logic Flaws

> You are a security consultant specializing in business logic vulnerabilities. Generate methodology for finding logical flaws: 1) Payment manipulation 2) Race conditions 3) Account takeover techniques 4) Inventory manipulation 5) Authentication bypass 6) Authorization flaws. Include test cases and examples.

### 2.5 Auth Bypass Techniques

> Act as an authentication security expert. Provide authentication bypass techniques: 1) Parameter manipulation 2) Session handling issues 3) JWT bypass methods 4) OAuth misconfigurations 5) 2FA bypass 6) Default credential testing. Include specific vulnerable patterns.

### 2.6 SSRF Testing

> As a web security specialist, create comprehensive SSRF testing methodology: 1) Cloud metadata service testing 2) Internal port scanning 3) Protocol smuggling 4) DNS rebinding 5) Blind SSRF discovery 6) Bypass techniques. Include payloads and testing approach.

### 2.7 XXE Analysis

> Act as an XML security expert. Provide XXE vulnerability discovery: 1) Basic XXE detection 2) Blind XXE testing 3) XXE via file upload 4) XXE via SAML 5) Out-of-band XXE 6) DTD inclusion attacks. Include specific payloads for different contexts.

### 2.8 Race Conditions

> You are a security researcher specializing in timing vulnerabilities. Generate race condition discovery methodology: 1) Burp Turbo Intruder usage 2) Python concurrency testing 3) Time-of-check-time-of-use testing 4) Coupon manipulation 5) Password reset race conditions 6) Session handling race conditions.

### 2.9 JWT Analysis

> Act as a cryptographic security specialist. Provide JWT security analysis: 1) Algorithm confusion attacks 2) Key confusion exploitation 3) Null signature testing 4) JWK header injection 5) Weak secret brute forcing 6) Key rotation issues. Include tools and specific attacks.

### 2.10 Open Redirect Testing

> As a web security tester, create open redirect discovery methodology: 1) Parameter-based redirect testing 2) Fragment-based redirects 3) SSRF to open redirect chains 4) OAuth redirect manipulation 5) Bypass techniques 6) Impact escalation. Include payloads organized by context.

### 2.11 CSRF Exploitation

> You are a web application security specialist. Provide CSRF discovery: 1) Form-based CSRF testing 2) JSON CSRF testing 3) Multi-part form CSRF 4) CORS misconfiguration testing 5) Logout CSRF 6) CSRF token bypass. Include tools and specific techniques.

### 2.12 SSRF to RCE Chain

> Act as a penetration tester. Generate a methodology for escalating SSRF to RCE: 1) Internal service identification 2) Redis exploitation 3) Docker API exploitation 4) Cloud metadata exploitation 5) Internal service chaining 6) Specific payloads for common internal services.

### 2.13 Command Injection

> As a command injection specialist, provide comprehensive testing methodology: 1) Black-box detection 2) Time-based blind injection 3) Out-of-band exploitation 4) Filter bypass techniques 5) WAF bypass 6) Context-specific payloads. Include payloads for different OS and contexts.

### 2.14 File Inclusion

> Act as a web security expert. Create file inclusion discovery methodology: 1) Path traversal testing 2) Null byte injection 3) Wrapper protocols 4) Log poisoning 5) Session file inclusion 6) PHP/other language specifics. Include specific test cases.

### 2.15 XML External Entity

> You are an XML security specialist. Provide XXE comprehensive testing: 1) Internal entity testing 2) External entity exploitation 3) Parameter entity usage 4) XInclude attacks 5) SVG file XXE 6) Excel file XXE. Include payloads for different file types.

### 2.16 Insecure Deserialization

> Act as an application security specialist. Generate deserialization vulnerability testing: 1) PHP unserialize testing 2) Python pickle testing 3) Java deserialization 4) .NET deserialization 5) Known gadget chains 6) YSoSerial usage. Include specific payloads and tools.

### 2.17 Template Injection

> As a web security tester, provide template injection discovery: 1) Server-side template injection detection 2) Jinja2 exploitation 3) Twig exploitation 4) ERB/Blade/Smarty testing 5) Sandbox escape techniques 6) Blind template injection. Include specific payloads.

### 2.18 WebSocket Testing

> You are a real-time security specialist. Create WebSocket security testing methodology: 1) Connection testing 2) Message manipulation 3) Origin testing 4) Cross-site WebSocket hijacking 5) Denial of service 6) Business logic testing. Include tools and techniques.

### 2.19 GraphQL Security

> Act as an API security expert. Provide GraphQL security testing: 1) Introspection testing 2) Query complexity attacks 3) Alias abuse 4) Directive abuse 5) Batch query attacks 6) Authorization testing. Include specific attack queries and tools.

### 2.20 HTTP Request Smuggling

> As a protocol security specialist, generate HTTP request smuggling discovery: 1) CLTE testing 2) TECL testing 3) Differential responses 4) WAF bypass 5) Internal desync 6) Response queue poisoning. Include specific payloads and detection techniques.

### 2.21 DOM-Based Vulnerabilities

> You are a client-side security specialist. Provide DOM vulnerability discovery: 1) DOM XSS sources and sinks analysis 2) Client-side prototype pollution 3) URL manipulation 4) PostMessage vulnerabilities 5) Browser extension testing. Include analysis methodology.

### 2.22 Web Cache Poisoning

> Act as a caching security expert. Create web cache poisoning methodology: 1) Cache key identification 2) Parameter pollution 3) Header injection 4) Cache probing techniques 5) Permanent poisoning 6) Cache deception attacks. Include specific test cases.

### 2.23 Host Header Attacks

> As a web security tester, provide Host header attack discovery: 1) Host header injection 2) Password reset poisoning 3) Web cache poisoning via host 4) Bypass techniques 5) Internal host header abuse. Include specific payloads and testing approach.

### 2.24 MIME Sniffing

> You are a browser security specialist. Generate MIME sniffing vulnerability testing: 1) Content-Type manipulation 2) XSS via MIME sniffing 3) JSON MIME confusion 4) Polyglot file creation 5) Response sniffing attacks. Include specific file payloads.

### 2.25 CORS Misconfiguration

> Act as an API security expert. Provide CORS misconfiguration discovery: 1) Origin reflection testing 2) Null origin exploitation 3) Wildcard CORS analysis 4) Predomain/Subdomain takeover 5) CORS + XSS chaining 6) Credential leakage testing.

---

## Category 3: EXPLOITATION PROMPTS

### 3.1 Advanced Payload Generation

> Act as an exploit developer. Generate context-specific payloads for: 1) XSS with specific WAF bypass 2) SQL injection for specific database 3) Command injection for specific OS 4) File inclusion for specific web server 5) Custom payload for target technology. Provide working, tested payloads.

### 3.2 Privilege Escalation

> As a post-exploitation specialist, provide Windows/Linux privilege escalation methodology: 1) Enumeration scripts analysis 2) Kernel exploit identification 3) Service exploitation 4) Sudo/sudoers misconfigurations 5) Scheduled tasks 6) Registry/run key persistence. Include specific commands and tools.

### 3.3 Shell Generation

> You are a reverse engineering specialist. Generate various shellcode and reverse shell payloads: 1) Windows reverse shell 2) Linux reverse shell 3) Web shell variations 4) One-liner variations 5) Encoded/obfuscated shells 6) Staged vs stageless. Include encoding options.

### 3.4 SQL Injection to RCE

> Act as a database security expert. Provide SQL injection to RCE methodology: 1) INTO OUTFILE writing 2) MSSQL xp_cmdshell 3) PostgreSQL COPY 4) Oracle Java execution 5) MySQL UDF exploitation 6) Chaining with other vulnerabilities.

### 3.5 LFI to RCE

> As a file inclusion specialist, create LFI to RCE escalation path: 1) Log poisoning (Apache, SSH) 2) /proc/self/environ injection 3) Session file inclusion 4) PHP filter wrapper 5) Data:// protocol 6) Expect:// wrapper. Include specific techniques.

### 3.6 XXE to RCE

> You are an XML exploitation specialist. Generate XXE to RCE methodology: 1) Parameter entity with external DTD 2) SVG with embedded scripts 3) Docx/Excel XXE to RCE 4) SOAP XXE exploitation 5) Blind XXE with FTP 6) XXE in PDF generation.

### 3.7 Java Deserialization

> Act as a Java security specialist. Provide Java deserialization exploitation: 1) Gadget chain identification 2) ysoserial usage 3) Custom gadget development 4] Spring/BlazeDS exploitation 5] Jackson/JGadget bypass 6] DNS/exfiltration via deserialization.

### 3.8 XML Injection Payloads

> As an injection specialist, generate comprehensive XML injection payloads: 1) Entity-based attacks 2) XInclude injection 3) XSLT injection 4) XPath injection 5] SOAP injection 6] XML DoS payloads. Include context-specific payloads.

### 3.9 Template Injection RCE

> You are a server-side exploitation specialist. Provide template injection to RCE: 1) Jinja2 sandbox escape 2) Twig RCE 3) ERB/Rails RCE 4) Freemarker RCE 5) Velocity RCE 6) Jade/Jadeite RCE. Include specific payloads and techniques.

### 3.10 Cross-Site Scripting Escalation

> Act as a client-side exploitation expert. Generate XSS escalation methodology: 1) Cookie stealing with exfiltration 2] Keylogging 3] Session hijacking 4] Phishing via XSS 5] Internal network scanning 6] Browser exploitation. Include working PoC code.

### 3.11 SSRF Exploitation Framework

> As an internal network specialist, create comprehensive SSRF exploitation: 1) Internal port scanning 2) Service identification 3] Cloud metadata extraction 4) Redis exploitation 5) Internal service chaining 6) Pivoting through SSRF. Include specific techniques and payloads.

### 3.12 Authentication Bypass

> You are an authentication security specialist. Generate authentication bypass techniques: 1) SQL injection in login 2] OAuth bypass 3] JWT bypass 4] Session fixation 5] Parameter tampering 6] Race conditions in auth. Include specific vulnerable patterns.

### 3.13 Authorization Bypass

> Act as an authorization specialist. Provide authorization bypass methods: 1) IDOR exploitation 2] Parameter manipulation 3] HTTP method override 4] Header manipulation 5] Forced browsing 6] Role manipulation. Include specific test cases.

### 3.14 JWT Exploitation

> As a cryptographic security expert, provide JWT exploitation: 1) Algorithm confusion attack 2) None algorithm exploitation 3) Weak secret cracking 4) JWK header injection 5) Key confusion 6) Time-based attacks. Include tools and specific attacks.

### 3.15 File Upload Exploitation

> You are a file upload security specialist. Generate upload exploitation: 1) Extension bypass 2) Content-Type manipulation 3] Double extensions 4) Null byte injection 5] Polyglot files 6) htaccess abuse. Include specific bypass techniques.

### 3.16 Remote Code Execution

> Act as an exploitation specialist. Provide RCE discovery and exploitation: 1) Code injection testing 2) Command injection escalation 3] Deserialization RCE 4] File upload RCE 5] Deserialization RCE chains 6] Custom exploit development. Include specific techniques.

### 3.17 OAuth 2.0 Exploitation

> As an authentication specialist, generate OAuth exploitation: 1) Redirect URI bypass 2] State parameter bypass 3] Scope escalation 4] Token leakage 5] Authorization code theft 6] Token reuse attacks. Include specific vulnerable patterns.

### 3.18 SAML Exploitation

> You are an SSO security specialist. Provide SAML exploitation: 1) XML signature wrapping 2) XXE in SAML 3) Assertion injection 4] Replay attacks 5) Token manipulation 6] Entity expansion attacks. Include specific techniques.

### 3.19 Internal Network Pivoting

> Act as a network exploitation specialist. Create internal network pivoting methodology: 1) SSH tunneling 2] Proxychains usage 3] Metasploit pivoting 4] Empire/Covenant usage 5] Port forwarding 6] SOCKS proxies. Include specific tools and configurations.

### 3.20 Container Escape

> As a container security specialist, provide container escape methodology: 1) Docker breakout techniques 2] Container escape to host 3] Kubernetes exploitation 4] Privileged container abuse 5] Volume mounting exploitation 6] Container root escape. Include specific techniques.

### 3.21 Cloud Exploitation

> You are a cloud security specialist. Generate cloud exploitation: 1) AWS privilege escalation 2] Azure AD exploitation 3] GCP metadata exploitation 4] Lambda exploitation 5] Cloud credential harvesting 6] Cloud-native attacks. Include specific techniques.

### 3.22 Wireless Exploitation

> Act as a wireless security specialist. Provide wireless exploitation: 1) WEP/WPA/WPA2 cracking 2] WPS exploitation 3] Evil twin attacks 4] Rogue AP deployment 5] Handshake capture 6] PMKID attacks. Include specific tools and techniques.

### 3.23 Active Directory Exploitation

> As an AD security specialist, create AD exploitation methodology: 1) Kerberoasting 2] AS-REP roasting 3] Golden/Silver ticket attacks 4] Pass-the-hash/ticket 5] DCSync attacks 6] ACL abuse. Include specific tools and commands.

### 3.24 Browser Exploitation

> You are a browser security researcher. Provide browser exploitation: 1) XSS to CSP bypass 2] Service worker exploitation 3] CORS exploitation 4] PostMessage vulnerabilities 5] UXSS exploitation 6] Extension exploitation. Include specific techniques.

### 3.25 Vulnerability Chaining

> Act as an expert penetration tester. Generate vulnerability chaining methodology: 1) Recon to vuln discovery 2] Low to high severity chains 3] Multiple bug combinations 4] Time-based chaining 5] Logic flaw chains 6) Complete engagement chains. Include real examples.

---

## Category 4: REPORT WRITING PROMPTS

### 4.1 Professional Report Template

> As a senior penetration tester, create a comprehensive bug bounty report template including: 1) Executive summary 2) Scope definition 3) Methodology 4) Findings with severity 5) Proof of concept 6) Impact analysis 7) Remediation recommendations 8) References. Format as professional markdown.

### 4.2 Impact Maximization

> You are a technical writer specializing in security reports. Generate techniques for maximizing the impact of vulnerability reports: 1) Business impact articulation 2) Technical severity translation 3) Likelihood assessment 4) Attack scenario development 5) Compelling PoC creation 6) Report structure optimization. Include examples.

### 4.3 PoC Development

> Act as a security consultant. Provide PoC development guidance: 1) Minimal PoC creation 2] Video PoC guidelines 3] Code snippets for PoC 4] Screenshot requirements 5] Step-by-step reproduction 6] Tool output documentation. Include templates.

### 4.4 CVSS Scoring

> As a CVSS specialist, provide accurate CVSS scoring methodology: 1) Base metric selection 2] Temporal considerations 3] Environmental customization 4) Score justification 5] Common scoring mistakes 6] Score appeals. Include real examples with scoring.

### 4.5 Executive Summary

> You are a security communications expert. Create executive summary writing: 1) Non-technical language 2) Business impact focus 3] Key findings highlight 4] Risk prioritization 5] Recommended actions 6] ROI of fixing. Include template and examples.

### 4.6 Remediation Guidance

> Act as a security architect. Provide remediation guidance: 1) Technical fixes 2] Configuration changes 3] Code modifications 4] Architecture changes 5] Compensating controls 6] Validation testing. Include specific recommendations for common vulnerabilities.

### 4.7 Evidence Documentation

> As a forensic documentation specialist, create evidence documentation: 1] Screenshot requirements 2] Video recording guidelines 3] Log extraction 4] Tool output preservation 5] Timestamp documentation 6] Chain of custody. Include specific requirements.

### 4.8 Technical Writing

> You are a technical security writer. Provide technical writing optimization: 1] Clear vulnerability description 2] Technical accuracy 3] Reproducibility 4] Proper terminology 5] Structured findings 6] Format consistency. Include style guide.

### 4.9 Report Review

> Act as a quality assurance specialist. Generate report review checklist: 1] Technical accuracy 2] Completeness 3] Clarity 4] Grammar/spelling 5] Formatting 6] Consistency. Include review criteria.

### 4.10 Severity Justification

> As a risk assessment specialist, provide severity justification: 1) Technical impact analysis 2] Business risk assessment 3] Exploitability factors 4] Likelihood calculation 5] CVSS vs real risk 6] Stakeholder communication. Include methodology.

### 4.11 Finding Categorization

> You are a security analyst. Create finding categorization: 1] Severity assignment 2] Category organization 3] Similar finding grouping 4] Root cause identification 5] Trend analysis 6] Remediation priority. Include framework.

### 4.12 Compliance Mapping

> Act as a compliance specialist. Generate compliance mapping: 1] OWASP Top 10 alignment 2] CVE mapping 3] CWE classification 4] NIST framework 5] PCI DSS requirements 6] Industry standards. Include templates.

### 4.13 Visual Documentation

> As a security documentation expert, create visual documentation: 1] Architecture diagrams 2] Attack flow diagrams 3] Timeline visualization 4] Screenshot annotations 5] Flowchart creation 6] Tool output graphs. Include guidelines.

### 4.14 Client Communication

> You are a client relations specialist. Provide client communication: 1] Finding presentation 2] Technical explanation 3] Remediation roadmap 4] Timeline negotiation 5] Risk acceptance 6] Escalation procedures. Include templates.

### 4.15 Report Templates

> Act as a reporting specialist. Generate multiple report formats: 1] Bug bounty report 2] Pentest executive report 3] Vulnerability assessment 4] Red team findings 5] Compliance report 6] Technical detail report. Include templates for each.

### 4.16 Finding Duplication

> As a data analyst, provide duplicate finding handling: 1] Similar finding identification 2] Root cause analysis 3] Deduplication methods 4] Combined reporting 5] Impact aggregation 6] Resolution tracking. Include methodology.

### 4.17 Remediation Tracking

> You are a remediation specialist. Create tracking methodology: 1] Finding to fix mapping 2] Status tracking 3] Timeline management 4] Verification process 5] Regression testing 6] Closure criteria. Include templates.

### 4.18 Real Report Examples

> Act as a report writer. Provide real report examples: 1] Critical SQL injection report 2] IDOR finding report 3] RCE vulnerability report 4] Authentication bypass report 5] Sensitive data exposure 6] Business logic flaw. Include full reports.

### 4.19 Before/After Reports

> As a security consultant, generate before/after reporting: 1] Initial finding description 2] Remediation implementation 3] Retest verification 4] Residual risk assessment 5] Improvement metrics 6] Final report. Include templates.

### 4.20 Multi-Language Reports

> You are an international security specialist. Create multi-language support: 1] Language selection 2] Technical translation 3] Cultural considerations 4] Local compliance 5] Regional standards 6] Localization tips. Include guidelines.

### 4.21 Vulnerability Disclosure

> Act as a disclosure specialist. Provide vulnerability disclosure: 1] Responsible disclosure timeline 2] Vendor communication 3] Public disclosure guidelines 4] Embargo handling 5] Coordinated disclosure 6] Press handling. Include templates.

### 4.22 Report Automation

> As an automation specialist, generate report automation: 1] Finding extraction 2] Template population 3] Screenshot embedding 4] PDF generation 5] Version control 6] Export options. Include tools and scripts.

### 4.23 Metrics & KPIs

> You are a security metrics specialist. Create reporting metrics: 1] Findings by severity 2] Time to remediation 3] Risk reduction 4] Coverage metrics 5] False positive rates 6] Trend analysis. Include dashboards.

### 4.24 Post-Incident Reports

> Act as an incident response specialist. Generate incident reports: 1] Timeline reconstruction 2] Root cause analysis 3] Attack vector identification 4] Impact assessment 5] Remediation steps 6] Prevention measures. Include templates.

### 4.25 Security Scorecard

> As a security analyst, provide security scorecard creation: 1] Risk scoring methodology 2] Finding aggregation 3] Trend visualization 4] Benchmark comparison 5] Improvement tracking 6] Executive presentation. Include templates.

---

## Category 5: CODE REVIEW PROMPTS

### 5.1 JavaScript Security Review

> Act as a JavaScript security expert. Perform comprehensive JavaScript security review for: 1] XSS vulnerabilities 2] Prototype pollution 3] Command injection 4] Path traversal 5] Hardcoded secrets 6] Unsafe regex. Analyze this code: [PASTE CODE]. Provide specific vulnerable lines and fixes.

### 5.2 Python Security Review

> As a Python security specialist, review Python code for: 1] Code injection 2] YAML deserialization 3] Pickle vulnerabilities 4] SQL injection 5] Path traversal 6] Insecure deserialization. Analyze this code: [PASTE CODE]. Identify vulnerabilities with specific fixes.

### 5.3 PHP Security Review

> Act as a PHP security expert. Provide PHP security review for: 1] SQL injection 2] Command injection 3] File inclusion 4] Session security 5] Cryptographic issues 6] Code execution. Analyze this code: [PASTE CODE]. Identify and fix vulnerabilities.

### 5.4 API Security Review

> You are an API security specialist. Review API code for: 1] Authentication flaws 2] Authorization issues 3] Input validation 4] Rate limiting 5] Data exposure 6] Business logic. Analyze this API code: [PASTE CODE]. Identify security issues.

### 5.5 Android Security Review

> Act as an Android security expert. Review Android code for: 1] Insecure storage 2] Hardcoded keys 3] Intent sniffing 4] WebView vulnerabilities 5] SSL pinning bypass 6] Rooting detection. Analyze this code: [PASTE CODE]. Identify issues.

### 5.6 iOS Security Review

> As an iOS security specialist, review iOS code for: 1] Data storage issues 2] Keychain usage 3] Clipboard exposure 4] Touch ID/Face ID bypass 5] Jailbreak detection 6] Network security. Analyze this code: [PASTE CODE]. Identify vulnerabilities.

### 5.7 Node.js Security Review

> Act as a Node.js security expert. Review Node.js code for: 1] Prototype pollution 2] Path traversal 3] Command injection 4] Regex DoS 5] JWT issues 6] Middleware misconfigurations. Analyze this code: [PASTE CODE]. Identify issues.

### 5.8 Java Security Review

> You are a Java security specialist. Review Java code for: 1] SQL injection 2] XML external entity 3] Path traversal 4] Deserialization 5] XXE 6] Insecure randomness. Analyze this code: [PASTE CODE]. Identify vulnerabilities.

### 5.9 .NET Security Review

> As a .NET security expert, review .NET code for: 1] SQL injection 2] Path traversal 3] XSS 4] Deserialization 5] ViewState issues 6] Request validation. Analyze this code: [PASTE CODE]. Identify security issues.

### 5.10 Ruby Security Review

> Act as a Ruby security specialist. Review Ruby code for: 1] SQL injection 2] Command injection 3] YAML deserialization 4] File access 5] Mass assignment 6] Session issues. Analyze this code: [PASTE CODE]. Identify vulnerabilities.

### 5.11 Go Security Review

> As a Go security expert, review Go code for: 1] SQL injection 2] Template injection 3] Path traversal 4] Command injection 5] Randomness issues 6] Concurrency problems. Analyze this code: [PASTE CODE]. Identify issues.

### 5.12 React Security Review

> You are a React security specialist. Review React code for: 1] XSS vulnerabilities 2] Dangerous URL handling 3] State manipulation 4] Prop drilling issues 5] Authentication bypass 6] Client-side storage. Analyze this code: [PASTE CODE]. Identify vulnerabilities.

### 5.13 Vue.js Security Review

> Act as a Vue.js security expert. Review Vue.js code for: 1] XSS vulnerabilities 2] v-html usage 3] Event handling 4] Component security 5] State management 6] Authentication. Analyze this code: [PASTE CODE]. Identify issues.

### 5.14 Angular Security Review

> As an Angular security specialist, review Angular code for: 1] XSS vulnerabilities 2] Template injection 3] DomSanitizer bypass 4] Router security 5] HTTP security 6] State management. Analyze this code: [PASTE CODE]. Identify vulnerabilities.

### 5.15 Django Security Review

> You are a Django security expert. Review Django code for: 1] SQL injection 2] XSS vulnerabilities 3] CSRF issues 4] Command injection 5] File uploads 6] Authentication. Analyze this code: [PASTE CODE]. Identify issues.

### 5.16 Flask Security Review

> Act as a Flask security specialist. Review Flask code for: 1] SQL injection 2] XSS vulnerabilities 3] Command injection 4] Secret key issues 5] Session security 6] Template injection. Analyze this code: [PASTE CODE]. Identify vulnerabilities.

### 5.17 Spring Security Review

> As a Spring security expert, review Spring code for: 1] SQL injection 2] XXE vulnerabilities 3] Deserialization 4] Authentication bypass 5] Authorization issues 6] Data exposure. Analyze this code: [PASTE CODE]. Identify issues.

### 5.18 Express.js Security Review

> You are an Express.js security specialist. Review Express code for: 1] Header security 2] Helmet usage 3] Input validation 4] Rate limiting 5] Session security 6] Error handling. Analyze this code: [PASTE CODE]. Identify vulnerabilities.

### 5.19 Infrastructure as Code

> Act as a DevSecOps specialist. Review IaC for: 1] Terraform security 2] CloudFormation issues 3] Kubernetes manifests 4] Docker security 5] Ansible playbooks 6] GitHub Actions. Analyze this code: [PASTE CODE]. Identify issues.

### 5.20 Database Query Review

> As a database security specialist, review database queries for: 1] SQL injection vulnerabilities 2] Query performance 3] Authorization in queries 4] Sensitive data exposure 5] Indexing issues 6] Connection security. Review these queries: [PASTE QUERIES]. Identify issues.

### 5.21 Authentication Code Review

> You are an authentication security specialist. Review auth code for: 1] Password storage 2] Session management 3] Token generation 4] MFA implementation 5] Password reset flow 6] Login brute force. Analyze this code: [PASTE CODE]. Identify vulnerabilities.

### 5.22 Cryptographic Review

> Act as a cryptography specialist. Review crypto implementation for: 1] Algorithm selection 2] Key management 3] IV handling 4] Random number generation 5] Hashing implementation 6] Encryption at rest. Analyze this code: [PASTE CODE]. Identify issues.

### 5.23 Third-Party Library Review

> As a dependency security specialist, review third-party usage for: 1] Known vulnerabilities 2] Outdated libraries 3] License issues 4] Supply chain risks 5] Deprecated APIs 6] Unnecessary dependencies. Analyze dependencies: [PASTE DEPENDENCIES]. Identify risks.

### 5.24 Configuration Review

> You are a configuration security specialist. Review configurations for: 1] Environment variables 2] Config files 3] Secrets management 4] Default credentials 5] Overly permissive settings 6] Missing security headers. Review this config: [PASTE CONFIG]. Identify issues.

### 5.25 Complete Code Review

> Act as a senior security architect. Perform comprehensive security review combining: 1] All OWASP Top 10 2] Business logic 3] Authentication/Authorization 4] Data handling 5] Error handling 6] Logging/Monitoring. Analyze this codebase: [PASTE CODE]. Comprehensive vulnerability assessment.

---

## Category 6: RED TEAM PROMPTS

### 6.1 Phishing Campaign Design

> Act as a red team specialist. Create comprehensive phishing campaign methodology: 1] Target reconnaissance 2] Email template creation 3] Landing page development 4] Credential harvesting 5] Multi-factor bypass 6] Campaign metrics. Include specific techniques and tools.

### 6.2 Social Engineering

> As a social engineering specialist, generate methodology: 1] Pretext development 2] Voice phishing (vishing) 3] SMS phishing (smishing) 4] In-person impersonation 5] Supply chain compromise 6] Baiting techniques. Include real examples.

### 6.3 C2 Infrastructure

> You are a command and control specialist. Create C2 infrastructure: 1] Domain registration 2] Redirector setup 3] TLS certificates 4] Beacon configuration 5] Redirection rules 6] Persistence mechanisms. Include specific tools and configurations.

### 6.4 Lateral Movement

> Act as a lateral movement specialist. Provide methodology: 1] Pass-the-hash/ticket 2] WinRM exploitation 3] WMI exploitation 4] Scheduled tasks 5] Service exploitation 6] RDP hijacking. Include specific commands and tools.

### 6.5 Persistence Techniques

> As a persistence specialist, generate persistence techniques: 1] Windows registry Run keys 2] Scheduled tasks 3] Service creation 4] DLL hijacking 5] WMI event subscription 6] ACIDBRIGHT/COVENANT usage. Include specific techniques.

### 6.6 Privilege Escalation

> You are a Windows privilege escalation specialist. Create methodology: 1] Service binary replacement 2] Registry manipulation 3] Token manipulation 4] Trusted path traversal 5] UAC bypass 6] Kernel exploits. Include specific techniques and tools.

### 6.7 Data Exfiltration

> Act as an exfiltration specialist. Generate data exfiltration: 1] DNS tunneling 2] HTTPS exfiltration 3] Cloud storage abuse 4] Email exfiltration 5] ICMP tunneling 6] Steganography. Include tools and techniques.

### 6.8 Physical Access

> As a physical security specialist, provide methodology: 1] Badge cloning 2] Lock picking guidance 3] Tailgating 4] Shoulder surfing 5] USB attacks 6] Hardware keyloggers. Include techniques and tools.

### 6.9 Wireless Attacks

> You are a wireless security specialist. Create wireless attack methodology: 1] WPA2 cracking 2] Rogue AP deployment 3] Evil twin attacks 4] Wireless reconnaissance 5] Bluetooth attacks 6] RFID cloning. Include tools and techniques.

### 6.10 Social Media OSINT

> Act as an OSINT specialist. Generate social media reconnaissance: 1] Employee identification 2] Personal information gathering 3] Location tracking 4] Relationship mapping 5] Sentiment analysis 6] Account takeover. Include tools and techniques.

### 6.11 Spear Phishing

> As a targeted attack specialist, create spear phishing: 1] Target profiling 2] Personalized pretext 3] Malicious document creation 4] Sandbox evasion 5] Tracking mechanisms 6] Campaign optimization. Include templates.

### 6.12 Watering Hole

> You are an attack specialist. Generate watering hole methodology: 1] Target website identification 2] Compromising legitimate sites 3] Malicious code injection 4] Exploit deployment 5] Victim tracking 6] Campaign management. Include techniques.

### 6.13 Credential Attacks

> Act as a credential specialist. Provide credential attacks: 1] Password spraying 2] Credential stuffing 3] Pass-the-hash 4] Kerberoasting 5] AS-REP roasting 6] Golden ticket attacks. Include tools and techniques.

### 6.14 Active Directory Attacks

> As an AD specialist, create AD attack methodology: 1] BloodHound usage 2] PowerView commands 3] DCSync attacks 4] ACL abuse 5] Trust exploitation 6] Persistence in AD. Include specific commands.

### 6.15 Cloud Red Team

> You are a cloud security specialist. Generate cloud red team: 1] AWS attack paths 2] Azure AD exploitation 3] GCP privilege escalation 4] Cloud credential harvesting 5] Lambda backdoors 6] Storage exploitation. Include techniques.

### 6.16 Bypass AV/EDR

> Act as an evasion specialist. Create AV/EDR bypass: 1] Encrypted payloads 2] Obfuscation techniques 3] Living-off-the-land 4] PowerShell AMSI bypass 5] Syscall usage 6] Custom malware development. Include techniques.

### 6.17 OSINT for Red Team

> As an OSINT specialist, provide red team OSINT: 1] Corporate reconnaissance 2] Employee OSINT 3] Technical reconnaissance 4] Public leaks 5] Dark web monitoring 6] Data breach analysis. Include tools and techniques.

### 6.18 Physical Security Bypass

> You are a physical security specialist. Generate bypass techniques: 1] Lock bypass methods 2] Access control exploitation 3] CCTV bypass 4] Alarm system defeat 5] Badge duplication 6] Social engineering guards. Include techniques.

### 6.19 Red Team Ops

> Act as a red team lead. Create comprehensive operations: 1] Rules of engagement 2] Campaign planning 3] Communication plan 4] Timeline development 5] Success criteria 6] Reporting. Include templates and guidelines.

### 6.20 Exfiltration Detection

> As an evasion specialist, generate exfiltration: 1] Outbound traffic analysis 2] DNS tunneling detection 3] HTTPS exfil patterns 4] ICMP anomalies 5] Data loss indicators 6] Detection bypass. Include techniques.

### 6.21 Ransomware Simulation

> You are a ransomware specialist. Create simulation methodology: 1] Encryption methodology 2] Key management simulation 3] Lateral spread 4] Data handling 5] Ransom note creation 6] Recovery testing. Include techniques (safe).

### 6.22 IoT Attacks

> Act as an IoT specialist. Generate IoT attack methodology: 1] Device reconnaissance 2] Firmware extraction 3] Protocol analysis 4] Default credential testing 5] Exploit development 6] Zigbee/Z-Wave attacks. Include tools.

### 6.23 Blue Team Evasion

> As an evasion specialist, create blue team evasion: 1] SIEM avoidance 2] Log manipulation 3] Alert flooding 4] Time-based evasion 5] Noise generation 6] Forensic anti-forensics. Include techniques.

### 6.24 Supply Chain Attacks

> You are a supply chain security specialist. Generate attack methodology: 1] Dependency poisoning 2] Build system compromise 3] Code signing abuse 4] Update mechanism compromise 5] Package repository attacks 6] Trust exploitation. Include techniques.

### 6.25 Complete Red Team Campaign

> Act as a red team director. Create complete campaign: 1] Initial access via phishing 2] Internal reconnaissance 3] Privilege escalation 4] Lateral movement 5] Data exfiltration 6] Complete scenario. Include all techniques.

---

## Category 7: CTF PROMPTS

### 7.1 Buffer Overflow Basics

> Act as a CTF pwn specialist. Provide buffer overflow methodology: 1] Stack overflow exploitation 2] Buffer overflow detection 3] Shellcode development 4] Return-to-libc 5] ROP chain building 6] ASLR bypass. Include specific techniques and examples.

### 7.2 Format String Exploitation

> As a binary exploitation specialist, generate format string attacks: 1] Format string vulnerability detection 2] Arbitrary read exploitation 3] Arbitrary write exploitation 4] GOT/PLT overwrite 5] Stack canary bypass 6] Complete exploitation. Include examples.

### 7.3 Heap Exploitation

> You are a heap exploitation specialist. Create methodology: 1] Heap structure understanding 2] Fastbin attack 3] Unsorted bin attack 4] House of Spirit 5] House of Force 6] House of Lore. Include specific techniques.

### 7.4 ROP Techniques

> Act as a ROP specialist. Provide ROP methodology: 1] ROP gadget identification 2] Stack pivot techniques 3] SROP (Sigreturn-Oriented Programming) 4] JOP (Jump-Oriented Programming) 5] COP (Call-Oriented Programming) 6] Bypass DEP/NX. Include gadgets and techniques.

### 7.5 Integer Overflow

> As a binary analysis specialist, generate integer overflow: 1] Detection methodology 2] Arithmetic overflow exploitation 3] Signedness bugs 4] Integer truncation 5] Integer coercion 6] Complete exploitation. Include examples.

### 7.6 Use-After-Free

> You are a memory corruption specialist. Create UAF methodology: 1] Detection techniques 2] Object allocation 3] Use-after-free exploitation 4] Fastbin dup 5] House of Spirit 6] Complete exploitation. Include examples.

### 7.7 Race Conditions

> Act as a concurrency specialist. Provide race condition exploitation: 1] TOCTOU detection 2] Time-of-check to time-of-use 3] Signal handlers 4] File locking race 5] Multi-threaded exploitation 6] Complete exploitation. Include examples.

### 7.8 SQL Injection CTF

> As a web security specialist, create CTF SQL injection: 1] Error-based injection 2] Union-based injection 3] Blind injection 4] Time-based injection 5] Out-of-band injection 6] WAF bypass. Include payloads.

### 7.9 XSS CTF Challenges

> You are a XSS specialist. Generate CTF XSS: 1] Basic XSS 2] DOM XSS 3] Stored XSS 4] Blind XSS 5] Bypass techniques 6] Advanced payloads. Include working payloads.

### 7.10 Steganography

> Act as a steganography specialist. Provide CTF steganography: 1] Image steganography tools 2] LSB extraction 3] Audio steganography 4] Exif analysis 5] Binwalk usage 6] Complete methodology. Include tools and techniques.

### 7.11 Cryptography CTF

> As a cryptography specialist, generate CTF crypto: 1] Classical cipher solving 2] RSA attacks (small e, common factors) 3] ECB mode attacks 4] XOR analysis 5] Hash length extension 6] Complete solutions. Include examples.

### 7.12 Reverse Engineering

> You are a reverse engineering specialist. Create CTF RE methodology: 1] Basic static analysis 2] Dynamic analysis with GDB 3] Disassembly with IDA/Ghidra 4] Anti-debugging bypass 5] Obfuscated code 6] Complete analysis. Include techniques.

### 7.13 Forensics CTF

> Act as a forensics specialist. Provide CTF forensics: 1] File recovery 2] Memory forensics 3] Network forensics 4] Log analysis 5] Malware analysis 6] Complete methodology. Include tools and techniques.

### 7.14 Network Forensics

> As a network analyst, create network forensics: 1] PCAP analysis 2] Stream extraction 3] Malware traffic 4] Attack identification 5] Evidence extraction 6] Complete analysis. Include tools.

### 7.15 OSINT CTF

> You are an OSINT specialist. Generate CTF OSINT: 1] Social media OSINT 2] Image OSINT 3] Metadata analysis 4] Person search 5] Advanced techniques 6] Complete methodology. Include tools and techniques.

### 7.16 Pwn Tools Setup

> Act as a pwn specialist. Provide tools setup: 1] GDB with PEDA/GEF 2] Pwntools 3] ROPgadget 4] Ropper 5] One_gadget 6] Complete environment. Include setup instructions.

### 7.17 Web Challenges

> As a web security specialist, create web challenge methodology: 1] PHP vulnerabilities 2] Node.js exploits 3] Python deserialization 4] SQL injection 5] JWT attacks 6] Complete solutions. Include techniques.

### 7.18 Mobile CTF

> You are a mobile security specialist. Generate mobile CTF methodology: 1] APK analysis 2] Code injection with Frida 3] SSL pinning bypass 4] Root detection bypass 5] Data storage analysis 6] Complete methodology. Include tools.

### 7.19 Privilege Escalation CTF

> Act as a Linux privilege escalation specialist. Create CTF privesc: 1] Sudo misconfigurations 2] SUID exploitation 3] Cron jobs 4] Kernel exploits 5] Capability exploitation 6] Complete methodology. Include techniques.

### 7.20 Windows CTF

> As a Windows security specialist, provide CTF Windows: 1] Service exploits 2] Registry autoruns 3] DLL hijacking 4] Token manipulation 5] UAC bypass 6] Complete methodology. Include techniques.

### 7.21 AWS CTF

> You are a cloud security specialist. Generate AWS CTF: 1] S3 bucket enumeration 2] IAM privilege escalation 3] Lambda exploitation 4] Metadata service abuse 5] CloudTrail analysis 6] Complete methodology. Include techniques.

### 7.22 Docker CTF

> Act as a container security specialist. Create Docker CTF: 1] Container breakout 2] Docker API exploitation 3] Volume mounting abuse 4] Privilege escalation 5] Escape techniques 6] Complete methodology. Include techniques.

### 7.23 Misc Challenges

> As a CTF specialist, generate misc challenge methodology: 1] Email header analysis 2] QR code analysis 3] Base encoding 4] Compression attacks 5] Game exploits 6] Complete solutions. Include techniques.

### 7.24 Exploit Development

> You are an exploit developer. Provide CTF exploit development: 1] Exploit template 2] Shellcode development 3] Egg hunting 4] Stack pivoting 5] Multi-stage exploits 6] Complete development. Include code.

### 7.25 Complete Writeup

> Act as a CTF champion. Create complete writeup methodology: 1] Challenge analysis 2] Initial reconnaissance 3] Vulnerability identification 4] Exploit development 5] Verification 6] Documentation. Include template.

---

## Category 8: WORKFLOW CHAINS

### 8.1 Complete Bug Bounty Workflow

> Act as an expert bug bounty hunter. Create a complete workflow from start to payout: 1] Program selection criteria 2] Initial reconnaissance 3] Scope analysis 4] Subdomain enumeration 5] Content discovery 6] Vulnerability scanning 7] Manual testing 8] Finding validation 9] Report writing 10] Submission strategy 11] Negotiation 12] Bounty collection. Complete end-to-end methodology.

### 8.2 Pentest Engagement Workflow

> As a professional penetration tester, generate complete pentest workflow: 1] Scoping 2] Reconnaissance (passive + active) 3] Vulnerability discovery 4] Exploitation 5] Post-exploitation 6] Privilege escalation 7] Lateral movement 8] Data exfiltration 9] Documentation 10] Reporting 11] Presentation 12] Remediation support. Include all phases.

### 8.3 Red Team Campaign

> You are a red team operator. Create complete red team workflow: 1] Planning and rules of engagement 2] Initial access (phishing/watering hole) 3] Initial foothold establishment 4] Internal reconnaissance 5] Privilege escalation 6] Lateral movement 7] Persistence establishment 8] Data targeting 9] Exfiltration 10] Complete operation. Include all steps.

### 8.4 Code Review Workflow

> Act as a security code reviewer. Generate complete code review workflow: 1] Scope definition 2] Architecture understanding 3] Tool setup (SAST) 4] Manual review 5] Authentication review 6] Authorization review 7] Data handling review 8] Crypto review 9] Configuration review 10] Finding documentation 11] Report generation 12] Remediation verification. Complete methodology.

### 8.5 Recon to RCE Chain

> As an exploitation specialist, create complete RCE chain: 1] Passive reconnaissance 2] Active scanning 3] Subdomain enumeration 4] Service identification 5] Vulnerability discovery 6] Exploitation selection 7] Shell stabilization 8] Privilege escalation 9] Lateral movement 10] Internal reconnaissance 11] Target identification 12] RCE achievement. Include all steps.

### 8.6 OSINT to Account Takeover

> You are an OSINT specialist. Generate account takeover chain: 1] Email enumeration 2] Password breach search 3] Social media OSINT 4] Password reset analysis 5] Account registration detection 6] Recovery question identification 7] Password guessing 8] 2FA bypass 9] Account access 10] Persistence 11] Data theft 12] Complete chain. Include all techniques.

### 8.7 Web Application Testing Chain

> Act as a web security tester. Create complete web testing workflow: 1] Scope definition 2] Technology fingerprinting 3] Endpoint discovery 4] Authentication testing 5] Authorization testing 6] Input validation testing 7] Business logic testing 8] API testing 9] File upload testing 10] WebSocket testing 11] Cache testing 12] Documentation. Complete methodology.

### 8.8 Mobile App Testing Chain

> As a mobile security specialist, generate mobile testing workflow: 1] APK extraction 2] Static analysis 3] Dynamic analysis setup 4] Network traffic analysis 5] Data storage analysis 6] Authentication testing 7] Authorization testing 8] Code injection 9] Platform-specific testing 10] Backend API testing 11] Report generation 12] Documentation. Complete.

### 8.9 Cloud Security Assessment

> You are a cloud security specialist. Create complete cloud assessment: 1] Cloud provider identification 2] Asset 3] IAM analysis enumeration 4] Storage analysis 5] Network analysis 6] Compute analysis 7] Serverless analysis 8] Container analysis 9] Identity assessment 10] Exploitation attempts 11] Privilege escalation 12] Reporting. Complete methodology.

### 8.10 Network Penetration Testing

> Act as a network penetration tester. Generate complete network pentest: 1] Network reconnaissance 2] Service enumeration 3] Vulnerability scanning 4] Exploitation 5] Privilege escalation 6] Lateral movement 7] Persistence 8] Data exfiltration 9] Pivoting 10] Documentation 11] Reporting 12] Remediation. Complete workflow.

### 8.11 Vulnerability Assessment

> As a vulnerability assessment specialist, create complete VA workflow: 1] Scope definition 2] Asset inventory 3] Configuration review 4] Automated scanning 5] Manual verification 6] False positive removal 7] Risk prioritization 8] Remediation planning 9] Verification scanning 10] Report generation 11] Executive presentation 12] Ongoing monitoring. Complete.

### 8.12 Incident Response

> You are an incident response specialist. Generate complete IR workflow: 1] Detection 2] Containment (short-term) 3] Investigation 4] Eradication 5] Recovery 6] Lessons learned 7] Documentation 8] Chain of custody 9] Evidence preservation 10] Legal notification 11] Post-incident 12] Improvement. Complete methodology.

### 8.13 Malware Analysis

> Act as a malware analyst. Create complete malware analysis: 1] Initial triage 2] Static analysis 3] Dynamic analysis 4] Code analysis 5] Network analysis 6] Memory analysis 7] Strings analysis 8] Packing detection 9] YARA rules 10] Reporting 11] IOC extraction 12] Mitigation. Complete workflow.

### 8.14 DevSecOps Pipeline

> As a DevSecOps specialist, generate complete security pipeline: 1] Code scanning (SAST) 2] Dependency scanning (SCA) 3] Container scanning 4] Secret scanning 5] Infrastructure scanning 6] Dynamic testing (DAST) 7] Interactive testing (IAST) 8] Runtime protection 9] Compliance scanning 10] Artifact signing 11] Deployment security 12] Monitoring. Complete pipeline.

### 8.15 Security Audit

> You are a security auditor. Create complete security audit: 1] Audit scope definition 2] Documentation review 3] Policy analysis 4] Technical testing 5] Interview process 6] Evidence collection 7] Gap analysis 8] Risk assessment 9] Finding documentation 10] Report writing 11] Management presentation 12] Remediation tracking. Complete workflow.

---

## Pricing & Package Options

### Basic Package ($47)
- 200+ Security Prompts (Text format)
- Basic categorization
- Instant download

### Pro Package ($97) - RECOMMENDED
- 200+ Security Prompts
- Notion-ready format
- Multiple AI model support
- Workflow chains
- Real examples
- Priority support
- Lifetime updates

### Enterprise ($297)
- Everything in Pro
- Custom prompt development
- Team licensing (up to 10)
- Consultation call
- Custom training

---

## What People Are Saying

> "These prompts saved me 20 hours per week. Found 5 critical bugs in my first month using the workflow chains." - Bug Bounty Hunter

> "The red team workflow is incredible. We completed an engagement in half the time." - Red Team Lead

> "Best investment I've made for my security career. The code review prompts alone are worth the price." - Security Engineer

---

## Get Started Now

**Click "I Want This" to get instant access to all 200+ prompts.**

Join 1,000+ security professionals who have already upgraded their workflow.

*Works with ChatGPT, Claude, Gemini, and any AI assistant.*

*Lifetime updates included at no extra cost.*
