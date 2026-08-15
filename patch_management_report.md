# Task 6 – The Importance of Patch Management

## Introduction

Patch management is basically the process of keeping software and systems updated. Companies release patches when they find security problems, bugs or other issues in their software.

It is an important part of vulnerability management because a vulnerability can stay open until the organisation fixes it. If a system is left unpatched, an attacker may be able to take advantage of the vulnerability.

When a vulnerability is publicly identified, it can be given a CVE number. This gives security teams a standard way of identifying and keeping track of known vulnerabilities.

## Why Patches Matter

Patches are important because attackers can take advantage of vulnerabilities that are already known. In some cases, a security update may already be available when an attack happens, but the organisation has not installed it yet.

### WannaCry

A good example is the WannaCry ransomware attack in 2017. WannaCry used a vulnerability in Microsoft's SMB protocol to spread between vulnerable Windows computers.

Microsoft had already released a security update for the vulnerability before the attack. However, many systems had not been updated.

The attack caused problems for organisations around the world, including parts of the UK's National Health Service.

This shows that releasing a patch is not enough. Organisations also need to make sure that the patch actually gets installed.

### Equifax

The Equifax breach in 2017 is another example of what can happen when a known vulnerability is not fixed.

The attackers exploited a vulnerability in Apache Struts. Equifax had been told about the vulnerability and affected systems were supposed to be patched, but one of the vulnerable systems was missed.

The attackers were then able to gain access to the company's systems and personal information was exposed.

The incident also resulted in a large settlement and caused serious damage to the company's reputation.

## Consequences of Not Patching

Not keeping systems updated can cause several problems:

- Data can be stolen.
- Attackers can install malware or ransomware.
- Systems can become unavailable.
- Businesses can lose money because of downtime and recovery costs.
- Customers can lose trust in the organisation.
- Organisations can face legal or compliance problems.

The cost of dealing with a cyberattack can also be much higher than the cost of keeping systems properly maintained.

## Patch Management Lifecycle

A simple patch management process can be divided into five stages.

### 1. Discovery

The organisation needs to know what systems and software it has.

This includes computers, servers, applications and network devices.

If an organisation does not know that a system exists, it is easy for that system to be missed when patches are being installed.

### 2. Assessment

The organisation checks which vulnerabilities affect its systems.

The security team then decides which vulnerabilities need to be dealt with first. A vulnerability affecting an internet-facing server would normally receive more attention than a low-risk issue on an isolated computer.

### 3. Testing

The patch should be tested before it is installed everywhere.

This is important because an update can sometimes cause compatibility problems or affect an application that the organisation depends on.

### 4. Deployment

After testing, the patch can be installed on the affected systems.

Critical vulnerabilities should be dealt with quickly, especially when attackers are already using them.

### 5. Verification

After the patch has been installed, the organisation needs to check that it worked.

This can be done by checking software versions, using vulnerability scanners or checking the organisation's patch-management system.

## 7-Step Patch Management Checklist

1. Keep an up-to-date list of all systems and software.
2. Monitor for new vulnerabilities and security updates.
3. Prioritise the most serious vulnerabilities.
4. Test important patches before deploying them.
5. Install patches within the required timeframe.
6. Check that the patches were installed successfully.
7. Keep records of the patching process.

CISA's Known Exploited Vulnerabilities Catalog can also be used to help identify vulnerabilities that are already being used by attackers.

## Challenges of Patch Management

### Legacy Systems

Some organisations still use old systems that may no longer receive updates.

One way of dealing with this is to replace unsupported systems. If that is not possible immediately, the system can be isolated and given limited network access.

### Downtime

Organisations may avoid installing updates because they are worried about interrupting important services.

Maintenance periods can be planned so that updates are installed when they will have the least impact.

### Testing

Some patches can cause problems with existing applications.

Using a test environment before deploying the patch to all systems can help find these problems.

### Too Many Vulnerabilities

Large organisations can have a lot of vulnerabilities to deal with at the same time.

Instead of trying to fix everything at once, they can prioritise vulnerabilities based on their severity and the risk they pose.

### Human Error

A system can sometimes be forgotten or missed during the patching process.

Using automated patching tools and regularly checking reports can help reduce this problem.

## Why Patch Management Should Be Continuous

Patch management should not be something an organisation only does once in a while. New vulnerabilities are discovered regularly, so systems need to be checked and updated on an ongoing basis.

Automation can make this easier, but organisations should still check that updates were installed correctly.

## Conclusion

Patch management is an important part of cybersecurity because it helps organisations deal with known security problems before attackers can take advantage of them.

The WannaCry attack and the Equifax breach are good examples of how serious the results can be when vulnerabilities are not properly dealt with.

A good patching process should involve finding the systems that need updates, checking the risks, testing patches, installing them and making sure they worked.

Patching cannot stop every cyberattack, but it can remove many of the known weaknesses that attackers look for.

#references

1. NIST – Guide to Enterprise Patch Management Planning  
   https://csrc.nist.gov/pubs/sp/800/40/r4/final

2. CISA – Known Exploited Vulnerabilities Catalog  
   https://www.cisa.gov/known-exploited-vulnerabilities-catalog

3. CVE Program – Common Vulnerabilities and Exposures  
   https://www.cve.org/

4. National Audit Office – Investigation: WannaCry cyber attack and the NHS  
   https://www.nao.org.uk/reports/investigation-wannacry-cyber-attack-and-the-nhs/

5. U.S. Government Accountability Office – Data Protection: Actions Taken by Equifax and Federal Agencies in Response to the 2017 Breach  
   https://www.gao.gov/products/gao-18-559

6. Federal Trade Commission – Equifax Settlement Related to 2017 Data Breach  
   https://www.ftc.gov/news-events/news/press-releases/2019/07/equifax-pay-575-million-part-settlement-ftc-cfpb-states-related-2017-data-breach
