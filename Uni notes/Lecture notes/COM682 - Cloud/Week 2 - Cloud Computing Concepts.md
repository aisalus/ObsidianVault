Subject: [[COM682 - Cloud]]
Date: 04-10-2023
Lecture Week 2 - Cloud Computing Concepts

## Main Points
- Project Natick - Data centre 117 ft underwater in Scotland's Orkney Islands
- Azure: 50 regions worldwide, available in 140 countries - Why? Scale, latency, compliance
- How is it possible to leverage these many thousand servers without interruption? Abstraction.
- Three types of abstraction: Conceptual, Logical and Physical
- Abstraction hides specifics from a consumer of services

- Cloud building blocks which allow for abstraction:
	- Application Software
	- Development Software
	- Resource Sharing
	- Infrastructure
- App layer: top layer the user sees
- Dev layer: allows devs to write software in terms of cloud platform API
- Resource layer: One machine, multiple tenants
- Infrastructure: Physical resources

- Cloud paradigms:
	- SaaS - Software as a Service (Microsoft 365)
	- PaaS - Platform as a Service (Google Applab)
	- IaaS - Infrastructure as a Service (Azure)

- SaaS:
	- Software and data hosted on Cloud
	- User access via thin client through web browser
	- Provider manages and maintains updates and security
	- Multitenant, scalable, one-to-many
	- Pricing: Fixed monthly/annual fee

- PaaS:
	- Allows for creation of web applications
	- Users develop, deploy and scale apps on platforms offered by provider
	- Provider responsible for platform. Dev responsible for software
	- Web-based IDE. Multitenant. Scaled by provider.
	- Pricing dependant on app usage.
	- Good for rapid development.
	- Not good for portable apps.

- IaaS:
	- Resources are available to users, usually as instances or virtual machines
	- Configurable infrastructure
	- Highest level of tenant control
	- Users are responsible for everything bar the actual hardware
	- Usually multitenant, but depending on need can be single tenant
	- Priced on an hourly basis
	- Prorated pricing: Partial hours charged partially
	- Non-prorated pricing: Partial hours charged as full hours
	- Can get very expensive depending on need and amount of instances
	- Very useful if lots of resources are needed quickly, for example holiday periods and high scalability is needed
	- Not always an option - Regulatory reasons like government

![[Pasted image 20231004154800.png]]

![[Pasted image 20231004154817.png]]

![[Pasted image 20231004154845.png]]

## Related Resources
- 

## Things to Memorize
- Cloud paradigms
- Abstraction