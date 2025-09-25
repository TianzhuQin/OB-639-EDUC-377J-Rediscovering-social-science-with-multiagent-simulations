# Rediscovering Social Science with Multiagent Simulations

F25-OB-639-01 / EDUC-377J-01

- **Meeting**: Tuesdays 3:00–5:50 PM (Fall quarter) in Botha Chan BC332
- **Instructors**: Amir Goldberg (`amirgo@stanford.edu`) and Daniel A. McFarland (`mcfarland@stanford.edu`)
- **Office Hours**: Amir – TBD; Daniel – Thursdays 3:20–5:20 PM ([Calendly](https://calendly.com/mcfarland-office-hours))
- **Grading**: 20% participation, 80% final project
- **Honor Code**: Collaborate on ideas, write your own work, no AI assistance for written submissions, cite all sources

This repository organizes weekly reference code, readings, and student contributions for the seminar. It is designed so the cohort can experiment with LLM-based multi-agent simulations, share code, and coordinate the final project deliverables.

## Repository Map

- `weeks/` – weekly folders with reference code space, prompts, and reading highlights
- `student-projects/` – student-created simulations, experiments, and analyses
- `final-project/` – guidance, milestones, and templates for the culminating project
- `resources/` – shared tools, datasets, and LLM simulation tips curated during the quarter

## Weekly Readings & Themes

**Week 1 – Foundations: What Are Models and Why Do We Need Them?**
- *Smaldino, Paul (2024).* Preface & Chapter 1 of _Modeling Social Behavior: Mathematical and Agent-Based Models of Social Dynamics and Cultural Evolution_. [EBSCO Access](https://research-ebsco-com.stanford.idm.oclc.org/c/qmsjx4/search/details/dp5e5attyv?db=nlebk&db=nlabk)
- *Bruch, E., & Atwell, J. (2013).* Agent-Based Models in Empirical Social Research. _Sociological Methods & Research_, 44(2), 186–221. [Link](https://doi.org/10.1177/0049124113506405)
- *Bail, Christopher A. (2024).* Can Generative AI Improve Social Science? _PNAS_, 121(21), e2314021121. [Link](https://www.pnas.org/doi/10.1073/pnas.2314021121)
- *Gürcan, Önder (2024).* LLM-Augmented Agent-Based Modelling for Social Simulations: Challenges and Opportunities. _HHAI 2024_. [Link](https://ebooks.iospress.nl/volumearticle/68007)
- *Adornetto, C. et al. (2025).* Generative Agents in Agent-Based Modeling: Overview, Validation, and Emerging Challenges. _IEEE Transactions on Artificial Intelligence_. [Link](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10985773)
- Optional: *Anthis, J. R. et al. (2025).* Position: LLM Social Simulations Are a Promising Research Method. _ICML Position Paper Track_. [arXiv](https://arxiv.org/pdf/2504.02234)
- Optional: *Bianchi, F., & Squazzoni, F. (2015).* Agent-Based Models in Sociology. _WIREs Computational Statistics_, 7(4), 284–306. [Link](https://wires.onlinelibrary.wiley.com/doi/pdfdirect/10.1002/wics.1356)
- Optional: *Gilbert, Nigel (2019).* _Agent-Based Models_. Sage Publications.
- Optional: *Horton, John J. (2023).* Large Language Models as Simulated Economic Agents: What Can We Learn from Homo Silicus? _NBER Working Paper_. [PDF](https://www.nber.org/system/files/working_papers/w31122/w31122.pdf)
- Optional: *Park, J. S. et al. (2023).* Generative Agents: Interactive Simulacra of Human Behavior. _UIST_.
- Optional: *Thapa, S. et al. (2025).* Large Language Models (LLM) in Computational Social Science: Prospects, Current State, and Challenges. _Social Network Analysis and Mining_. [Link](https://link.springer.com/article/10.1007/s13278-025-01428-9)

**Week 2 – Individual Foundations / Agents**
- *Smaldino, Paul (2024).* Chapter 2 “Particles.”
- *Sumers, T. R. et al. (2024).* Cognitive Architectures for Language Agents. _TMLR_.
- *Kozlowski, A. C., & Evans, J. (2025).* Simulating Subjects: The Promise and Peril of Artificial Intelligence Stand-Ins for Social Agents and Interactions. _Sociological Methods & Research_. [Link](https://doi.org/10.1177/00491241251337316)
- *Baggio, Giosuè (2025).* Could Machine Learning Help to Build a Unified Theory of Cognition? _Nature_, 644, 881–883. [Link](https://www.nature.com/articles/d41586-025-02353-9)
- Optional: *Ashokkumar, A. et al. (2024).* Predicting Results of Social Science Experiments Using Large Language Models. [PDF](https://samim.io/dl/Predicting%20results%20of%20social%20science%20experiments%20using%20large%20language%20models.pdf)
- Optional: *Binz, M. et al. (2025).* A Foundation Model to Predict and Capture Human Cognition. _Nature_, 644, 1002–1009. [Link](https://doi.org/10.1038/s41586-025-09215-4)
- Optional: *Park, J. S. et al. (2024).* Generative Agent Simulations of 1,000 People. [arXiv](https://arxiv.org/pdf/2411.10109)
- Optional: *Turner, Stephen P. (2018).* _Cognitive Science and the Social: A Primer_. Routledge Press.

**Week 3 – Homophily**
- *Smaldino, Paul (2024).* Chapter 3.
- *Piao et al. (2025).* Emergence of Human-Like Polarization Among Large Language Model Agents. [arXiv](https://arxiv.org/abs/2501.05171)
- *Kozlowski, A. C., H. Kwon, & J. Evans (2024).* In Silico Sociology: Forecasting COVID-19 Polarization with Large Language Models. [arXiv](https://arxiv.org/abs/2407.11190)
- *Törnberg, P. (2023).* Don’t Blame the Algorithms for Online Polarization—Science.org. [Link](https://www.science.org/content/article/don-t-blame-algorithm-polarization-may-be-inherent-social-media)
- Optional: *Larooij, M., & Törnberg, P. (2025).* Can We Fix Social Media? Testing Prosocial Interventions Using Generative Social Simulation. [arXiv](https://arxiv.org/pdf/2508.03385)

**Week 4 – Simple & Complex Contagion, Networks**
- *Smaldino, Paul (2024).* Chapter 4 “Contagion” and Chapter 9 “Networks.”
- *Guilbeault, D., Becker, J., & Centola, D. (2018).* Complex Contagions: A Decade in Review. In _Complex Spreading Phenomena in Social Systems_. [arXiv](https://arxiv.org/pdf/1710.07606)
- *Goldberg, Amir, & Stein, S. K. (2018).* Beyond Social Contagion: Associative Diffusion and the Emergence of Cultural Variation. _American Sociological Review_.
- *Chang, S. et al. (2025).* LLMs Generate Structurally Realistic Social Networks but Overestimate Political Homophily. _ICWSM_. [Link](https://ojs.aaai.org/index.php/ICWSM/article/view/35820/37974)
- Optional: *Centola, D., & Macy, M. (2007).* Complex Contagions and the Weakness of Long Ties. _American Journal of Sociology_. [JSTOR](https://www.jstor.org/stable/10.1086/521848)
- Optional: *Papachristou, M., & Yuan, Y. (2024).* Network Formation and Dynamics Among Multi-LLMs. [arXiv](https://arxiv.org/abs/2402.10659)
- Optional: *Cohen, M. D. et al. (1972).* A Garbage Can Model of Organizational Choice. _Administrative Science Quarterly_. [JSTOR](https://www.jstor.org/stable/pdf/2392088.pdf)

**Week 5 – Belief Change & Persuasion**
- *Smaldino, Paul (2024).* Chapter 5 “Opinion Dynamics.”
- *Havin, M. et al. (2025).* Can (A)I Change Your Mind? [arXiv](https://arxiv.org/abs/2503.01844)
- *Chuang, Y.-S. et al. (2023).* Simulating Opinion Dynamics with Networks of LLM-Based Agents. [arXiv](https://arxiv.org/abs/2311.09618)
- *Tessler, M. et al. (2024).* AI Can Help Humans Find Common Ground in Democratic Deliberation. _Science_, 386. [Link](https://www.science.org/doi/10.1126/science.adq2852)

**Week 6 – Cooperation, Coordination, Norms, Conventions**
- *Smaldino, Paul (2024).* Chapters 6 “Cooperation” and 7 “Coordination.”
- *Ashery, A. F. et al. (2025).* Emergent Social Conventions and Collective Bias in LLM Populations. _Science Advances_, 11(20), eadu9368. [Link](https://www.science.org/doi/full/10.1126/sciadv.adu9368)
- *Dai, G. et al. (2024).* Artificial Leviathan: Exploring Social Evolution of LLM Agents Through the Lens of Hobbesian Social Contract Theory. [arXiv](https://arxiv.org/pdf/2406.14373)
- *Bicchieri, C. (2014).* Norms, Conventions, and the Power of Expectations. In _Philosophy of Social Science: A New Introduction_. [Link](https://global.oup.com/academic/product/philosophy-of-social-science-9780199645107)
- Optional: *Hollis, Martin (1994).* The Philosophy of Social Science: An Introduction (Chapter 6 “Games and Rational Agents”). [EBSCO](https://research.ebsco.com/c/qmsjx4/search/details/fxmmy7cwlf?db=nlebk)
- Optional: *Shoham, Y., & Tennenholtz, M. (1997).* On the Emergence of Social Conventions. _Artificial Intelligence_, 94(1-2), 139–166.
- Optional: *Hawkins, R. X. D. et al. (2019).* The Emergence of Social Norms and Conventions. _Trends in Cognitive Sciences_, 23(2), 158–169.
- Optional: *Wu, Z. et al. (2024).* Shall We Team Up: Exploring Spontaneous Cooperation of Competing LLM Agents. [arXiv](https://arxiv.org/abs/2402.12327)

**Week 7 – Social & Organizational Learning**
- *Laland, K. N. (2004).* Social Learning Strategies. _Learning & Behavior_, 32(1), 4–14. [doi:10.3758/BF03196002]
- *Barkoczi, D., & Galesic, M. (2016).* Social Learning Strategies Modify the Effect of Network Structure on Group Performance. _Nature Communications_, 7(13109). [doi:10.1038/ncomms13109]
- *Rendell, L. et al. (2010).* Why Copy Others? Insights from the Social Learning Strategies Tournament. _Science_, 328(5975), 208–213. [doi:10.1126/science.1184719]
- *Lazer, D., & Friedman, A. (2007).* The Network Structure of Exploration and Exploitation. _Administrative Science Quarterly_, 52(4), 667–694.
- Optional: *Brugnoli, E. et al. (2019).* Recursive Patterns in Online Echo Chambers. _Scientific Reports_, 9(1). [doi:10.1038/s41598-019-56191-7]
- Optional: *March, J. (1991).* Exploration and Exploitation in Organizational Learning. _Organization Science_, 2(1), 71–87.
- Optional: *Perez, J. et al. (2024).* Cultural Evolution in Populations of Large Language Models. [arXiv](https://arxiv.org/pdf/2403.08882)

**Week 8 – Conversation & Constructionist Approaches**
- *Carley, Kathleen (1986).* Knowledge Acquisition as a Social Phenomenon. _Instructional Science_, 14, 381–438. [JSTOR](https://www.jstor.org/stable/pdf/23369065.pdf)
- *Gupta, A. et al. (2024).* Harnessing Toulmin’s Theory for Zero-Shot Argument Explication. _ACL 2024_. [Link](https://aclanthology.org/2024.acl-long.552.pdf)
- *Zhou, X. et al. (2024).* Is This the Real Life? Is This Just Fantasy? The Misleading Success of Simulating Social Interactions with LLMs. [arXiv](https://arxiv.org/pdf/2403.05020)
- *Ivey, J. et al. (2024).* Real or Robotic? Assessing Whether LLMs Accurately Simulate Qualities of Human Responses in Dialogue. [arXiv](https://arxiv.org/pdf/2409.08330)
- Optional: *Chakraborty, I. et al. (2023).* AI and AI-Human Based Salesforce Hiring Using Conversational Interview Videos. [SSRN](http://www-2.rotman.utoronto.ca/userfiles/brownbags/marketing/files/SalesVideoData-Toronto.pdf)
- Optional: *Goldberg, Adele E. (2024).* Usage-Based Constructionist Approaches and Large Language Models. [PDF](https://scispace.com/pdf/a-chat-about-constructionist-approaches-and-llms-4ay9ur881a.pdf)
- Optional: *Yang, D. et al. (2024).* The Call for Socially Aware Language Technologies. [arXiv](https://arxiv.org/pdf/2405.02411)

**Week 9 – Modeling the Scientific Process**
- *Smaldino, Paul (2024).* Chapter 8 “The Scientific Process.”
- *Yang, Y., Youyou, W., & Uzzi, B. (2020).* Estimating the Deep Replicability of Scientific Findings Using Human and Artificial Intelligence. _PNAS_, 117(20), 10762–10768.
- *de Tarlé, L. D. et al. (2025).* Argumentative Agent-Based Models. _Journal of Applied Logics_, 12(3). [PDF](https://philpapers.org/archive/DUPAAM-3.pdf)
- *Zollman, K. J. S. (2010).* The Epistemic Benefit of Transient Diversity. _Erkenntnis_, 72(1), 17–35. [PDF](http://fitelson.org/few/few_07/zollman.pdf)
- Optional: *Liang, W. et al. (2024).* Can Large Language Models Provide Useful Feedback on Research Papers? _NEJM AI_, 1(8), AIoa2400196.

**Week 10 – Student Presentations**
- Showcase of final projects, in-progress experiments, and reflective syntheses.

## How to Contribute

1. Fork or branch from `main` before making changes.
2. Place personal or team deliverables in a dedicated subfolder under `student-projects/` using the convention `student-projects/<sunet-id>-<short-description>/`.
3. Submit pull requests with a concise summary and include notes on how to reproduce any results.

Questions, suggestions, or new resource links are welcome via issues or pull requests or email me [tianzhu@stanford.edu](mailto:tianzhu@stanford.edu). Let’s build a shared toolkit for exploring sociological theory with multi-agent LLM simulations.
