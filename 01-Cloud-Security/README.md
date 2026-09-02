# Cloud Security

## Overview

Cloud environments make it easy for organizations to store data and run applications, but a small security mistake can expose important resources.

In this mini-project, I looked at two common cloud security problems: **misconfigured cloud resources** and **weak identity and access controls**. I analyzed how these weaknesses could be exploited and what security measures could be used to reduce the risk.

---

## Objective

To identify common cloud security risks, understand their possible impact, and determine practical security measures that can help protect cloud resources and user access.

---

## Scenario

The scenario is based on a fictional organization, **Secure Systems Inc.**

The organization uses cloud resources and needs to protect them from accidental exposure and unauthorized access.

The main security concerns were:

- Cloud resources being incorrectly configured
- Sensitive storage or databases being exposed
- Users having more permissions than they actually need
- Weak authentication and access controls

---

## What I Analyzed

### 1. Cloud Misconfiguration

A cloud resource may become exposed because of incorrect security settings.

For example:

- A database or storage resource could be made publicly accessible
- Network rules could allow unnecessary access
- Security settings may not be properly enforced

These mistakes can expose sensitive information or give attackers access to cloud resources.

### 2. Weak Identity & Access Controls

Giving users more access than they need increases the damage that can happen if an account is compromised.

Some common weaknesses include:

- Excessive permissions
- No Multi-Factor Authentication (MFA)
- Poorly defined access roles
- Lack of the **Principle of Least Privilege**

The goal is to make sure users only have the access required for their work.

---

## Security Approach

I looked at three main ways to reduce these risks:

### Infrastructure as Code (IaC)

Using predefined and approved configurations can reduce mistakes when cloud resources are created.

For example, security settings such as private storage and restricted network access can be included in standard templates.

### Cloud Security Posture Management (CSPM)

CSPM can continuously check cloud environments for security problems such as exposed resources or incorrect configurations.

This helps organizations find configuration issues before they become serious security incidents.

### Identity & Access Management (IAM)

IAM controls who can access cloud resources and what they are allowed to do.

Applying **least privilege** helps limit unnecessary access and reduces the impact of compromised accounts.

---

## Key Findings

- A simple cloud configuration mistake can expose sensitive resources.
- Weak access controls can make a compromised account much more dangerous.
- Least privilege helps limit unnecessary access.
- IaC can reduce repeated configuration mistakes.
- CSPM helps continuously identify security issues.
- Cloud security needs both **secure configurations and strong identity controls**.

---

## Skills & Concepts Applied

- Cloud Security
- Cloud Infrastructure Threat Analysis
- IAM
- Principle of Least Privilege
- Infrastructure as Code (IaC)
- Cloud Security Posture Management (CSPM)
- Security Misconfiguration Analysis
- Access Control
- Risk Identification & Mitigation

---

## What I Learned

This project helped me understand that cloud security is not only about protecting the cloud itself. **How resources are configured and who can access them are equally important.**

I learned how misconfigurations and excessive permissions can create security risks, and how IAM, least privilege, IaC, and CSPM can work together to reduce those risks.

---

## Conclusion

A cloud environment can be secure at one level and still be vulnerable because of a simple configuration or access-control mistake.

This exercise showed me how important it is to combine **secure configurations, controlled access, and continuous monitoring** when protecting cloud resources.
