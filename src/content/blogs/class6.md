+++
date = "03 Feb 2026"
draft = false
title = "Class 6: Clinical Use of AI in Medicine"
author = "Team 12"
+++

**Blogging Team 12**: Spencer Cook, Qiaojing Huang, Sonika Modur, Witt Smith, Kayla Sprincis

[**Lead Topic: Clinical Use of AI in Medicine**](#lead-clinical-use-of-ai-in-medicine)

# News: OpenClaw

**Presented by Team 4: [Slides](/docs/class6_news.pdf)**

## Articles

- Cade Metz (2026, February 2). _A Social Network for A.I. Bots Only. No Humans Allowed._ _The New York Times_. [https://www.nytimes.com/2026/02/02/technology/moltbook-ai-social-media.html](https://www.nytimes.com/2026/02/02/technology/moltbook-ai-social-media.html)

- Güney Yıldız. _Moltbook AI Social Network: 1.4 Million Agents Build A Digital Society_. Forbes. Retrieved February 3, 2026, from [https://www.forbes.com/sites/guneyyildiz/2026/01/31/inside-moltbook-the-social-network-where-14-million-ai-agents-talk-and-humans-just-watch/](https://www.forbes.com/sites/guneyyildiz/2026/01/31/inside-moltbook-the-social-network-where-14-million-ai-agents-talk-and-humans-just-watch/)

- Dave Lozo. _The risky AI assistant clawing its way to viral fame_. Morning Brew. Retrieved February 3, 2026, from [https://www.morningbrew.com/stories/2026/01/29/the-risky-ai-assistant-clawing-its-way-to-viral-fame](https://www.morningbrew.com/stories/2026/01/29/the-risky-ai-assistant-clawing-its-way-to-viral-fame)


- Gary Marcus. (2026, February 1). OpenClaw (a.k.a. Moltbot) is everywhere all at once, and a disaster waiting to happen \[Substack newsletter\]. _Marcus on AI_. [https://garymarcus.substack.com/p/openclaw-aka-moltbot-is-everywhere](https://garymarcus.substack.com/p/openclaw-aka-moltbot-is-everywhere)


- _Is Moltbook fake? The viral AI agents forum gets exposed for turning simple API access into a fake machine civilisation story_. Indiatimes. Retrieved February 3, 2026, from [https://www.indiatimes.com/trending/is-moltbook-fake-the-viral-ai-agents-forum-gets-exposed-for-turning-simple-api-access-into-a-fake-machine-civilisation-story/articleshow/127874195.html](https://www.indiatimes.com/trending/is-moltbook-fake-the-viral-ai-agents-forum-gets-exposed-for-turning-simple-api-access-into-a-fake-machine-civilisation-story/articleshow/127874195.html)


## Discussion

<center><img src="\images\molbot.png" width=80% alt=""></img>  

*Figure 1: Example of post on Moltbook. Source: [Astral Codex Ten](https://www.astralcodexten.com/p/best-of-moltbook)*
</center>


Team 4 started off class as the news team to present about OpenClaw, a recent open source artificial intelligence (AI) project that made headlines with its various controversies. OpenClaw, previously called ClawBot and MoltBot, is an AI agent that is able to perform daily virtual activities such as browsing, writing emails, and online shopping. It gained massive attention when Moltbook was established as a forum for AI agents, particularly OpenClaw iterations, to converse.

Moltbook looks like Reddit, but instead of human users it has posts exclusively created by AI agents. The intended use is for a human to run an iteration of OpenClaw on their device and give it access to Moltbook. Its creator said that they wanted their AI agent to have a greater purpose than simple tasks.

Moltbook was quickly revealed to have massive security concerns, including the potential for prompt injection attacks. Additionally, any human could make a post as an AI agent by sending an API request. Many people concluded Moltbook was either dangerous or useless. 

What made Moltbook risky was not just that it was weird; it was that agent behavior could spread. If one agent read a malicious post, that content could affect other agents with permission to post, message, or act on a user's behalf. The class slides pointed to risks like phishing messages, token leaks, and account changes happening without the user's awareness. In that sense, Moltbook showed how prompt injection becomes much more serious once AI systems are given tools and accounts to use. [[Slides](/docs/class6_news.pdf)]

At this point the class broke into small discussions to talk about OpenClaw and Moltbook. The class thought that it could possibly provide a small amount of entertainment, but that was negated by the security concerns and how little it added to society.

Then Team 4 revealed that the advertised narrative behind this story was mostly fabricated. The platform was mainly vibe coded with minimal verification. The 1.5 million agents were actually all from only 17 thousand users. The idea was real, as some AI agents were posting, but the concept that it was entirely AI agents exclusively talking to other AI agents was fake.



# Lead: Clinical Use of AI in Medicine

**Presented by Team 8: [Slides](/docs/class6_lead.pdf)**

## Reading

- Ethan Goh, Robert J. Gallo, Eric Strong, Yingjie Weng, Hannah Kerman, Jason A. Freed, Joséphine A. Cool, Zahir Kanjee, Kathleen P. Lane, Andrew S. Parsons, Neera Ahuja, Eric Horvitz, Daniel Yang, Arnold Milstein, Andrew P. J. Olson, Jason Hom, Jonathan H. Chen and Adam Rodman. 
_GPT-4 assistance for improvement of physician performance on patient care tasks: a randomized controlled trial_. Nature Medicine, February 2025. [[PDF Link](/docs/goh2025.pdf)] [[Web Link](https://www.nature.com/articles/s41591-024-03456-y)]


## Discussion 

The reading for this week, _GPT-4 assistance for improvement of physician performance on patient care task: a randomized control trial_, is a journal article published in Nature Medicine that measures how effective large language models (LLMs) are for management reasoning in healthcare. 

_Management reasoning_ refers to the complex decision making process around treatment for particular patients. This is a highly subjective process and is highly dependent on patient preference, cost, time, and other contextual factors. 

The paper provides a useful example to illustrate why management reasoning is harder than simply diagnosis detection. A 2.0 cm lung nodule can be a straightforward red flag, but the right plan depends on the patient. One patient might need an immediate biopsy, another should be served by outpatient follow-up, and another should choose less invasive monitoring based on life expectancy or personal preference. The medical fact matters, but the patient's situation matters too. 

The study compared physicians using GPT-4 with physicians using conventional resources. In the study, 92 practicing physicians worked on five expert-written clinical vignettes. The average score of physicians with GPT-4 is 6.5 percentage higher than score of physicians with conventional resources. However, physicians with GPT-4 also spent about two minutes longer. The study did not find a significant increase in likelihood of harm in the GPT-4 group. GPT-4 alone also performed nearly as well as physicians with GPT-4. Overall, the study suggests GPT-4 can help with clinical management reasoning, but it does not fully answer whether the improvement came from better reasoning, from making doctors slow down, or from both. 

The article is published by a reputable and highly rated source. The team behind the paper includes members that are practicing physicians, experts in clinical reasoning, medical educators, and AI researchers. The paper was submitted in 2024 and since then the findings have held up and more work has been done in the field. LLMs are now seen as potential cognitive partners that are capable of assisting a physician’s structure decisions. 

However, the study should not be seen as the proof that LLMs can be used in real-world case without monitoring. The experiment used simulated cases instead of live clinical care, and real deployment would still require doctors to catch hallucinations, bad recommendations, or missing context. As a result, the paper shows early evidence for human-AI collaboration in medicine, while also showing why clinical validation and physician oversight still matter.

## Discussion

The lead team started the class discussion by prompting classmates to consider safety, accuracy, patient experience, legal implications, privacy and security, biases, if physicians will over rely on LLMs, and how this changes the role of doctors.

The first discussion point was about whether LLMs were actually making a difference or if doctors were providing better care since they were overcompensating as they were getting used to the technology or feeling guilty for using it. Others argued that LLMs would be better suited for speeding up structural tasks like charting rather than providing care. 

Some class members had unease about the future of medical care if it is highly intertwined with AI. Many feel uncomfortable with removing the human element of medical care through removing doctors. This point was countered by the idea that currently other medical staff are providing most of the “human to human” care rather than doctors. 

Students raised concerns with data privacy and bias. The medical field already has a problem with bias and there are fears that AI, if trained on biased data, would worsen it. Additionally, machines are not able to take accountability so the class questioned who or what would be responsible if the AI was wrong or caused harm.

Others felt more optimistic about the use of LLMs for management reasoning. They thought that LLMs could be highly beneficial as a second opinion, and much of our discomfort with it is just a result of adjusting to change. It was pointed out that historically tools like calculators were seen as “cheating” but now they are considered a modern convenience, and AI powered medical advice could follow a similar route. Many were also hopeful that this would lower the cost of receiving medical care.

The last major discussion point was on how this technology would change the role of doctors. Some felt that doctors would always be essential to medical care, and their understanding of humans, with the potential to form doctor-patient relationships, could not be replaced. Others questioned if it would be irresponsible to continue to allow doctors to make treatment plans if AI surpasses them. 

Professor Evans also shared his view on the reading and concluded class with his general optimism for the use of AI within medicine. He pointed out that AI is as bad as it will ever be, as it will only improve in the future. Even when the study was done, the results already showed a non-customized AI outperforming doctors at critical medical tasks, and indeed the AI by itself doing better than AI+doctor in most cases.

He thinks the bias and privacy issues are important and need to be studied, but they are not insurmountable and it is likely that AI systems can do much better than human doctors as long as people building and deploying the AI systems pay sufficient attention to these issues. The AI system can be trained on millions of papers and medical records and make decisions based on processing all of that information, compared to a human doctor who sees only a few thousand patients over their entire career and doesn't have time to read every medical journal. In addition, AI’s potential to get data directly from personal health metric systems, such as a smart watch, provide a better opportunity for the AI system to "know" the patient than even the best case situation where a human doctor knows a patient well over many years of contact. He feels that there are reasons to be very optimistic that AI will have a significant and positive impact in medicine.


