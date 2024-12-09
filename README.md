# Data Science Seminar: Seminar Machine Learning - Large Language Models

Instructor: [Ricardo Usbeck](https://orcid.org/0000-0002-0191-7211)

Language models, which are trained to predict text given other text, underly many recent successes in natural language processing and artificial intelligence.
Whether used for transfer learning (using language modelling as a pre-training objective before subsequent fine-tuning on a downstream task) or prompting (formulating an input sequence that induces a model to perform a desired task without any training), language modelling has proven to be an effective way of imbuing models with useful capabilities.
These capabilities have been observed to consistently improve as the size of the language model increases, which has led to a focus on developing ever-larger language models.
In this course, we will survey the history of language model scaling, as well as recent advances in building, analyzing, and using large LMs.
The course will use a [role-playing seminar format](https://colinraffel.com/blog/role-playing-seminar.html), described in more detail below.

## Prerequisites

Students must have experience with machine learning (preferably deep learning) and the basics of modern natural language processing.
Before taking the class, you should be able to read a recent machine learning or natural language processing conference paper and come away with a decent understanding of the basic concepts and ideas proposed in the paper (but not necessarily a deep, perfect understanding of every last detail).

## Course Structure

This class will use a [role-playing seminar](https://colinraffel.com/blog/role-playing-seminar.html) format where students take on different roles and present papers to one another.
All grading will be based on these presentations and course participation; there will be a final poster. 

### Readings

Each class will involve the presentation and discussion of two papers.
The pair of papers covered in each class session are meant to complement each other, e.g. because one paper might be the historical precedent of the other, or the papers were contemporary, or they present different viewpoints on the same topic.
Before each class, everyone is required to have read both papers.
Students will be assigned roles.
This role defines the lens through which they read the paper and determines what they prepare for the in-class discussion.
Students in the non-presenting groups are also required to read the papers, complete a quick exercise (described below), and come to class ready to discuss.
All students will obtain a thorough understanding of the chosen papers and will develop their paper reading, literature review, and prototyping skills.

#### Presentation roles

This seminar is organized around the different "roles" students play each week. The number of roles given out depends on the number of students in the class.

  - **Explainer (Theory):** The explainer describes the underlying method and its theoretical foundation to the group. They can use the whiteboard to make a 1 sketch or bring a 1 handout or make 1 slide. The goal is, that students understand the underlying theory in detail. Whatever is brought to class stays visible to all during the following discussion.
  - **Scientific Peer Reviewers:** Complete a full critical, but not necessarily negative, review of the paper. Follow the [guidelines for NeurIPS reviewers](https://neurips.cc/Conferences/2022/ReviewerGuidelines) (under "Review Form"). Please complete the "Strengths and Weaknesses" and "Questions" sections and assign an overall score; you can skip the rest of the review (including writing a summary since all students should have read the paper). You can go to [OpenReview](https://openreview.net/) to see actual reviews, e.g., search for my name. The time-box for this role is 5 minutes max.
  - **Archaeologist:** Could you determine where this paper sits in the context of previous and subsequent work? Find and report on one prior paper *that we are not reading in this class* that substantially influenced the current paper **or** one newer paper *that we are not reading in this class* that was heavily influenced by the current paper. 
  - **Academic Researcher:** You’re a researcher who is working on a new project in this area. Propose an imaginary follow-up project not just based on the current but only possible due to the existence and success of the current paper.
  - **Industry Practitioner:** You work at a company or organization developing an application or product of your choice (that has not already been suggested in a prior session). Bring a convincing pitch for why you should be paid to implement the method in the paper and discuss at least one positive and negative impact of this application.
  - **Private Investigator:** You are a detective who needs to run a background check on one of the paper’s authors. Where have they worked? What did they study? What previous projects might have led to working on this one? What motivated them to work on this project? Feel free to contact the authors, but remember to be courteous, polite, and on-topic. Can you say something about the venue where this paper was published? Can you say something about the popular interest in the paper, if there was any?
  - **Hacker:** Implement a small part of the paper on a small dataset or toy problem. Prepare to share the core code of the algorithm with the class. Do not simply download and run an existing implementation - you should implement at least a (toy version of a) method from the paper. However, you are welcome to use (and give credit to) an existing implementation for "backbone" code (e.g. model building, data loading, training loop, etc.).
  - **Social Impact and Sustainability Assessor** Identify how this paper self-assesses its (likely positive) impact on the world. Have any additional positive social impacts left out? What are possible negative social impacts that were overlooked or omitted?
 - **Diagrammer:** Create a diagram of one of the concepts or ideas from the paper or re-make one of the plots in the paper to make it clearer. Please pick something that hasn't already been diagrammed from a previous paper.
 - **Blogger:** Write a paragraph about each of the two papers and an additional paragraph comparing and contrasting them. The summary of each paper should cover the motivation behind the paper, a description of any of the proposed methods, and an overview of the key findings. You should write a bit about how they are different and/or build on one another. The blogger will not be present during the class session.

#### Non-presenter assignment

If you aren't in the presenting group during a given class period, please prepare the following and **send it via email**:

  - 1. A new title for either one of the papers and/or a new name for an algorithm proposed in either paper
  - 2. At least one question about either paper - could be something you're confused about or something you'd like to hear discussed more.
  - 3. One idea for a missing experiment.

## Grading

1. Presentations (up to 10 possibilities to be in a group): For each class session where you are presenting, you will be graded out of 10 points. You will receive full credit if you do a thorough job of undertaking your role and present it in a clear and compelling way. The score will be averaged.
2. Discussion (up to 10 possibilities): For each class session where you aren't presenting, you'll be given 1 point for completing the non-presenter assignment and attending and participating in class. The score will be calculated out of 10.

## Attendance, late work, and the honor code

If you miss a class without completing the corresponding assignment, you'll get a zero for that session.

If you miss a class where you are in a "presenting" role for that session, you must still create the presentation (2-pager) for that role **before** the class.

If you miss a class where you'd be in a "non-presenting" role, to get credit for that session you need to **complete** the non-presenting assignment and send it to me **before** the start of class.

There's really no way to accept late work for the readings since it's vital that we're all reading the same papers at the same time.

All students are expected to follow the guidelines of the [Leuphana Campus Rules](https://www.leuphana.de/einrichtungen/gleichstellung.html).
In the context of this class, it is particularly important that you cite the source of different ideas, facts, or methods and do not claim someone else's work as your own.
If you are unsure about which actions violate that honour code, consult studentconduct.unc.edu.

## Conduct

I ask that we all follow the [NeurIPS Code of Conduct](https://nips.cc/public/CodeOfConduct) and the [Recurse Center Social Rules](https://www.recurse.com/social-rules).
Since this is a discussion class, we must respect everyone's perspective and input.
In particular, I value the perspectives of individuals from all backgrounds reflecting the diversity of our students.
I broadly define diversity to include race, gender identity, national origin, ethnicity, religion, social class, age, sexual orientation, political background, and physical and learning ability.
I will strive to make this classroom an inclusive space for all students.
Please let me know if there is anything I can do to improve.

Acts of discrimination, harassment, interpersonal (relationship) violence, sexual violence, sexual exploitation, stalking, and related retaliation are prohibited.
If you have experienced these types of conduct, you are encouraged to report the incident and seek resources on campus or in the community.
Please contact the Ombudsperson at [https://www.leuphana.de/en/university/organisation/ombudsperson.html](https://www.leuphana.de/en/university/organisation/ombudsperson.html) to discuss your specific needs.

## Changes

The professor reserves the right to make changes to the syllabus including project due dates. These changes will be announced as early as possible. 

## Schedule

The schedule below includes a preliminary list of the papers we will be reading.
These papers are subject to change, though I will try to make changes only to papers that are at least two weeks away.
If you have any suggested changes, feel free to tell me.

Why are we not talking about the newest models such as Gemma, Mistral, Qwen or GPT o1? There are also new model families such as [State Space Models](https://www.kolaayonrinde.com/blog/2024/02/11/mamba.html) or [KAN: Kolmogorov-Arnold Networks](https://arxiv.org/abs/2404.19756) where we do not have the time to delve into.
We know too little but you can prove me wrong!


| Date       | Group A Paper                                                                                                                                                                                          | Group B Paper                                                                                                                    | Additional Material                                                                                                                                                                                                        |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 14.10.2023 | Organization                                                                                                                                                                                           |                                                                                                                                  |                                                                                                                                                                                                                            |
| 21.10.2023 | My Research and Artifacts of the Seminar, Topic Discussion and Selection                                                                                                                                                            |                                                                                                                                  |                                                                                                                                                                                                                            |
| 28.10.2023 | Cancelled                                                                                             |  | Homework: Prepare your readings! Find a visual introduction to most models at [AI by Hand](https://aibyhand.substack.com/)|
| 04.11.2023 | Paper 1: [Efficient Estimation of Word Representations in Vector Space (Word2Vec)](https://arxiv.org/abs/1301.3781)                                                                                             |  | [Speech and Language Processing (3rd ed. draft)](https://web.stanford.edu/~jurafsky/slp3/), [Demo 1](https://www.cs.cmu.edu/~dst/WordEmbeddingDemo/), [Demo 2](https://remykarem.github.io/word2vec-demo), [Demo 3 (recommended)](https://ronxin.github.io/wevi/),[Jalammar: The illustrated Word2Vec](https://jalammar.github.io/illustrated-word2vec/), [Reference Blog Post](https://mccormickml.com/2016/04/19/word2vec-tutorial-the-skip-gram-model/)|
| 11.11.2023 | Paper 2: [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)                                                                                           |  | [LLM Basics: Embedding Spaces - Transformer Token Vectors Are Not Points in Space](https://www.lesswrong.com/posts/pHPmMGEMYefk9jLeh/llm-basics-embedding-spaces-transformer-token-vectors-are) [How do BERT Transformers work?](https://www.exxactcorp.com/blog/Deep-Learning/how-do-bert-transformers-work), [Teaching paper: How do transformers work?](https://arxiv.org/abs/2304.10557), [Transformers take over in other communities](https://docs.google.com/presentation/d/1ZXFIhYczos679r70Yu8vV9uO6B1J0ztzeDxbnBxD1S0/edit?usp=sharing), [Speech and Language Processing (3rd ed. draft)](https://web.stanford.edu/~jurafsky/slp3/), [Transformers visually explained](https://x.com/rfeers/status/1836344502543618385)|
| 18.11.2023 | Paper 3: [Language Models are Unsupervised Multitask Learners (GPT-2)](https://cdn.openai.com/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)                              | Paper 4: [Language Models are Few-Shot Learners (GPT-3)](https://arxiv.org/abs/2005.14165)                                                        | [How GPT3 Works - Visualizations and Animations](https://jalammar.github.io/how-gpt3-works-visualizations-animations/), [LLM Visualization - Click through here once!](https://bbycroft.net/llm), [Llama 3.1 405B Release notes - see the need for GPUs](https://x.com/astonzhangAZ/status/1815763885380747422), [Understanding LLMs: A Comprehensive Overview from Training to Inference](https://arxiv.org/pdf/2401.02038v2)                                                                             |
| 25.11.2023 | Paper 5: [Robust Speech Recognition via Large-Scale Weak Supervision (Whisper)](https://arxiv.org/abs/2212.04356)                                                             | Paper 6: [LiLT: A Simple yet Effective Language-Independent Layout Transformer for Structured Document Understanding](https://arxiv.org/abs/2202.13669)                                                |                                 |
| 02.12.2023 |  Paper 7: [The FineWeb Datasets: Decanting the Web for the Finest Text Data at Scale](https://arxiv.org/abs/2406.17557)                                                                                                   | Paper 8: [Rethinking Interpretability in the Era of Large Language Models](https://arxiv.org/pdf/2402.01761)                                                                                                                                                                                                                                |
| 09.12.2023 | Paper 9: [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜](https://dl.acm.org/doi/10.1145/3442188.3445922)                                                                             | Paper 10: [Release Strategies and the Social Impacts of Language Models](https://arxiv.org/abs/1908.09203)                                 |   [Exercise: Find Problems in an Evaluation](https://ehudreiter.com/2021/08/09/exercise-find-problems-in-an-evaluation/)                                     |
| 16.12.2023 |   Paper 11: [Holistic Evaluation of Language Models](https://arxiv.org/abs/2211.09110)                                                                                                                             | Paper 12: [Beyond the Imitation Game: Quantifying and extrapolating the capabilities of language models](https://arxiv.org/abs/2206.04615) | [Stanford Course CS 329T: Trustworthy Machine Learning](https://web.stanford.edu/class/cs329t/), [LLM Arena - a new way of evaluating LLMs](https://lmarena.ai/)                          |
| 06.01.2024 | Paper 13: [Extracting Training Data from Large Language Models](https://arxiv.org/abs/2012.07805)                                                                                                                | Paper 14: [Language Models as Knowledge Bases?](https://arxiv.org/abs/1909.01066)                                                          |  [A bad way to measure hallucination](https://ehudreiter.com/2023/10/31/a-bad-way-to-measure-hallucination/)    [Chain-of-Verification Reduces Hallucination in Large Language Models](https://arxiv.org/abs/2309.11495)  [LLama 2 Intro and Hallucination Reduction by Meta](https://ai.meta.com/llama/get-started/)   [A survey on large language model (LLM) security and privacy:The Good, The Bad, and The Ugly](https://www.sciencedirect.com/science/article/pii/S266729522400014X)                                                                                                                                                                                                                       |
| 13.01.2024 |   Paper 15: [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks (RAG)](https://arxiv.org/abs/2005.11401)                                                                                                                             | Paper 16: [What Are Tools Anyway? A Survey from the Language Model Perspective](https://zorazrw.github.io/files/WhatAreToolsAnyway.pdf) |                                                                                                                                   |
| 20.01.2024 | Paper 17: [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/pdf/2304.03442)                                                                                                                             | Paper 18: [GPT-4V(ision) is a Generalist Web Agent, if Grounded](https://arxiv.org/abs/2401.01614) | [Demo of SeeAct](https://github.com/OSU-NLP-Group/SeeAct?tab=readme-ov-file) [Imprompter: Tricking LLM Agents into Improper Tool Use](https://imprompter.ai/)                                     |
| 27.01.2024 | Poster Conference  |||                                                                                                                                


## Acknowledgements

Thanks to [Colin Raffel](http://colinraffel.com) for providing this great idea for a seminar under [https://github.com/craffel/llm-seminar/](https://github.com/craffel/llm-seminar/)

