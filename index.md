---
layout: page
title: IN4334 - Analytics and Machine Learning for Software Engineering (2023/24 Q1)
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


IN4334 is a seminar course that aims to give students a _deep_ understanding of
and hands-on approach on how deep neural networks and NLP techniques are used
to represent knowledge and solve existing SE problems in novel ways.



### Learning Objectives

This course will enable students to:

* Understand current literature in the area of software analytics and machine learning for software engineering
* Apply software analytics techniques to extract actionable software engineering insights
* Apply machine learning / deep learning algorithms to solve software engineering tasks


### Before you decide to join the course

* We welcome all students who are willing to dive into cutting-edge ML research.

* _We expect students to have experience with ML already_. We also
  expect them to have some interest in program analysis. This is not an
  introductory course.

* Due to resource constraints, the course is offered to 40 students.
  If we have more than 40 registrations, we may apply CV-based selection.
  Students with demonstrable experience (i.e., GitHub repos) in ML will be
  preferred.

### Course Organization

* **5 ECTS**: This means that you need to devote at least 140 hours of study
  for this course, per person. Given that the course runs in a period of
  7 weeks, the workload is around 20 hours a week.

* **Reading sessions**: The course consists of lectures and reading sessions.
  You are not required, but you are **strongly encouraged**, to attend. Per meeting, we will be
  discussing 1 paper (presentations given either by the lecturer or
  by teams) in terms of techniques, insights, and impact.

* **Homework**: Before each lecture, you must read and prepare questions
about the papers that will be discussed during the lecture. You can find
the list of the papers to read at the beginning of each week's lecture.
You must also watch/read any material pointed to by the syllabus.

Please keep in mind that you are attending this course on a voluntary basis.
Coming to the classroom unprepared will not be the best use of your time,
so do your homework first!

* **Lecturers**: The course is supervised by Maliheh Izadi and Georgios Gousios,
  who are responsible for the content and the assignments.
  Several people will provide help with topics of their expertise.

* **Course deliverables**: To finish the course you will need to:

    * Give a 30-minute presentation on one paper
    * Apply ML to a software engineering problem
    * Provide mid-term project progress
    * Document your project's results in the form of a research paper
    * Give a final presentation about your project
    * Provide peer feedback for two project reports from other groups

* **Groups**: You will work in groups of 4-5 persons. You are free to choose
  your group partners; if this is not possible, the course lecturers will
  assign you to a group.

* **Labs**: Unsupervised, optional. 4 hours per week, designed to give
  you a place and time to work together. No feedback will be provided
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
are among the most recent deep learning-based solutions
for an enhanced software development experience.
In this project,
we aim to tailor pre-trained language models
to source code
to solve software engineering tasks
including code completion, type completion, and code summarization.
Each group will fine-tune, perform few-shot learning, or prompt engineering 
to improve a pre-trained code model
for the specific task at hand.
Then, you will evaluate the model outputs on a test set.

You will implement different models. You are required to use Python and
more specifically, [Pytorch](https://pytorch.org). 

### Required action items for week 1:

* [DeepBug paper](https://arxiv.org/abs/1805.11683), by Pradel and Sen.
* Form a group of 5 people with your classmates and choose a research paper for presentation. As a group, you will present a research paper together and do the course project.
* Add your group in the Google sheet shared [here](https://docs.google.com/spreadsheets/d/1SWoQGnuFX948Zx5zNti3vdhSrgL242E9w6_FiEme4lg/edit?usp=sharing). Share your GitHub ID as well.
* The deadline for the last two items is Thursday (Sep 7th) at 8:00 AM. Afterward, we will assign the remaining students to the incomplete groups. 
  

### Contents

| Date   |Week |Lecture | Reading material                | Lecturer |
|:------:|:---:|:------:|---------------------------------|----------|
|  5/9   | 1 | 1  | Course Introduction, [DeepBugs](https://arxiv.org/abs/1805.11683) | Georgios |
|  7/9   | 1 | 2  | [Recent work on Correctness of Code generated by LLMs](https://arxiv.org/abs/2303.11455) | Prem (UCD)|
|  12/9   | 2 | 3  | N-grams, RNN, [Code2Seq](https://arxiv.org/abs/1808.01400) | Georgios |
|  14/9  | 2 | 4  | Representations, Transformers, Large Languge Models | Georgios |
|  19/9  | 3 | 5  | [CodeXGLUE](https://arxiv.org/abs/2102.04664): A Machine Learning Benchmark Dataset for Code Understanding and Generation | Maliheh |
|  21/9  | 3 | 6  | [UniXcoder](https://arxiv.org/pdf/2203.03850): Unified Cross-Modal Pre-training for Code Representation | Maliheh |
|  26/9  | 4 | 7  | [Codex](https://arxiv.org/abs/2107.03374): Evaluating Large Language Models Trained on Code | GG / MI |
|  28/9  | 4 | 8  |  Code Filling: [InCoder](https://arxiv.org/pdf/2204.05999) and [CodeCompose](https://arxiv.org/abs/2305.12050)| Chandra (Meta) |
|  3/10  | 5 | 9  | Project feedback session: mini-presentations (8-10min) | Ali/Georgios |
|  5/10  | 5 | 10  | [StarCoder](https://arxiv.org/abs/2305.06161): May the source be with you!  |  Georgios |
|  10/10  | 6 | 11 | Guest lecture | Rui (Meta) |
|  12/10  | 6 | 12 | [Code Llama](https://arxiv.org/abs/2308.12950): Open Foundation Models for Code | Georgios |
|  17/10 | 7 | 13 | [WizardCoder](https://arxiv.org/pdf/2306.08568.pdf): Empowering Code LLMs with Evol-Instruct | Maliheh |
|  19/10 | 7 | 14 | [CodeT5+](https://arxiv.org/abs/2305.07922): Open Code Large Language Models for Code Understanding and Generation | Maliheh |
|  24/10 | 8 | 15 | [SantaCoder](https://arxiv.org/abs/2301.03988): don't reach for the stars! | Maliheh |
|  26/10 | 8 | 16 | Initial report deadline | All groups |
|  31/10 | 9 | 17 | Final report deadline | All groups |
|  10/11 | 10 | 18 | Presentation day | All groups |

---
**Lecturers**

* Maliheh Izadi: [Maliheh Izadi](https://malihehizadi.github.io/PersonalWebsite)
* Georgios Gousios: [Georgios Gousios](https://gousios.org)

**Guest lecturers**

* [Prof Prem Devanbu](https://www.cs.ucdavis.edu/~devanbu/) (UC Davis, USA)
* [Dr. Chandra Maddila](https://chandramaddila.github.io/) (Meta, USA)
* [Prof. Rui Maranhao Abreu](https://ruimaranhao.com/) (FEUP and Meta)

**Assistants**

* [Ali Al-kaswan](https://aalkaswan.github.io/)  (PhD, TU Delft)
* Jonathan Katzy (PhD, TU Delft)


### Assessment

The course grade will be calculated as:

* Project results in the form of a research paper (80%)
* Final presentation/discussion of results (20%)
* One Research paper presentation during the course (Pass/Fail)
* Mid-term project report (Pass/Fail)
* Peer feedback on project reports (Pass/Fail)

### Deadlines

All deadlines are 17:00 CET.

* 3/10 (usual lecture timeslot): Mid-term progress presentations
* 26/10: Submission of the first version of project reports
* 28/10: Submission of peer feedback
* 31/10: Submission of the final version of the report (incorporating the feedback from your peers)
* 2/11: Final presentations

