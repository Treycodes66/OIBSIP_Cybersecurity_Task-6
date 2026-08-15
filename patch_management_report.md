# Task 6 – The Importance of Patch Management

## Introduction

Patch management is the process of keeping an organisation's software, operating systems and devices up to date. Patches are often released to fix security vulnerabilities, bugs and other problems.

Patch management is an important part of vulnerability management because a vulnerability can remain open until the affected system is patched or another security control is put in place.

A vulnerability can be discovered by researchers, vendors or attackers. Once publicly reported, it can receive a **CVE (Common Vulnerabilities and Exposures)** identifier. Security teams can then use this information to identify affected systems and decide how urgently they need to be fixed.

---

## Why Patches Matter

Unpatched systems are a major security risk because attackers often look for vulnerabilities that are already known and have available exploits.

Two well-known examples are **WannaCry** and the **Equifax data breach**.

### WannaCry

In 2017, the WannaCry ransomware attack spread by exploiting a vulnerability in Microsoft's SMB protocol. Microsoft had already released a security update for the vulnerability before the attack took place.

Many organisations had not installed the update, which allowed WannaCry to spread between vulnerable systems. The UK's National Audit Office reported that the attack affected at least 81 NHS trusts in England.

This shows why installing security patches on time is important. Having a patch available does not help if the organisation does not actually install it.

### Equifax

The 2017 Equifax breach is another example of the risks of poor patch management.

Attackers exploited a vulnerability in Apache Struts. Equifax had been notified about the vulnerability and instructed staff to patch affected systems, but one of the vulnerable systems remained unpatched.

The breach eventually exposed personal information belonging to approximately **145.5 million people**.

The incident shows that organisations need to know which systems they have, which vulnerabilities affect them and whether patches were successfully installed.

---

## Consequences of Not Patching

Failing to patch systems can lead to several problems:

- **Data breaches** – attackers may gain access to personal or confidential information.
- **Ransomware** – vulnerabilities can be used to gain access to systems and deploy ransomware.
- **Financial losses** – organisations may have to pay for recovery, investigation, legal services and downtime.
- **Reputation damage** – customers may lose trust after a security incident.
- **Compliance problems** – organisations may face regulatory action or penalties if they fail to protect sensitive information.
- **Business disruption** – attacks can make important systems unavailable.

The IBM 2025 Cost of a Data Breach Report estimated the global average cost of a data breach at around **US$4.44 million**.

The Equifax settlement also reached up to **US$575 million**, showing how expensive a major security incident can become.

---

## Patch Management Lifecycle

A basic patch management lifecycle can be divided into five stages:

### 1. Discovery

The organisation identifies its computers, servers, applications, network devices and other systems.

It is difficult to patch systems properly if the organisation does not know they exist.

### 2. Assessment

Security teams identify which vulnerabilities affect their systems and decide how serious they are.

Factors such as the vulnerability's severity, whether it is being actively exploited and whether the affected system is exposed to the internet can be considered.

### 3. Testing

The patch is tested before being deployed widely.

Testing helps identify compatibility problems or situations where the update could break an important application.

### 4. Deployment

The patch is installed on the affected systems.

Critical vulnerabilities should be patched as quickly as possible, especially when attackers are already exploiting them.

### 5. Verification

After deployment, the organisation checks whether the patch was actually installed successfully.

Vulnerability scanners, patch-management software and system-version checks can be used for verification.

---

## 7-Step Patch Management Checklist

A practical patch management process can follow these seven steps:

1. **Keep an asset inventory** – know what systems and software the organisation uses.
2. **Monitor for vulnerabilities** – keep track of new CVEs and vendor security updates.
3. **Prioritise risks** – patch critical and actively exploited vulnerabilities first.
4. **Test patches** – check important updates before large-scale deployment.
5. **Deploy patches** – install approved patches within the required timeframe.
6. **Verify the update** – confirm that systems were successfully patched.
7. **Keep records** – document what was patched, when it was patched and any systems that were missed.

CISA's **Known Exploited Vulnerabilities (KEV) Catalog** can help organisations identify vulnerabilities that are already being exploited in the real world.

---

## Challenges of Patch Management

### Legacy Systems

Older systems may no longer receive security updates.

**Solution:** Replace unsupported systems where possible. If replacement is not immediately possible, isolate them and limit network access.

### Downtime

Some organisations delay patches because they are worried about interrupting important services.

**Solution:** Use maintenance windows, backups and staged deployments to reduce the impact of updates.

### Testing

A patch can sometimes cause compatibility problems with existing software.

**Solution:** Test important patches before deploying them to all systems.

### Too Many Vulnerabilities

Large organisations may have hundreds or thousands of vulnerabilities to deal with.

**Solution:** Use risk-based prioritisation instead of treating every vulnerability equally.

### Human Error

Some systems may simply be missed during the patching process.

**Solution:** Use automated patch-management tools and regularly check patching reports.

---

## Why Patch Management Should Be Continuous

Patch management should not be treated as a once-off task. New vulnerabilities are discovered regularly, which means organisations need to continuously monitor, assess and update their systems.

Automation can also help organisations identify missing patches and deploy updates more efficiently. However, important systems still need monitoring and verification to make sure updates were successfully applied.

---

## Conclusion

Patch management is a basic but very important part of cybersecurity. Keeping systems patched reduces the amount of time attackers have to take advantage of known vulnerabilities.

The WannaCry attack and Equifax breach both show what can happen when known vulnerabilities are not properly addressed.

An effective patch management strategy should therefore involve knowing what systems exist, identifying vulnerabilities, prioritising risks, testing patches, deploying them and checking that they were successfully installed.

Patching cannot prevent every cyberattack, but it can significantly reduce the number of known vulnerabilities that attackers can use.

---

## References

1. **NIST** – *Guide to Enterprise Patch Management Planning*  
   https://csrc.nist.gov/pubs/sp/800/40/r4/final

2. **CISA** – *Known Exploited Vulnerabilities Catalog*  
   https://www.cisa.gov/known-exploited-vulnerabilities-catalog

3. **CVE Program** – *Common Vulnerabilities and Exposures*  
   https://www.cve.org/

4. **National Audit Office** – *Investigation: WannaCry cyber attack and the NHS*  
   https://www.nao.org.uk/reports/investigation-wannacry-cyber-attack-and-the-nhs/

5. **U.S. Government Accountability Office** – *Data Protection: Actions Taken by Equifax and Federal Agencies in Response to the 2017 Breach*  
   https://www.gao.gov/products/gao-18-559

6. **Federal Trade Commission** – *Equifax Settlement Related to 2017 Data Breach*  
   https://www.ftc.gov/news-events/news/press-releases/2019/07/equifax-pay-575-million-part-settlement-ftc-cfpb-states-related-2017-data-breach
