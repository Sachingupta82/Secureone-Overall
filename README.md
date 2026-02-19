# SecureOne

SecureOne is an automated security orchestration platform designed to help developers, freelancers, and businesses identify and remediate security vulnerabilities( specially owasp top 10 vulnerability ). In an era where applications are built rapidly through vibe coding and freelance development, security is often overlooked or poorly implemented. SecureOne ensures that applications are comprehensively tested against a wide range of vulnerabilities and provides automated fixes that integrate directly into development workflows.

---

## Screenshots

<div align="center">
  <table>
    <tr>
      <td><img src="https://drive.google.com/uc?export=view&id=1_3BOWXDrd5t0Bvu1VlHC76r2ULQUYw4e" width="100%" alt="Home Screen" /></td>
      <td><img src="https://drive.google.com/uc?export=view&id=191OZyyboRmRHNCBZFNQyBbqEXjMVBcmR" width="100%" alt="Screenshot 1" /></td>
      <td><img src="https://drive.google.com/uc?export=view&id=1tzFuYHYkT4-ZybnZqoFQ0goAD6OrQonx" width="100%" alt="Screenshot 2" /></td>
    </tr>
    <tr>
      <td><img src="https://drive.google.com/uc?export=view&id=1_Qxj7eJhYnZd3Zu2xPhPJC4HOY5zGasY" width="100%" alt="Screenshot 3" /></td>
      <td><img src="https://drive.google.com/uc?export=view&id=12_oE_ffR0UadhJ6H3FbxwsQmAOdc5ecs" width="100%" alt="Screenshot 4" /></td>
      <td><img src="https://drive.google.com/uc?export=view&id=1-dDIWUiIsDVIdQqI3Cqts8rpo24PYege" width="100%" alt="Screenshot 5" /></td>
    </tr>
    <tr>
      <td><img src="https://drive.google.com/uc?export=view&id=1fo9q49WJsYLGMRJgBuXPotk9ISWmel3v" width="100%" alt="Screenshot 6" /></td>
      <td><img src="https://drive.google.com/uc?export=view&id=1_OObONtmnkvnzy0BoDAU1rEPwGdBiEOc" width="100%" alt="Screenshot 7" /></td>
      <td></td>
    </tr>
  </table>
</div>

---

## Overview

Modern applications frequently go live with serious security weaknesses (mostly OWASP Top 10 vulnerabilities) including injection flaws, cross-site scripting, broken authentication, and misconfigurations. These vulnerabilities can lead to data breaches, account takeovers, financial losses, and significant reputational damage. The challenge is compounded by the rise of vibe coding where developers prioritize speed over security, and freelance developers who may lack security expertise or skip critical edge cases to meet deadlines.

SecureOne addresses this gap through a unified orchestration platform that combines multiple security testing methodologies into a single, automated workflow. Rather than being just a scanner, SecureOne orchestrates static analysis, dynamic testing, and AI-powered code review to provide comprehensive security coverage with minimal manual effort.

---

## Project Resources

