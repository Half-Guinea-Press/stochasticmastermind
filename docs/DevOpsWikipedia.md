# DevOps
DevOps is a methodology in the software development and IT industry. Used as a set of practices and tools, DevOps integrates and automates the work of software development (Dev) and IT operations (Ops) as a means for improving and shortening the systems development life cycle.[^1]

## History
Proposals to combine software development methodologies with deployment and operations concepts began to appear in the late 80s and early 90s.[^2]

Around 2007 and 2008, concerns were raised by those within the software development and IT communities that the separation between the two industries, where one wrote and created software entirely separate from those that deploy and support the software was creating a fatal level of dysfunction within the industry.[^3]

In 2009, the first conference named DevOps Days was held in Ghent, Belgium. The conference was founded by Belgian consultant, project manager and agile practitioner Patrick Debois.[^4] [^5] The conference has now spread to other countries.[^6]

In 2012, a report called “State of DevOps” was first published by Alanna Brown at Puppet Labs.[^7] [^8]

As of 2014, the annual State of DevOps report was published by Nicole Forsgren, Gene Kim, Jez Humble and others. They stated that the adoption of DevOps was accelerating.[^9] [^10] Also in 2014, Lisa Crispin and Janet Gregory wrote the book More Agile Testing, containing a chapter on testing and DevOps.[^11] [^12]

In 2016, the DORA metrics for throughput (deployment frequency, lead time for changes), and stability (mean time to recover, change failure rate) were published in the State of DevOps report.[^7]

## See also
Many of the ideas fundamental to DevOps practices are inspired by, or mirror, other well known practices such as Lean and Deming's Plan-Do-Check-Act cycle, through to The Toyota Way and the Agile approach of breaking down components and batch sizes.[^13] Contrary to the "top-down" proscriptive approach and rigid framework of ITIL in the 1990s, DevOps is "bottom-up" and a flexible practice, created by software engineers, with software engineer needs in mind.[^14]

### Agile
The motivations for what has become modern DevOps and several standard DevOps practices such as automated build and test, continuous integration, and continuous delivery originated in the Agile world, which dates (informally) to the 1990s, and formally to 2001. Agile development teams using methods such as extreme programming couldn't "satisfy the customer through early and continuous delivery of valuable software"[^15] unless they subsumed the operations / infrastructure responsibilities associated with their applications, many of which they automated. Because Scrum emerged as the dominant Agile framework in the early 2000s and it omitted the engineering practices that were part of many Agile teams, the movement to automate operations / infrastructure functions splintered from Agile and expanded into what has become modern DevOps. Today, DevOps focuses on the deployment of developed software, whether it is developed using Agile oriented methodologies or other methodologies.

### ArchOps
ArchOps presents an extension for DevOps practice, starting from software architecture artifacts, instead of source code, for operation deployment.[^16] ArchOps states that architectural models are first-class entities in software development, deployment, and operations.

### CI/CD
Automation is a core principle for achieving DevOps success and CI/CD is a critical component.[^17] Plus, improved collaboration and communication between and within teams helps achieve faster time to market, with reduced risks.[^18]

### Site-reliability engineering
In 2003, Google developed site reliability engineering (SRE), an approach for releasing new features continuously into large-scale high-availability systems while maintaining high-quality end-user experience.[^19] While SRE predates the development of DevOps, they are generally viewed as being related to each other.

### Toyota production system, lean thinking, kaizen
Toyota production system, also known under the acronym TPS, was the inspiration for lean thinking with its focus on continuous improvement, kaizen, flow and small batches. The andon cord principle to create fast feedback, swarm and solve problems stems from TPS.[^20] [^21]

### DevSecOps, shifting security left
DevSecOps is an augmentation of DevOps to allow for security practices to be integrated into the DevOps approach. Contrary to a traditional centralized security team model, each delivery team is empowered to factor in the correct security controls into their software delivery. Security practices and testing are performed earlier in the development lifecycle, hence the term "shift left". Security is tested in three main areas: static, software composition, and dynamic.

In dynamic testing, also called black-box testing, software is tested without knowing its inner functions. In DevSecOps this practice may be referred to as dynamic application security testing (DAST) or penetration testing. The goal is early detection of defects including cross-site scripting and SQL injection vulnerabilities. Threat types are published by the open web application security project, e.g. its TOP10,[^22] and by other bodies.

