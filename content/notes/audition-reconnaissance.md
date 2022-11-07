---
title: "audition-reconnaissance"
tags:
- 
enableToc: false
---

The phase of reconnaissance in [system auditing](notes/system-auditing.md) consists of gathering as much specific information possible about a target. It can be open ports, software versions, running services, etc.

as it is a lot of information, it is stored and organized in a 
	-> target database
		its structure depends on the type of target, but generally it consists of
			the identification of the host
			port
			protocol
			service
			version
			comments
		can be created using pencil and paper or a spreadsheet, but for more organization, tools like 
		-> Metasploit
			it is a toolkit including more than 500 tools, capable of automatically create and manage a target database
		and Core Impact can be used

one of the most popular tools used in reconnaissance is
	-> nmap
		can find ports and services behind those ports;
		has a scripting engine that can extend the information gathering by the tool
			-> Nmap Scripting Engine (NSE)
				allows to automate network tasks
		can be used for network testing, discovery, advanced version, backdoor, vulnerability and exploit detection etc
another popular tool, already cited, is
	-> Metasploit 

## References