| Resource | Link |
|----------|------|
| 🎥 PPT Explanation Video | [Watch Here](https://drive.google.com/file/d/1uwCqD5R7j1PJO12_RhA0bjXP5vwKk8c0/view?usp=drive_link) |
| 📊 Presentation Slides | [View Slides](https://docs.google.com/presentation/d/1um7TVR6eZdUeLPjO3wwFNSD643aT7DPh/edit?usp=drive_link&ouid=117703724265025809442&rtpof=true&sd=true) |
| 💻 Frontend Code | [GitHub — SecureOne Frontend](https://github.com/Sahil-Kavatkar/SecureOne) |
| ⚙️ Backend Code | [GitHub — SecureOne Backend](https://github.com/Sachingupta82/secure-one-backend) |

---

## Problem Statement

Small and medium enterprise owners who rely on freelance developers for their technology products face a critical challenge. Freelancers, focused on delivering features quickly, often ignore security edge cases, leaving business applications vulnerable to attack. The rise of vibe coding has accelerated this problem, with developers building products rapidly without the security testing that traditional development processes include.

Manual security reviews require specialized expertise and significant time — resources that are rarely available in fast-paced freelance engagements or startup environments. Existing security tools are complex, require deep security knowledge to operate, and produce results that are difficult for non-security professionals to interpret and act upon.

There is a need for an automated, comprehensive, and developer-friendly security platform that:

- Orchestrates multiple testing methodologies including static analysis, dynamic testing, and AI-powered code review
- Detects critical security flaws across applications and code repositories
- Generates actionable reports with clear remediation steps
- Provides automated fix code that integrates directly into development workflows
- Adapts dynamically to evolving threats without requiring manual updates
- Makes security testing accessible to non-security professionals

SecureOne addresses this gap through intelligent orchestration of security testing tools and AI-powered analysis.

---

## Core Functionality

SecureOne provides a unified platform that allows users to:

1. Connect a GitHub repository for comprehensive static analysis
2. Provide a deployed web application URL for dynamic testing
3. Upload mobile application files for binary analysis
4. Perform automated security testing across all inputs
5. Receive detailed security reports with severity-based prioritization
6. Obtain AI-generated fix code for identified vulnerabilities
7. Create GitHub issues and pull requests with recommended patches
8. Track security posture over time with historical analysis

All of this is accomplished through a simple, intuitive interface that requires no specialized security expertise and can be completed in just a few clicks.

---

## OWASP Top 10 Coverage

SecureOne efficiently detects and helps remediate all OWASP Top 10 vulnerabilities:

| Rank | Vulnerability | Detection Method |
|------|---------------|------------------|
| A01 | Broken Access Control | SAST patterns + DAST testing |
| A02 | Cryptographic Failures | SAST pattern scanning |
| A03 | Injection | DAST active attacks + SAST patterns |
| A04 | Insecure Design | AI-powered code analysis |
| A05 | Security Misconfiguration | Configuration scanning + DAST |
| A06 | Vulnerable Components | Dependency scanning |
| A07 | Identification Failures | Authentication testing |
| A08 | Software Integrity Failures | Supply chain analysis |
| A09 | Logging Failures | Code pattern analysis |
| A10 | SSRF | DAST attack simulation |

The platform dynamically adapts to changes in the OWASP Top 10 without requiring manual updates, ensuring that scans always reflect the current threat landscape.

---

## How It Works

SecureOne orchestrates multiple security testing methodologies to provide comprehensive coverage of applications and codebases.

### 🔍 Static Application Security Testing (SAST)

SecureOne analyzes source code repositories using over 300 pattern-based detection rules that identify security vulnerabilities, insecure coding practices, and hardcoded secrets. The pattern library covers:

- Frontend vulnerabilities including DOM-based XSS, insecure client-side storage, and CSP misconfigurations
- Backend vulnerabilities including SQL injection, command injection, and authentication flaws
- Mobile application vulnerabilities for both Android and iOS platforms
- Infrastructure as code misconfigurations and cloud security issues
- Dependency vulnerabilities and outdated library detection

The pattern library is dynamically updated based on changes to emerging threat landscapes, ensuring that scans remain current without manual intervention.

### 🌐 Dynamic Application Security Testing (DAST)

For deployed applications, SecureOne orchestrates OWASP ZAP to perform comprehensive dynamic testing that simulates real-world attack scenarios. The testing process includes:

- Application crawling and endpoint discovery through both traditional spiders and AJAX spiders for deep coverage of modern single-page applications
- Passive analysis to identify information disclosure and misconfigurations
- Active attack simulation to identify exploitable vulnerabilities
- Authenticated scanning for applications that require login
- Support for various authentication methods including form-based, header-based, and OAuth

### 🤖 AI-Powered Code Analysis

Beyond pattern-based detection, SecureOne leverages Gemini AI to perform deep semantic analysis of code repositories. The AI engine:

- Identifies complex vulnerabilities that pattern-based detection might miss
- Provides contextual explanations of why code is vulnerable
- Generates secure code fixes that maintain existing functionality
- Maps vulnerabilities to specific lines in source files
- Adapts to new vulnerability types without requiring rule updates

### 📱 Binary Analysis

For mobile applications, SecureOne orchestrates jadx and MobSF to decompile and analyze APK and AAB files. This provides visibility into:

- Manifest file vulnerabilities and permission misconfigurations
- Hardcoded secrets and API keys in binary code
- Insecure data storage practices
- Network security misconfigurations
- Code obfuscation and anti-tampering weaknesses

### 🔧 Automated Remediation

The platform goes beyond detection by providing actionable remediation:

- AI-generated fix code that directly addresses identified vulnerabilities
- GitHub issue creation with detailed vulnerability descriptions and severity ratings
- Pull request generation with ready-to-merge fix code
- Integration with existing development workflows

---

## Vulnerabilities Covered

SecureOne detects vulnerabilities aligned with the OWASP Top 10 and beyond, including:

- Injection (SQL Injection, NoSQL Injection, Command Injection, Code Injection)
- Cross-Site Scripting (XSS) including reflected, stored, and DOM-based variants
- Broken Access Control including IDOR and privilege escalation
- Security Misconfiguration including CORS, CSP, and header issues
- Sensitive Data Exposure including hardcoded secrets and PII
- Authentication and Session Failures including JWT weaknesses and session fixation
- Cross-Site Request Forgery (CSRF)
- Insecure Dependencies and outdated libraries
- Path Traversal and file inclusion vulnerabilities
- XXE and XML-based attacks
- SSRF and server-side request forgery
- Insecure Deserialization
- Business logic flaws and race conditions
- Mobile-specific vulnerabilities including exported activities, insecure storage, and certificate pinning issues

---

## Key Features

| Feature | Description |
|---------|-------------|
| 🔗 Unified Orchestration | SAST, DAST, and AI-powered analysis in a single platform |
| ⚡ 3-Click Workflow | Complete detection to remediation in three simple steps |
| 📋 300+ Detection Rules | Comprehensive pattern-based vulnerability coverage |
| 🧠 AI Code Analysis | Deep semantic vulnerability detection via Gemini AI |
| 🔄 Dynamic Adaptation | Auto-updates to reflect latest OWASP Top 10 changes |
| 🐙 GitHub Integration | Seamless repository access and one-click PR creation |
| 📱 Mobile Binary Analysis | APK/AAB analysis through jadx decompilation |
| 🕷️ Deep Spidering | Traditional and AJAX crawling for modern SPAs |
| 🛠️ Auto Fix Generation | Line-specific fix recommendations with merge-ready code |
| 📊 Severity Reporting | Prioritized findings with historical posture tracking |

---

## Business Model

SecureOne operates on a simple, transparent credit-based model.

### Free Trial Credits

New users receive **100 free credits** upon signing up, allowing them to experience the platform's capabilities before making any purchase decision. This provides ample opportunity to scan small projects and evaluate the quality of findings and fix recommendations.

### Credit Usage

Credits are consumed for all actions performed on the platform — web scans, mobile scans, repository scans, AI analysis, fix generation, and GitHub integration features.

### Credit Purchase Plans

| Plan | Credits | Price |
|------|---------|-------|
| 🚀 Starter | 1,000 credits | $5 |
| 💼 Professional | 5,000 credits | $20 |

> Purchased credits **do not expire**, allowing users to maintain a balance for occasional scanning needs.

---

## Target Users

- 🏢 **SME Owners** — Need assurance that freelance-built products are secure before going live
- 👨‍💻 **Freelance Developers** — Want to validate deliverables and differentiate through secure development
- ⚡ **Vibe Coders** — Building rapidly without time for comprehensive manual security testing
- 🚀 **Startups** — Launching MVPs who need basic security assurance before customer exposure
- 🛡️ **Dev Teams** — Preparing applications for production deployment
- 🎓 **Educational Institutions** — Teaching secure development practices
- 🔎 **Bug Bounty Hunters** — Conducting security assessments efficiently

---

## Technology Stack

| Layer | Technology |
|-------|------------|
| Backend | Node.js with Express |
| Database | MongoDB with Mongoose ODM |
| Static Analysis | Custom pattern engine with 300+ rules |
| Dynamic Analysis | OWASP ZAP with authenticated scanning |
| AI Analysis | Google Gemini AI |
| Mobile Analysis | jadx + MobSF |
| GitHub Integration | Octokit |
| Real-time Updates | Socket.io |
| Frontend | React with Tailwind CSS |

---

## Why SecureOne

Traditional security testing requires specialized expertise, multiple tools, and significant manual effort. SecureOne eliminates these barriers through:

- **Orchestration, not just scanning** — Multiple methodologies unified into a single workflow
- **Complete remediation** — We don't just tell you what's wrong, we show you how to fix it
- **Accessibility** — No security expertise required to run comprehensive tests
- **Integration** — Direct GitHub integration means fixes can be applied with a single click
- **Currency** — Dynamic adaptation ensures you're always testing against current threat landscapes
- **Coverage** — From source code to running applications to mobile binaries, we test everything
- **Simplicity** — The entire process from scan initiation to fix application takes minutes, not days

---

## Getting Started

1. Sign up for a SecureOne account and receive **100 free credits** immediately
2. Connect your GitHub repositories through the simple OAuth flow
3. Configure your first scan by providing a target URL or selecting a repository
4. Choose the appropriate scan type based on your application architecture
5. Monitor progress through the live terminal interface
6. Review findings with severity-based prioritization
7. Generate and apply fixes with one-click GitHub integration
8. Track your security posture over time through the dashboard

> The entire process from scan initiation to fix application takes **minutes, not days**, and requires no specialized security knowledge.

---

<div align="center">

Thank you for visiting our project!
We hope SecureOne demonstrates how security testing can be made **simple, accessible, and actionable** for everyone.

</div>
