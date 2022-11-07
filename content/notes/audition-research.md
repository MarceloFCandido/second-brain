---
title: "audition-research"
tags:
- 
enableToc: false
---

In a [system audition](notes/system-auditing.md), after [gathering information](notes/audition-reconnaissance.md) about the system, as the [ethical hacker](notes/ethical-hacking) knows the [vulnerabilities](notes/vulnerability.md) of the [scope](notes/test-scope.md), the professional must find the [exploits](notes/exploit.md) for which of those are viable on the investigated systems (as not every vulnerability found is exploitable).

The know vulnerabilities are the focus in this phase, as they are more exploitable;
The companies assign an ID for its products' vulnerabilities know globally.
This ID is the 
	-> CVE (Common Vulnerability Exposure)
		It is compose by:
			Vulnerability description
			-> CVSS vector
			Products affected
			Vulnerability type
Common types of vulnerabilities are
	-> Denial of Service (DOS)
	-> Execution (Exec)
	-> Overflows
and there are also
	-> Specific Application Vulnerabilities

About finding the exploits, that is an important skill, there are three types of exploit codes
	-> Proof of concept or analysis of a vulnerability
		incomplete codes created by experts in the field that describe a given vulnerability.
	-> Public exploits
		Community-made raw code to be adapted and executed in the target. Can be dangerous to be executed.
	-> Commercial exploits
		Vendor-made codes tested in various environments, safe to be executed. Can also be followed by metrics of how the vulnerability affects the
			-> CIA triad


## References
