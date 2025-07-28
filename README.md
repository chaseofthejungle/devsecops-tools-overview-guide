# DevSecOps Tools Overview Guide

(TODO: Finish descriptions of tool categories and individual technologies.)

#### Table of Contents

1. [Static Application Security Testing (SAST)](#sast)
2. [Dynamic Application Security Testing (DAST)](#dast)
3. [Software Composition Analysis (SCA)](#sca)
4. [Secret Management](#secman)
5. [Secret Scanning](#secscan)
6. [Binary/Image Scanning](#binimg)
7. [Artifact Scanning](#artscan)
8. [Environment and IaC (Infrastructure as Code) Security](#enviac)
9. [Vulnerability Management](#vulman)
10. [Compliance as Code (CaC)](#compcode)
11. [Supplemental Resources](#supplemental)

## 1. <a name="sast">Static Application Security Testing (SAST)</a>

*Static Application Security Testing (SAST)* tools can prevent security issues by detecting vulnerabilities early. They perform automated scanning, evaluate source code, and assure that standards and compliance are enforced. This can keep the costs of systems remediation low.

*Examples of open-source tools include:*

* **Bandit**
* **Brakeman**
* **ESLint**
* **GitLab SAST**
* **SonarQube**

<hr />
  
## 2. <a name="dast">Dynamic Application Security Testing (DAST)</a>

*DAST (Dynamic Application Security Testing)* tools evaluate for external vulnerabilities (e.g., secure data exposures, SQL injection) in presently running apps (in realtime), reducing the possibilities of data breaches and exploits by threat actors. They conduct black box tests, evaluate environments for misconfigurations, missing configurations, and present threats, and evaluate business logic.

*Examples of open-source tools include:*

* **Arachni**
* **Nikto**
* **SQLMap**
* **ZAProxy (OWASP Zed Attack Proxy)**

<hr />
  
## 3. <a name="sca">Software Composition Analysis (SCA)</a>
  
*Examples of open-source tools include:*

* **OWASP Dependency-Check**
* **Snyk**
* **Trivy**

<hr />
  
## 4. <a name="secman">Secret Management</a>
  
*Examples of open-source tools include:*

* **Bitwarden**
* **Conjur**
* **HashiCorp Vault**
* **Keywhiz**

<hr />
  
## 5. <a name="secscan">Secret Scanning</a>
  
*Examples of open-source tools include:*

* **Detect Secrets**
* **GitLeaks**
* **TruffleHog**

<hr />
  
## 6. <a name="binimg">Binary/Image Scanning</a>
  
*Examples of open-source tools include:*

* **Anchore Engine**
* **Clair**
* **Grype**
* **Trivy**

<hr />
  
## 7. <a name="artscan">Artifact Scanning</a>
  
*Examples of open-source tools include:*

* **Anchore Engine**
* **Clair**
* **Dependency-Track**
* **Grype**
* **OWASP Dependency-Check**
* **Trivy**

<hr />
  
## 8. <a name="enviac">Environment and IaC (Infrastructure as Code) Security</a>
  
*Examples of open-source tools include:*

* **Checkov**
* **Kubescape**
* **Terrascan**
* **tfsc**

<hr />
  
## 9. <a name="vulman">Vulnerability Management</a>

*Examples of open-source tools include:*
  
* **Clair**
* **Nessus Essentials**
* **OpenVAS**

<hr />
  
## 10. <a name="compcode">Compliance as Code (CaC)</a>
  
*Examples of open-source tools include:*

* **Ansible**
* **InSpec**
* **Lynis**
* **OpenScap**
* **OSSECs**
  
<hr />
  
## 11. <a name="supplemental">Supplemental Resources</a>

* *[AWS Article: What is DevSecOps?](https://aws.amazon.com/what-is/devsecops/)*
* *[IBM Article: What is DevSecOps?](https://www.ibm.com/think/topics/devsecops)*
* *[Red Hat Article: What is DevSecOps?](https://www.redhat.com/en/topics/devops/what-is-devsecops)*
