# Europe Should Adopt Memory Safe Technology to Achieve a secure future

Apr 15, 2025\.  First draft by Tara Tarakiyee and Hugo van de Pol.

Goal: collect comments

# Executive Summary

The number of cybersecurity incidents that affect European citizens and businesses is rising at an alarming rate. 70% of all security vulnerabilities share the same root cause and can be prevented by using modern, so-called memory-safe technology. This technology is not new, but the rate of adoption is slow due to a lack of short-term economic incentive and support for industry.

Large-scale adoption of memory-safe technology perfectly fits Europe’s forthcoming secure-by-design approach to cybersecurity. In fact, it’s the most effective way to protect Europe’s cybersecurity, reduce cybersecurity costs, and to foster innovation.

The supporting organizations call on European and national policy makers to act, out of obligation as well as untapped opportunity: to provide clear incentives and support for the large-scale adoption of memory-safe technology.

# Introduction

Today, the authoring organisations are releasing a joint statement underscoring the critical importance of adopting memory safe technology as a foundational pillar of digital infrastructure that is secure by design.

With [digital threats stemming from vulnerabilities escalating](https://www.enisa.europa.eu/sites/default/files/2024-11/ENISA%20Threat%20Landscape%202024_0.pdf), the urgency for a more resilient digital infrastructure has never been greater.

In prior years major publications by the U.S. Cybersecurity and Infrastructure Security Agency (CISA) and the U.S. White House have set the tone on the importance of memory safety \[[1](https://www.cisa.gov/sites/default/files/2023-10/Shifting-the-Balance-of-Cybersecurity-Risk-Principles-and-Approaches-for-Secure-by-Design-Software.pdf), [2](https://www.cisa.gov/resources-tools/resources/case-memory-safe-roadmaps), [3](https://bidenwhitehouse.archives.gov/wp-content/uploads/2024/02/Final-ONCD-Technical-Report.pdf)\], however in recent times the US-based agency is facing major budget cuts. Leadership from European institutions and organisations to secure our common digital infrastructure is not only long overdue, it is also imperative in the current geopolitical moment. 

We call on:

* European decision-makers in government and industry (including regulators) to take a clear stance and develop guidance on adopting memory safe technologies.

* Manufacturers and developers of digital infrastructure to evaluate the security and economic benefits of memory safe technologies and build strategic implementation roadmaps.

# What Is Memory Safety?

Memory safety refers to the ability of programming languages \- the very building blocks of all of the digital systems we rely on every day \-  to prevent security vulnerabilities that are due to accidentally mishandling memory.

These memory-related vulnerabilities:

* Account for [60%–70% of all software security vulnerabilities](https://www.chromium.org/Home/chromium-security/memory-safety/) in large codebases written in memory unsafe languages;

* Are typically hard to detect, costly to fix when they appear in production, and often used in exploits;

* Persist despite decades of developer training and tooling aimed at preventing them.

Memory safe languages (e.g. **Rust**, **Swift**, or **Java**) mitigate these risks by enforcing strict rules, making it impossible to introduce entire classes of memory-related bugs by default. This makes memory safety one of the most powerful methods for achieving secure-by-design systems.

# Why Memory Safe Tech Is Crucial

Choosing memory safe technologies is one of the most impactful decisions a manufacturer of digital infrastructure components can make to improve cybersecurity. 

* Security gains are systemic: By transitioning to memory safe languages, up to 70% of vulnerabilities can be eliminated.

* Security becomes scalable: It reduces reliance on human vigilance, which is increasingly unsustainable in the face of talent shortages, increasingly complex systems, and growing attack surfaces.

* Prevention becomes the default: By enforcing security at the language level, the software becomes safer by default, not by afterthought.

# The Urgency for Action: Secure-by-Design

We are at a pivotal moment:

* Global tensions and cyber warfare are on the rise, while our dependence on digital infrastructure grows daily;

* The cost of cyber breaches continues to climb, with some incidents costing billions;

* There is an acute shortage of cybersecurity professionals and qualified software engineers. Moreover, universities are largely moving away from memory-unsafe languages like C in their undergraduate courses. 

All of this demands a shift in mindset: from reactive patching to proactive prevention.

Considering security earlier in the development lifecycle is not a new concept, but certainly no longer optional. This has been recognized in Europe by the passing of the Cyber Resilience Act (CRA) and its security-by-design requirement. 

As the standards for the CRA are currently being developed, it’s important to consider memory safety early in their design, and include strategies to shift towards memory-safe tech where feasible, and include resources for remediation where not.

# Europe Has the Groundwork, but needs to act decisively

For decades, memory unsafe languages like C and C++ were the only viable option for performance-critical systems such as operating systems, browsers, and networking stacks. This is no longer the case.

With the rise of modern, performant memory safe languages—most notably Rust—it is now feasible to build even low-level systems securely. Furthermore, we are seeing encouraging advances towards memory-safe C++. 

That said, we are not advocating a wholesale rewrite of legacy systems. That would not be feasible. But we can and should:

* Use memory safe languages for the development of new code or components; 

* Gradually transition critical components in legacy systems where feasible;

* Introduce meaningful mitigations to reduce the risk in existing and legacy memory-unsafe systems. 

The path towards memory safety is not an easy one, but in our view the long-term security, economic, and societal benefits far outweigh the costs of inaction. Europe already has a strong foundation for this transition:

* Developers and companies in Europe have been significant contributors to open-source, memory safe critical infrastructure, such as implementations of the critical internet protocols Domain Name System (DNS) and Network Time Protocol (NTP), as well as in industries such as energy and automobile sectors;    
* There is growing adoption of memory safe languages in critical infrastructure applications and industry, according to the latest State of Rust survey. 

While the foundation exists, to get to a memory-safe future, we need shifts in development teams and supply chains, as well as long-term planning and coordinated action across industries and governments.

# We Call Upon Government and Industry to:

* **Take a decisive stance**: Formally recognize memory safety as a cornerstone of Europe's cyber resilience strategy and include specific memory safety requirements in the implementation guidelines for the Cyber Resilience Act. Where existing memory-unsafe languages are in use, this would include recommendations on measures to reduce risk where feasible.

* **Understand the economic and security business case for memory safety:** Look into the long-term financial advantages of memory-safe technologies, including reduced security incident costs, decreased downtime, lower maintenance burdens, and enhanced customer trust.

* **Establish clear migration pathways**: Issue guidelines and strategies to help organizations assess and transition critical digital infrastructure components to memory-safe technologies that builds on best practices and existing work in open standards bodies.   
* **Invest in capacity building**: Create and fund specialized training programs to address the skill shortage in memory-safe programming, partnering with universities to align outputs with the future needs of industry. 

* **Provide transition support**: Establish funding mechanisms and technical resources to assist small and medium enterprises in evaluating and implementing memory-safe alternatives in their development processes.

* **Foster the Memory Safe Ecosystem**: Invest in existing and potential open source projects and companies developing memory-safe technologies through targeted support and public-private partnerships.

* **Require risk assessment and mitigation**: Make memory safety evaluations and mitigation planning a mandatory component of security risk assessments for critical infrastructure providers and government suppliers.

# Other References

- SHIFTING THE BALANCE OF CYBERSECURITY [https://www.cisa.gov/sites/default/files/2023-10/Shifting-the-Balance-of-Cybersecurity-Risk-Principles-and-Approaches-for-Secure-by-Design-Software.pdf](https://www.cisa.gov/sites/default/files/2023-10/Shifting-the-Balance-of-Cybersecurity-Risk-Principles-and-Approaches-for-Secure-by-Design-Software.pdf)  
- The Case for Memory Safe Roadmaps [https://www.cisa.gov/resources-tools/resources/case-memory-safe-roadmaps](https://www.cisa.gov/resources-tools/resources/case-memory-safe-roadmaps)  
- BACK TO THE BUILDING BLOCKS: A Path Toward Secure And Measurable Software  
  [https://bidenwhitehouse.archives.gov/wp-content/uploads/2024/02/Final-ONCD-Technical-Report.pdf](https://bidenwhitehouse.archives.gov/wp-content/uploads/2024/02/Final-ONCD-Technical-Report.pdf)  
- 2025 Open Source Security and Risk Analysis” Report [https://www.blackduck.com/resources/analyst-reports/open-source-security-risk-analysis.html](https://www.blackduck.com/resources/analyst-reports/open-source-security-risk-analysis.html)  
- The Time is Now \- Practical Mem-Safety  
  [https://github.com/dwizzzle/Presentations/blob/master/david\_weston-isrg\_tectonics\_keynote.pdf](https://github.com/dwizzzle/Presentations/blob/master/david_weston-isrg_tectonics_keynote.pdf)  
- Securing tomorrow's software: the need for memory safety standards  
  [https://security.googleblog.com/2025/02/securing-tomorrows-software-need-for.html](https://security.googleblog.com/2025/02/securing-tomorrows-software-need-for.html)  
- The Memory Safety Continuum (OpenSSF Memory Safety SIG), [https://memorysafety.openssf.org/memory-safety-continuum/](https://memorysafety.openssf.org/memory-safety-continuum/)  
- The Case for Writing Network Drivers in High-Level Programming Languages  
  https://arxiv.org/abs/1909.06344