DevSecOps has also been described as a cultural shift involving a holistic approach to producing secure software by integrating security education, security by design, and security automation.[^23]

Additional links
DataOps
DevOps toolchain
Twelve-factor app
Infrastructure as code
Lean software development
Value stream

## Cultural change
DevOps initiatives can create cultural changes in companies[^24] by transforming the way operations, developers, and testers collaborate during the development and delivery processes.[^25] Getting these groups to work cohesively is a critical challenge in enterprise DevOps adoption.[^26] [^27] DevOps is as much about culture as it is about the toolchain.[^28]

### Microservices
Although in principle it is possible to practice DevOps with any architectural style, the microservices architectural style is becoming the standard for building continuously deployed systems. Small size service allows the architecture of an individual service to emerge through continuous refactoring.[^29]

### DevOps automation
It also supports consistency, reliability, and efficiency within the organization, and is usually enabled by a shared code repository or version control. As DevOps researcher Ravi Teja Yarlagadda hypothesizes, "Through DevOps, there is an assumption that all functions can be carried out, controlled, and managed in a central place using a simple code."[^30]

#### Automation with version control
Many organizations use version control to power DevOps automation technologies like virtual machines, containerization (or OS-level virtualization), and CI/CD. The paper "DevOps: development of a toolchain in the banking domain" notes that with teams of developers working on the same project, "All developers need to make changes to the same codebase and sometimes edit even the same files. For efficient working, there has to be a system that helps engineers avoid conflicts and retain the codebase history,"[^31] with the Git version control system and the GitHub platform referenced as examples.

## GitOps
GitOps evolved from DevOps.[^32] [^33] [^34] The specific state of deployment configuration is version-controlled. Because the most popular version-control is Git, GitOps' approach has been named after Git.[^35] [^36] [^37] Changes to configuration can be managed using code review practices, and can be rolled back using version-controlling. Essentially, all of the changes to a code are tracked, bookmarked, and making any updates to the history can be made easier.[^38] As explained by Red Hat, "visibility to change means the ability to trace and reproduce issues quickly, improving overall security."[^38]

