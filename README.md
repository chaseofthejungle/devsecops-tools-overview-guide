# DevSecOps Tools Overview Guide

**Description/Overview:** *DevSecOps* is the active integration of DevOps workflows and security tools, based on process changes. Similarly, *AppSec Posture Management (ASPM)* concerns evaluations of security signals across the Systems Development Life Cycle (SDLC) to handle vulnerabilities, apply security controls, and increase transparency. The implementation of systems-integrated and automated DevSecOps tools strengthens the security posture of systems/apps, providing protection against cyber attacks.

#### Table of Contents

1. [Why Use Open-Source Security Tools?](#whyuse)
2. [Static Application Security Testing (SAST)](#sast)
3. [Dynamic Application Security Testing (DAST)](#dast)
4. [Software Composition Analysis (SCA)](#sca)
5. [Secret Management](#secman)
6. [Secret Scanning](#secscan)
7. [Binary/Image Scanning](#binimg)
8. [Software Artifact Scanning](#artscan)
9. [Environment and Infrastructure-as-Code (IaC) Security](#enviac)
10. [Vulnerability Management](#vulman)
11. [Compliance as Code (CaC)](#compcode)
12. [Supplemental Resources](#supplemental)

<hr />

## 1. <a name="whyuse">Why Use Open-Source Security Tools?</a>

* **Community-Supported**: Members of open-source communities (e.g., forums, social media) can quickly provide advice and knowledge of how to integrate and optimize open-source (OS) tools.
* **Highly Customizable**: Open-source tools can be flexibly integrated into current workflows and project specifications.
* **Instant Visibility**: Codebases are transparent/completely visible, empowering developers to learn the functionality and operations of tools.
* **Low Costs**: Open-source tools are usually free to acquire, with source code readily accessible, modifiable, and permitted to be rereleased with changes.

<hr />

## 2. <a name="sast">Static Application Security Testing (SAST)</a>

*Static Application Security Testing (SAST)* tools can prevent security issues by detecting vulnerabilities early. They perform automated scanning, evaluate source code, and assure that standards and compliance are enforced. This can keep the costs of systems remediation low.

*Examples of open-source tools include:*

* **Bandit**
* **Brakeman**
* **ESLint**
* **GitLab SAST**
* **SonarQube**

<hr />
  
## 3. <a name="dast">Dynamic Application Security Testing (DAST)</a>

*DAST (Dynamic Application Security Testing)* tools evaluate for external vulnerabilities (e.g., secure data exposures, SQL injection) in presently running apps (in realtime), reducing the possibilities of data breaches and exploits by threat actors. They conduct black box tests, evaluate environments for misconfigurations, missing configurations, and present threats, and evaluate business logic.

*Examples of open-source tools include:*

* **Arachni**
* **Nikto**
* **SQLMap**
* **ZAProxy (OWASP Zed Attack Proxy)**

<hr />
  
## 4. <a name="sca">Software Composition Analysis (SCA)</a>

*Software Composition Analysis (SCA)* tools help keep apps secure and compliant by analyzing open-source dependencies for dependency management, licensure, policy enforcement, risk assessment, security alert/notification, and other vulnerabilities. They scan third party components, package manifests, and software libraries in doing so.

*Examples of open-source tools include:*

* **OWASP Dependency-Check**
* **Snyk**
* **Trivy**

<hr />
  
## 5. <a name="secman">Secret Management</a>

*Secret management* tools are essential for protecting management of, authorization for access control to, and storage of, sensitive information and credentials for apps, users, and services. Examples of such data/credentials include: Personally Identifiable Information (PII), passwords, certificates, and API and encryption keys. Mechanisms such as dynamic secret generation, automated secret rotation, and Command Line Interface (CLI) access control can assist secret management tools in their efficacy.

*Examples of open-source tools include:*

* **Bitwarden**
* **Conjur**
* **HashiCorp Vault**
* **Keywhiz**

<hr />
  
## 6. <a name="secscan">Secret Scanning</a>

*Secret scanning* tools continuously search for and recognize secrets, such as API and encryption keys, certificates, passwords, and tokens, that are present within config files, repositories, and program source code. These secrets are commonly accidentally hard coded and made publicly available by data stewards and organizations.

*Examples of open-source tools include:*

* **Detect Secrets**
* **GitLeaks**
* **TruffleHog**

<hr />
  
## 7. <a name="binimg">Binary/Image Scanning</a>

*Binary and image scanner tools* evaluate compiled binaries, container images, and containerized applications for faulty configurations and compliances, malware, and any other vulnerabilities.

*Examples of open-source tools include:*

* **Anchore Engine**
* **Clair**
* **Grype**
* **Trivy**

<hr />
  
## 8. <a name="artscan">Software Artifact Scanning</a>

*Software artifact scanner tools* integrate with software artifact repositories to perform extensive scanning and monitoring for licensing and compliance issues, quality assurance, and security-related vulnerabilities.

*Examples of open-source tools include:*

* **Anchore Engine**
* **Clair**
* **Dependency-Track**
* **Grype**
* **OWASP Dependency-Check**
* **Trivy**

<hr />
  
## 9. <a name="enviac">Environment and Infrastructure-as-Code (IaC) Security</a>

*Environment and Infrastructure-as-Code (IaC) security tools* perform automated/autonomous security checks, monitoring the environments and infrastructures surrounding deployed apps and assuring resilence and compliance with organizational security policies and external, industry-wide regulatory standards.

*Examples of open-source tools include:*

* **Checkov**
* **Kubescape**
* **Terrascan**
* **tfsc**

<hr />
  
## 10. <a name="vulman">Vulnerability Management</a>

*Examples of open-source tools include:*
  
* **Clair**
* **Nessus Essentials**
* **OpenVAS**

<hr />
  
## 11. <a name="compcode">Compliance as Code (CaC)</a>
  
*Examples of open-source tools include:*

* **Ansible**
* **InSpec**
* **Lynis**
* **OpenScap**
* **OSSECs**
  
<hr />
  
## 12. <a name="supplemental">Supplemental Resources</a>

* *[AWS Article: What is DevSecOps?](https://aws.amazon.com/what-is/devsecops/)*
* *[IBM Article: What is DevSecOps?](https://www.ibm.com/think/topics/devsecops)*
* *[Red Hat Article: What is DevSecOps?](https://www.redhat.com/en/topics/devops/what-is-devsecops)*
