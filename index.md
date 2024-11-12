---
layout: page
title: CS4570 - Machine Learning for Software Engineering (2024/25 Q2)
description: Course information
---

### General description

Software repositories archive valuable software engineering data, such as source
code, execution traces, historical code changes, mailing lists, and bug reports.
This data contains a wealth of information about a project's status and history.
By doing data science on software repositories, researchers can gain an empirically
based understanding of software development practices, and practitioners can
better manage, maintain, and evolve complex software projects.

In recent years, the advances in Machine Learning and AI technologies,
as demonstrated by the successful application of Deep Neural Networks in various
domains [did not go unnoticed](https://github.com/src-d/awesome-machine-learning-on-source-code)
[in the field of Software Engineering](https://ml4code.github.io/papers.html).
Researchers have applied DNNs to tackle issues such as automated program
repair, code summarization, code completion, code structure representation, etc.


CS4570 is a seminar course that aims to give students a hands-on approach to applying neural networks and NLP techniques to solve existing SE problems.



### Learning Objectives

This course will enable students to:

* Understand current literature in the area of software analytics and machine learning for software engineering.
* Apply machine learning / deep learning algorithms to solve software engineering tasks.
* Apply software analytics techniques to extract actionable software engineering insights.
* Evaluate model performance on a software engineering task.



### Before you decide to join the course

_We expect students to have experience with ML already_. We also
  expect them to have some interest in program analysis. This is *NOT* an
  introductory course. Here are the requirements:

* Experience with programming is required (preferably Python)
* Experience with machine learning and specifically deep learning techniques is a must-have.
* Familiarity with transformer-based language models and modern NLP is needed

Recommended:
* Experience with research methods is nice to have
* Taking the NLP course before this class is recommended



### Course Organization

* **5 ECTS**: This means that you need to devote at least 140 hours of study
  for this course, per person. That is 17.5 hours per week for a duration of 8 weeks. Two hours is for the class and the rest should be spent on reading papers and working on the projects.

* **Reading sessions**: As seminars are a main part of this course, class attendance and engagement in discussions are vital. Per session, we will be
  discussing papers (presentations are given either by the lecturer or
  by teams) in terms of techniques, insights, and impact.

* **Action items**: Before each lecture, you must read and prepare questions
about the papers that will be discussed during the lecture.
Please keep in mind that you are attending this course on a voluntary basis.
Coming to the classroom unprepared will not be the best use of your time,
so do your homework first!

* **Lecturers**: The course is supervised by Maliheh Izadi,
  who is responsible for the content and the project.
 

* **Course deliverables**: To finish the course you will need to:

    * Give a 30-minute presentation on one paper (we will adjust the time based on the final number of students)
    * Apply ML to a software engineering problem
    * Provide mid-term project progress
    * Document your project's results in the form of a research paper
    * Give a final presentation about your project
    * Provide peer feedback for two projects from other groups

* **Groups**: You will work in groups of 6-7 people (may need to adjust the number based on the total number of students). CS and DSAIT students are already assigned to 13 groups. If you are a new student from another program and do not have a group, you are free to choose your group partners during the first lecture, hence presence in the first lecture is **mandatory**, otherwise you cannot contribute to a team and will fail the class.

* **Labs**: you are encouraged to spend a minimum of 4 hours per week working on your project with your teammates. No feedback will be provided
  during lab hours by the lecturers.

### The project
Lately, machine-learning techniques have been successfully
tailored to many software engineering problems.
For instance, intelligent code completion helps developers
finish their programming tasks faster and more efficiently
by decreasing the typing effort,
providing type-correct solutions,
and enabling them to explore APIs.
[InCoder](https://arxiv.org/abs/2204.05999),
[UniXcoder](https://arxiv.org/pdf/2203.03850), and
[CoPilot](https://github.com/features/copilot)
are among some of the recent deep learning-based solutions
for an enhanced software development experience.
In this project,
we aim to tailor language models to source code
to solve software engineering tasks
including code completion, type completion, and code summarization.
Each group will fine-tune, perform few-shot learning, or prompt engineering 
to improve a pre-trained code model
for a software engineering problem of their choosing.
Then, they will evaluate the model outputs on a test set.

You will implement different models. You are required to use Python and
more specifically, [Pytorch](https://pytorch.org). 

More details will be shared during the course.



### Required action items for week 1:

* Form a group of 6-7 people with your classmates (if you are not in a group already) and choose a research paper for presentation. As a group, you will present a research paper together and do the course project.
* Add your group in the Google sheet shared [here](https://docs.google.com/spreadsheets/d/1tTYupSTvEu8MMK3DkNbdTg36IXN8gKGxvSz8eNmmkA8/edit?usp=sharing). Share your GitHub ID as well.
* The deadline for the last two items is Friday (Nov 15th) at 17:00. Afterward, you cannot take the class as you do not have a group. 

### Paper presentation and discussion guidelines
<span style="color: #BA0F30;">**NOTE!**</span> Please refer to the sample [template](pages/discussion-template.html).

### Contents

| Date   |Week |Lecture | Reading material                | Source |
|:------:|:---:|:------:|---------------------------------|----------|
|  Nov 13th   | 1 | 1 | Course introduction and modeling code | Lecturer |
|  Nov 13th   | 1 | 2 | Code Generation with Transformers and Benchmarking (paper presentation) | Lecturer |
|  Nov 20th   | 2 | 1  | [CodeXGLUE, A Machine Learning Benchmark Dataset for Code Understanding and Generation](https://arxiv.org/abs/2102.04664) | Microsoft|
|  Nov 20th   | 2 | 2  | [Codex, Evaluating Large Language Models Trained on Code](https://arxiv.org/abs/2107.03374) | OpenAI|
|  Nov 27th   | 3 | 1  | [EvalPlus, Is Your Code Generated by ChatGPT Really Correct? Rigorous Evaluation of Large Language Models for Code Generation](https://arxiv.org/abs/2305.01210) | UIUC |
|  Nov 27th  | 3 | 2  | [CodeT5+: Open Code Large Language Models for Code Understanding and Generation](https://arxiv.org/pdf/2305.07922) | Salesforce |
|  Dec 4th  | 4 | 1  | [Code Llama: Open Foundation Models for Code](https://scontent.frtm1-1.fna.fbcdn.net/v/t39.2365-6/440937359_1249838219330505_1104237120116944930_n.pdf?_nc_cat=109&ccb=1-7&_nc_sid=3c67a6&_nc_ohc=eFL-JWuycecQ7kNvgGNb3OR&_nc_zt=14&_nc_ht=scontent.frtm1-1.fna&_nc_gid=Ag-BIch6x0Lf2YXJs4h9Yrr&oh=00_AYDHQfpCK9k4GicNU8uCZU1ZKpewWJqonlwLe3o8mYYcgw&oe=67396CA0) | Meta |
|  Dec 4th  | 4 | 2  | [Chatbot Arena: An Open Platform for Evaluating LLMs by Human Preference](https://arxiv.org/abs/2403.04132) | UC Berkeley, Stanford |
|  Dec 11th  | 5 | 1  | [StarcCoder 2 and the Stack V2](https://arxiv.org/abs/2402.19173) | HuggingFace |
|  Dec 11th | 5 | 2  | [WizardCoder: Empowering Code LLMs with Evol-Instruct](https://arxiv.org/abs/2306.08568) | HuggingFace |
|  Dec 18th  | 6 | 1  | [CodeGemma: Open Code Models Based on Gemma](https://arxiv.org/abs/2406.11409) | Google |
|  Dec 18th  | 6 | 2 | [Magicoder: Empowering Code Generation with OSS-Instruct](https://arxiv.org/abs/2312.02120) |  UIUC |
|  Jan 8th | 7 | 1 | [SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770)  | Princeton |
|  Jan 8th | 7 | 2 | [DeepSeek-Coder: When the Large Language Model Meets Programming -- The Rise of Code Intelligence](https://arxiv.org/abs/2401.14196) | DeepSeek |
|  Jan 15th | 8 | 1 | [LiveCodeBench: Holistic and Contamination Free Evaluation of Large Language Models for Code](https://arxiv.org/abs/2403.07974) | UC Berkeley, MIT, Cornell |
|  Jan 15th | 8 | 2 | [Stable Code Technical Report](https://arxiv.org/pdf/2404.01226) | StabilityAI |
|  Jan 22nd  | 9 | 18 | <span style="color: #BA0F30;">**Final presentations EEMCS-Lecture Hall D@ta (36.HB.01.630) - Exam day - book your calendars**</span> | |

---
**Lecturer**

* Maliheh Izadi: [Maliheh Izadi](https://malihehizadi.github.io/PersonalWebsite)


**Assistants**

* Ali Al-kaswan
* Jonathan Katzy
* Daniele Cipolone
* Razvan Popescu
* Nadine Kou
* Roham Koohestani
  

### Assessment

The course grade will be calculated as:

* Project results in the form of a research paper (70%)
* Final presentation/discussion of results (20%)
* Individual Q&A in presentation (10%)
* One Research paper presentation during the course (Pass/Fail)
* Mid-term project report (Pass/Fail)
* Peer feedback on project reports (Pass/Fail)