## References
[^1]: Courtemanche, Meredith; Mell, Emily; Gills, Alexander S. "What Is DevOps? The Ultimate Guide". TechTarget. Retrieved 2023-01-22.
[^2]: Chapman, M., Gatti, N: A model of a service life cycle, Proceedings of TINA '93, pp. I-205–I-215, Sep., 1993.
[^3]: Atlassian. "History of DevOps". Atlassian. Retrieved 2023-02-23.
[^4]: Mezak, Steve (25 January 2018). "The Origins of DevOps: What's in a Name?". devops.com. Retrieved 6 May 2019.
[^5]: Debois, Patrick (9 October 2008). "Agile 2008 Toronto". Just Enough Documented Information. Retrieved 12 March 2015.
[^6]: Debois, Patrick. "DevOps Days". DevOps Days. Retrieved 31 March 2011.
[^7]: Alana Brown; Nicole Forsgren; Jez Humble; Nigel Kersten; Gene Kim (2016). "2016 State of DevOps Report" (PDF). Puppet Labs, DORA (DevOps Research. Retrieved 2019-05-06.
[^8]: "Puppet - Alanna Brown". Puppet Labs. Retrieved 2019-04-27.
[^9]: Nicole Forsgren; Gene Kim; Nigel Kersten; Jez Humble (2014). "2014 State of DevOps Report" (PDF). Puppet Labs, IT Revolution Press and ThoughtWorks. Retrieved 2019-04-27.
[^10]: "2015 State of DevOps Report" (PDF). Puppet Labs, Pwc, IT Revolution Press. 2015. Retrieved 2019-05-06.
[^11]: "More Agile Testing" (PDF). October 2014. Retrieved 2019-05-06.
[^12]: Crispin, Lisa; Gregory, Janet (October 2014). More Agile Testing. Addison-Wesley. ISBN 9780133749571. Retrieved 2019-05-06.
[^13]: Klein, Brandon Thorin (2021-05-01). "The DevOps: A Concise Understanding to the DevOps Philosophy and Science". doi:10.2172/1785164. OSTI 1785164. S2CID 236606284.
[^14]: "The History and Evolution of DevOps | Tom Geraghty". 5 July 2020. Retrieved 2020-11-29.
[^15]: "Principles behind the Agile Manifesto". agilemanifesto.org. Retrieved 2020-12-06.
[^16]: Castellanos, Camilo; Correal, Dario (15 September 2018). "Executing Architectural Models for Big Data Analytics". Software Architecture. Lecture Notes in Computer Science. Vol. 11048. pp. 364–371. doi:10.1007/978-3-030-00761-4_24. ISBN 978-3-030-00760-7.
[^17]: Humble, Jez; Farley, David (2011). Continuous Delivery: reliable software releases through build, test, and deployment automation. Pearson Education Inc. ISBN 978-0-321-60191-9.
[^18]: Chen, Lianping (2015). "Continuous Delivery: Huge Benefits, but Challenges Too". IEEE Software. 32 (2): 50–54. doi:10.1109/MS.2015.27. S2CID 1241241.
[^19]: Beyer, Betsy; Jones, Chris; Petoff, Jennifer; Murphy, Niall Richard (April 2016). Site Reliability Engineering. O'Reilly Media. ISBN 978-1-4919-2909-4.
[^20]: Analyzing the DNA of DevOps, Brent Aaron Reed, Willy Schaub, 2018-11-14.
[^21]: The DevOps Handbook: How to Create World-Class Agility, Reliability, and Security in Technology Organizations, Gene Kim, Patrick Debois, John Willis, Jezz Humble, 2016
[^22]: "OWASP TOP10". Archived from the original on June 8, 2023. Retrieved June 8, 2023.
[^23]: Wilson, Glenn (December 2020). 'DevSecOps: A leader's guide to producing secure software with compromising flow, feedback and continuous improvement'. Rethink Press. ISBN 978-1781335024.
[^24]: Emerging Technology Analysis: DevOps a Culture Shift, Not a Technology (Report). Gartner.
[^25]: Loukides, Mike (7 June 2012). "What is DevOps?". O'Reilly Media.
[^26]: "Gartner IT Glossary – devops". Gartner. Retrieved 30 October 2015.
[^27]: Jones, Stephen; Noppen, Joost; Lettice, Fiona (21 July 2016). Proceedings of the 2nd International Workshop on Quality-Aware DevOps - QUDOS 2016 (PDF). pp. 7–11. doi:10.1145/2945408.2945410. ISBN 9781450344111. S2CID 515140.
[^28]: Mandi Walls (25 September 2015). "Building a DevOps culture". O'Reilly.
[^29]: Chen, Lianping; Ali Babar, Muhammad (2014). "2014 IEEE/IFIP Conference on Software Architecture". The 11th Working IEEE/IFIP Conference on Software Architecture(WICSA 2014). IEEE. pp. 195–204. doi:10.1109/WICSA.2014.45. ISBN 978-1-4799-3412-6.
[^30]: Teja Yarlagadda, Ravi (9 March 2021). "DevOps and Its Practices". SSRN 3798877.
[^31]: Morisio, Maurizio (16 April 2021). DevOps: development of a toolchain in the banking domain. Politecnico di Torino (laurea). Retrieved 16 August 2021.
[^32]: "Getting Started with GitOps". TheNewStack.io. 13 December 2021. Retrieved 5 April 2022.
[^33]: "GitOps Workflows and Principles for Kubernetes". ContainerJournal.com. 1 April 2022. Retrieved 5 April 2022.
[^34]: "Kubernetes at Scale without GitOps Is a Bad Idea". TheNewStack.io. 7 March 2022. Retrieved 5 April 2022.
[^35]: "Top 5 Challenges in Modern Kubernetes Testing". TheNewStack.io. 11 March 2022. Retrieved 5 April 2022.
[^36]: "The world's largest telcos are now embracing GitOps. Deutsche Telekom explains why".
[^37]: "Can 'shift left' in DevOps pipelines go too far?". Techtarget.com. Retrieved 5 April 2022.
[^38]: "What is GitOps?". www.redhat.com. Retrieved 2023-03-30.
