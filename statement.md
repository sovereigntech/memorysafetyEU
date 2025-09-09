# Improving Europe's cybersecurity posture through memory safety

Apr 15, 2025\.  First draft by Tara Tarakiyee and Hugo van de Pol.

Goal: collect comments

Aug 04, 2025\.  Revised draft by Benjamin Schilling based on comments provided by community.

Goal: Agree on draft.

# Executive Summary

Memory safety vulnerabilities account for 60-70% of all software security issues in major digital systems written in memory-unsafe programming languages. As cyber threats intensify globally, Europe has the groundwork and potential to make memory safe technologies a cornerstone of secure digital infrastructure. This statement calls for decisive action from European decision makers and industry leaders to prioritise memory safety as part of a comprehensive "secure-by-design" approach.

# Introduction

Today, the authoring organisations are releasing a joint statement underscoring the critical importance of adopting memory safe technology as a foundational pillar of digital infrastructure that is secure by design.

With [digital threats stemming from vulnerabilities escalating](https://www.enisa.europa.eu/sites/default/files/2024-11/ENISA%20Threat%20Landscape%202024_0.pdf), the urgency for a more resilient digital infrastructure has never been greater.

In prior years major publications by the U.S. Cybersecurity and Infrastructure Security Agency (CISA) and the U.S. White House have set the tone on the importance of memory safety \[[1](https://www.cisa.gov/sites/default/files/2023-10/Shifting-the-Balance-of-Cybersecurity-Risk-Principles-and-Approaches-for-Secure-by-Design-Software.pdf), [2](https://www.cisa.gov/resources-tools/resources/case-memory-safe-roadmaps), [3](https://bidenwhitehouse.archives.gov/wp-content/uploads/2024/02/Final-ONCD-Technical-Report.pdf), [4](https://www.cisa.gov/resources-tools/resources/product-security-bad-practices), [5](https://www.cisa.gov/resources-tools/resources/secure-design-alert-eliminating-buffer-overflow-vulnerabilities), [6](https://www.ncsc.nl/actueel/nieuws/2025/07/22/casus-citrix-kwetsbaarheid)\], however in recent times the US-based agency is facing major budget cuts. Leadership from European institutions and organisations to secure our common digital infrastructure is not only long overdue, it is also imperative in the current geopolitical moment. With the EU Cyber Resilience Act, a first legislation prioritises secure-by-design development, for which the use of memory safe technology is essential.

We call on:

* European decision-makers in government and industry (including regulators) to take a clear stance and develop guidance on adopting memory safe technologies.

* Manufacturers and developers of digital infrastructure to evaluate the security and economic benefits of memory safe technologies and build strategic implementation roadmaps.

# What Is Memory Safety?

Memory safety refers to the ability of programming languages — the very building blocks of all of the digital systems we rely on every day — to prevent security vulnerabilities that are due to accidentally mishandling memory.

These memory-related vulnerabilities:

* Account for [60%–70% of all software security vulnerabilities](https://www.chromium.org/Home/chromium-security/memory-safety/) in large codebases written in memory unsafe languages. Examples of such code bases include the operating systems, web browsers, and screen sharing solutions that businesses and citizens use every day; 

* Are typically hard to detect, costly to fix when they appear in production, and often used in exploits \[[1](https://heartbleed.com/), [2](https://googleprojectzero.blogspot.com/p/0day.html), [3](https://www.reuters.com/technology/cybersecurity/china-cyber-spies-hacked-computers-dutch-defence-ministry-report-2024-02-06/), [4](https://www.cisa.gov/news-events/ics-advisories/icsa-20-343-01)\];

* Persist despite decades of developer training and tooling aimed at preventing them.

Memory safe languages (e.g., **Rust**, **Python**, **Swift**, or **Java**) mitigate these risks by enforcing strict rules, making it impossible to introduce entire classes of memory-related bugs by default. This makes memory safety one of the most powerful methods for achieving secure-by-design systems.

# Why Memory Safe Tech Is Crucial

Choosing memory safe technologies is one of the most impactful decisions a manufacturer of digital infrastructure components can make to improve cybersecurity. 

* Security gains are systemic: By transitioning to memory safe languages, up to 70% of vulnerabilities can be eliminated.

* Security becomes scalable: It reduces reliance on human vigilance, which is increasingly unsustainable in the face of talent shortages, increasingly complex systems, and growing attack surfaces.

* Prevention becomes the default: By enforcing security at the language level, the software becomes safer by default, not by afterthought.

* Ecosystems around memory safe languages improve developer efficiency: Developer experience of all major memory safe languages contributes to increased productivity, as they provide integrated tools for development and supply chain management.

# The Urgency for Action: Secure-by-Design

We are at a pivotal moment:

* Global tensions and cyber warfare are on the rise, while our dependence on digital infrastructure grows daily;

* The cost of cyber breaches continues to climb, with some incidents costing billions;

* While there is an acute shortage of cybersecurity professionals and qualified software engineers; \[[1](https://www.asisonline.org/security-management-magazine/latest-news/today-in-security/2024/october/skills-shortage-cybersecurity/)\]. 

All of this demands a shift in mindset: from reactive patching to proactive prevention \[[1](https://www.orangecyberdefense.com/global/security-navigator)\].

Considering security earlier in the development lifecycle is not a new concept, but certainly no longer optional. This has been recognised in Europe by the passing of the Cyber Resilience Act (CRA) and its security-by-design requirement. 

# Where we are today
As CISA previously concluded: the most effective, systematic and scalable way to get rid of all memory-safety vulnerabilities is to build new systems using memory-safe by default tech, and to migrate legacy systems step by step.

In Europe, there is now some adoption of modern memory-safe tech, and several incentives for it, including:

+ regulation that demands a secure-by-design approach to cybersecurity (e.g. the CRA, which is in development); 
+ the awareness that the current reactive approach to cybersecurity is no longer feasible (orange report);
+ the generally high skill level of engineers, which lowers the bar for using modern tech. 

At the same time, individual businesses, including large industry players that build part of our digital infrastructure, perceive a lack of short-term economic incentive in the midst of fierce international competition to start migrating parts of large existing code bases. 

Society as a whole is bearing the long-term consequences and costs of the persisting vulnerabilities in these systems. In The Netherlands for example, the root cause of both the recent hack of the Public Prosecution office and China spying on the Ministry of Defense in 2022-2023 was memory-unsafe code. 

To us this means that regulatory bodies have the obligation to recognize the detriment of the current situation, but also the opportunities that faster adoption of memory-safe technologies would bring: lowering the costs of cybersecurity, both for companies and for society, and ensuring technological innovation, thus strengthening Europe’s competitive position.

# We Call To:

* **Take a decisive stance**: Formally recognise memory safety as a cornerstone of Europe's cyber resilience strategy and include specific memory safety requirements in the implementation guidelines for the Cyber Resilience Act. Where existing memory-unsafe languages are in use, this would include recommendations on measures to reduce risk where feasible.

* **Industries for understanding the economic and security business case for memory safety:** Look into the long-term financial advantages of memory safe technologies, including reduced security incident costs, decreased downtime, lower maintenance burdens, and enhanced customer trust.

* **Standardisation Bodies to establish clear migration pathways**: Issue guidelines and strategies to help organisations assess and transition critical digital infrastructure components to memory safe technologies that builds on best practices and existing work in open standards bodies. 

* **EU and governments to invest in capacity building, provide transition support and require risk assessment and mitigation**: Create and fund specialised training programs to address the skill shortage in memory safe programming, partnering with universities to align outputs with the future needs of industry. Establish funding mechanisms and technical resources to assist small and medium enterprises in evaluating and implementing memory safe alternatives in their development processes. Invest in existing and potential open source projects and companies developing memory safe technologies through targeted support and public-private partnerships. Make memory safety evaluations and mitigation planning a mandatory component of security risk assessments for critical infrastructure providers and government suppliers.

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
- 2024 State of Rust Survey, [https://blog.rust-lang.org/2025/02/13/2024-State-Of-Rust-Survey-results/](https://blog.rust-lang.org/2025/02/13/2024-State-Of-Rust-Survey-results/)
- Most admired and desired programming languages in 2025 StackOverflow Developer Survey, [https://survey.stackoverflow.co/2025/technology/#admired-and-desired](https://survey.stackoverflow.co/2025/technology/#admired-and-desired)

