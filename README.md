# Data Science Seminar: Seminar Machine Learning - Large Language Models

Instructor: [Ricardo Usbeck](https://orcid.org/0000-0002-0191-7211)

Language models, which are trained to predict text given other text, underly many recent successes in natural language processing and artificial intelligence.
Whether used for transfer learning (using language modeling as a pre-training objective before subsequent fine-tuning on a downstream task) or prompting (formulating an input sequence that induces a model to perform a desired task without any training), language modeling has proven to be an effective way of imbuing models with useful capabailities.
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

This seminar is organized around the different "roles" students play each week:
Reviewer, Archaeologist, Researcher, Hacker, Diagrammer, and (possibly) Blogger.

  - **Scientific Peer Reviewers:** Complete a full critical, but not necessarily negative, review of the paper. Follow the [guidelines for NeurIPS reviewers](https://neurips.cc/Conferences/2022/ReviewerGuidelines) (under "Review Form"). Please complete the "Strengths and Weaknesses" and "Questions" sections and assign an overall score; you can skip the rest of the review (including writing a summary since all students should have read the paper).
  - **Archaeologist:** Could you determine where this paper sits in the context of previous and subsequent work? Find and report on one prior paper *that we are not reading in this class* that substantially influenced the current paper **or** one newer paper *that we are not reading in this class* that was heavily influenced by the current paper.
  - **Academic Researcher:** You’re a researcher who is working on a new project in this area. Propose an imaginary follow-up project not just based on the current but only possible due to the existence and success of the current paper.
  - **Industry Practitioner:** You work at a company or organization developing an application or product of your choice (that has not already been suggested in a prior session). Bring a convincing pitch for why you should be paid to implement the method in the paper and discuss at least one positive and negative impact of this application.
  - **Private Investigator:** You are a detective who needs to run a background check on one of the paper’s authors. Where have they worked? What did they study? What previous projects might have led to working on this one? What motivated them to work on this project? Feel free to contact the authors, but remember to be courteous, polite, and on-topic.
  - **Hacker:** Implement a small part of the paper on a small dataset or toy problem. Prepare to share the core code of the algorithm to the class. Do not simply download and run an existing implementation - you should implement at least a (toy version of a) method from the paper. However, you are welcome to use (and give credit to) an existing implementation for "backbone" code (e.g. model building, data loading, training loop, etc.).
  - **Social Impact and Sustainability Assessor** Identify how this paper self-assesses its (likely positive) impact on the world. Have any additional positive social impacts left out? What are possible negative social impacts that were overlooked or omitted?
 - **Diagrammer:** Create a diagram of one of the concepts or ideas from the paper or re-make one of the plots in the paper to make it clearer. Please pick something that hasn't already been diagrammed from a previous paper.
 - **Blogger:** Write a paragraph each about the two papers and an additional paragraph comparing and contrasting them. The summary of each paper should cover the motivation behind the paper, a description of any of the proposed methods, and an overview of the key findings. You should write a bit about how they are different and/or build on one another. The blogger will not present during the class session.

#### Non-presenter assignment

If you aren't in the presenting group during a given class period, please submit before class:
  1. A new title for either one of the papers and/or a new name for an algorithm proposed in either paper
  2. At least one question about either paper - could be something you're confused about or something you'd like to hear discussed more.
  3. One idea for a missing experiment.

## Schedule

The schedule below includes a preliminary list of the papers we will be reading.
These papers are subject to change, though I will try to make changes only to papers that are at least two weeks away.
If you have any suggested changes, feel free to tell me.

| Date       | Group A Paper                                                                                                                                                                                          | Group B Paper                                                                                                                    | Additional Material                                                                                                                                                                                                        |
| ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 16.10.2023 | Organization                                                                                                                                                                                           |                                                                                                                                  |                                                                                                                                                                                                                            |
| 23.10.2023 | My Research and Artifacts of the Seminar                                                                                                                                                               |                                                                                                                                  |                                                                                                                                                                                                                            |
| 30.10.2023 | Discussion of Papers and Selection                                                                                                                                                                     |                                                                                                                                  |                                                                                                                                                                                                                            |
| 06.11.2023 | [Efficient Estimation of Word Representations in Vector Space (Word2Vec)](https://arxiv.org/abs/1301.3781)                                                                                             | [The Unreasonable Effectiveness of Recurrent Neural Networks](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)           | [https://www.lesswrong.com/posts/pHPmMGEMYefk9jLeh/llm-basics-embedding-spaces-transformer-token-vectors-are](https://www.lesswrong.com/posts/pHPmMGEMYefk9jLeh/llm-basics-embedding-spaces-transformer-token-vectors-are) |
| 13.11.2023 | [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)                                                                                   | [RoBERTa: A Robustly Optimized BERT Pretraining Approach](https://arxiv.org/abs/1907.11692)                                      | [https://www.exxactcorp.com/blog/Deep-Learning/how-do-bert-transformers-work](https://www.exxactcorp.com/blog/Deep-Learning/how-do-bert-transformers-work)                                                                 |
| 20.11.2023 | [Language Models are Unsupervised Multitask Learners](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)                              | [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)                                                        | [https://jalammar.github.io/how-gpt3-works-visualizations-animations/](https://jalammar.github.io/how-gpt3-works-visualizations-animations/)                                                                               |
| 27.11.2023 | [Robust Speech Recognition via Large-Scale Weak Supervision](https://arxiv.org/abs/2212.04356)                                                             | [LiLT: A Simple yet Effective Language-Independent Layout Transformer for Structured Document Understanding](https://arxiv.org/abs/2202.13669)                                                |                                 |
| 04.12.2023 | [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜](https://dl.acm.org/doi/10.1145/3442188.3445922)                                                                             | [Release Strategies and the Social Impacts of Language Models](https://arxiv.org/abs/1908.09203)                                 |   [https://ehudreiter.com/2021/08/09/exercise-find-problems-in-an-evaluation/](https://ehudreiter.com/2021/08/09/exercise-find-problems-in-an-evaluation/)                                     |
| 11.12.2023 | [RealToxicityPrompts: Evaluating Neural Toxic Degeneration in Language Models](https://arxiv.org/abs/2009.11462)                                                                                       | [TruthfulQA: Measuring How Models Mimic Human Falsehoods](https://arxiv.org/abs/2109.07958)                                      |                                                                                                                                                                                                                            |
| 18.12.2023 | [The Pile: An 800GB Dataset of Diverse Text for Language Modeling](https://arxiv.org/abs/2101.00027)                                                                                                   | [Documenting Large Webtext Corpora: A Case Study on the Colossal Clean Crawled Corpus](https://arxiv.org/abs/2104.08758)         |                                                                                                                                                                                                                            |
| 08.01.2024 | [Extracting Training Data from Large Language Models](https://arxiv.org/abs/2012.07805)                                                                                                                | [Language Models as Knowledge Bases?](https://arxiv.org/abs/1909.01066)                                                          |                                                                                                                                                                                                                            |
| 15.01.2024 | [Do Prompt-Based Models Really Understand the Meaning of their Prompts?](https://arxiv.org/abs/2109.01247)                                                                                             | [Multitask Prompted Training Enables Zero-Shot Task Generalization](https://arxiv.org/abs/2110.08207)                            | [Chain-of-Verification Reduces Hallucination in Large Language Models](https://arxiv.org/abs/2309.11495)                                                                                                                   |
| 22.01.2024 | [🦩 Flamingo: a Visual Language Model for Few-Shot Learning](https://storage.googleapis.com/deepmind-media/DeepMind.com/Blog/tackling-multiple-tasks-with-a-single-visual-language-model/flamingo.pdf) | [Rethinking the Role of Demonstrations: What Makes In-Context Learning Work?](https://arxiv.org/abs/2202.12837)                  | [https://huggingface.co/blog/idefics](https://huggingface.co/blog/idefics)                                                                                                                                                 |
| 29.01.2024 | [Holistic Evaluation of Language Models](https://arxiv.org/abs/2211.09110)                                                                                                                             | [Beyond the Imitation Game: Quantifying and extrapolating the capabilities of language models](https://arxiv.org/abs/2206.04615) | [https://web.stanford.edu/class/cs329t/](https://web.stanford.edu/class/cs329t/)                                                                                                                                           |


## Grading

1. Presentations (up to 10 possibilities to be in a group): For each class session where you are presenting, you will be graded out of 10 points. You will receive full credit if you do a thorough job of undertaking your role and present it in a clear and compelling way. The score will be averaged.
2. Discussion (up to 10 possibilities): For each class session where you aren't presenting, you'll be given up 1 point for completing the non-presenter assignment and attending and participating in class. The score will be calculated out of 10.

## Attendance, late work, and the honor code

If you miss a class without completing the corresponding assignment, you'll get a zero for that session.
If you miss a class where you are in a "presenting" role for that session, you must still create the presentation for that role before the class and you must find someone else to present it for you.
If you miss a class where you'd be in a "non-presenting" role, to get credit for that session you need to complete the non-presenting assignment and send it to me before the start of class.
There's really no way to accept late work for the readings since it's vital that we're all reading the same papers at the same time.

All students are expected to follow the guidelines of the [UNC honor code](http://honor.unc.edu).
In the context of this class, it is particularly important that you cite the source of different ideas, facts, or methods and do not claim someone else's work as your own.
If you are unsure about which actions violate that honor code, or consult studentconduct.unc.edu.

## Conduct

I ask that we all follow the [NeurIPS Code of Conduct](https://nips.cc/public/CodeOfConduct) and the [Recurse Center Social Rules](https://www.recurse.com/social-rules).
Since this is a discussion class, it's especially important that we respect everyone's perspective and input.
In particular, I value the perspectives of individuals from all backgrounds reflecting the diversity of our students.
I broadly define diversity to include race, gender identity, national origin, ethnicity, religion, social class, age, sexual orientation, political background, and physical and learning ability.
I will strive to make this classroom an inclusive space for all students.
Please let me know if there is anything I can do to improve.

Acts of discrimination, harassment, interpersonal (relationship) violence, sexual violence, sexual exploitation, stalking, and related retaliation are prohibited.
If you have experienced these types of conduct, you are encouraged to report the incident and seek resources on campus or in the community.
Please contact the Ombudsperson https://www.leuphana.de/en/university/organisation/ombudsperson.html to discuss your specific needs.

## Changes

The professor reserves the right to make changes to the syllabus including project due dates. These changes will be announced as early as possible. 

## Acknowledgements

Thanks to [Colin Raffel](http://colinraffel.com) for providing this great idea for a seminar under [https://github.com/craffel/llm-seminar/](https://github.com/craffel/llm-seminar/)

