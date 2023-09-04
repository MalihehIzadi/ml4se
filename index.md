---
layout: page
title: IN4334 - Machine Learning for Software Engineering (ML4SE)
description: Course information
---

## General description

Software repositories archive valuable software engineering data, such as source
code, execution traces, historical code changes, mailing lists, and bug reports.
This data contains a wealth of information about a project's status and history.
Doing data science on software repositories, researchers can gain empirically
based understanding of software development practices, and practitioners can
better manage, maintain, and evolve complex software projects.

In the recent years, the advances in Machine Learning and AI technologies,
as demonstrated by the successful application of Deep Neural Networks in various
domains [did not go unnoticed](https://github.com/src-d/awesome-machine-learning-on-source-code)
[in the field of Software Engineering](https://ml4code.github.io/papers.html).
Researchers have applied DNNs to tackle issues such as automated program
repair, code summarization, code completion, code structure representation, etc.

IN4334 is a seminar course that aims to give students a _deep_ understanding of
and hands-on approach on how deep neural networks and NLP techniques a

---

## Learning Objectives

This course will enable students to:

* Understand current literature in the area of software analytics and machine learning for software engineering
* Apply software analytics techniques to extract actionable software engineering insights
* Apply machine learning / deep learning algorithms to solve software engineering tasks


## Before you decide to join the course

* We welcome all students that are willing to dive into cutting edge ML research.

* _We expect students to have experience with ML already_. We also
  expect them to have some interest in program analysis. This is not an
  introductory course.

* Due to resource constraints, the course is offered for 40 students.
  If we have more than 40 registrations, we may apply CV-based selection.
  Students with demonstrable experience (i.e., GitHub repos) in ML will be
  preferred.

## Course Organization

* **5 ECTS**: This means that you need to devote at least 140 hours of study
  for this course, per person. Given that the course runs in a period of
  7 weeks, the workload is around 20 hours a week.

* **Reading sessions**: The course consists of lectures and reading sessions.
  You are not required, but you are **strongly encouraged**, to attend. Per meeting, we will be
  discussing 1 paper (presentations given either by the lecturer or
  by teams) in terms of techniques, insights and impact.

* **Homework**: Before each lecture, you must read and prepare questions
about the papers that will be discussed during the lecture. You can find
the list of the papers to read on the beginning of each week's lecture.
You must also watch/read any material pointed to by the syllabus.

Please keep in mind that you are attending this course on voluntary basis.
Coming to the classroom unprepared will not be the best use of your time,
so do your homework first!

* **Lecturers**: The course is supervised by Maliheh Izadi and Georgios Gousios,
  who are responsible for the content and the assignments.
  Several people will provide help in topics of their expertise.

* **Course deliverables**: To finish the course you will need to:

    * Give a 30 min presentation of one papers
    * Apply ML to a software engineering problem
    * Provide mid-term project progress
    * Document your project's results in a form of a reseach paper
    * Give a final presentation about your project
    * Provide peer feedback for two project reports from other groups

* **Groups**: You will work in groups of 4-5 persons. You are free to choose
  your group partners; if this is not possible, the course lecturers will
  assign you to a group.

* **Labs**: Unsupervised, optional. 4 hours per week, designed to give
  you a place and time to work together. No feedback will be provided
  during lab hours by the lecturers.

## The project
Lately, machine learning techniques have been successfully
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
for source code
to solve software engineering tasks
including code completion, type completion, and code summarization.
Each gorup will fine-tune, perform few-short learning or prompt engineering 
to improve a pre-trained code model
for the specific task at hand.
Then, you will evaluate the models outputs on a test set.

You will implement different models. You are required to use Python and
more specifically, [Pytorch](https://pytorch.org). Check our curated list of
[tutorials](tutorials.html) that might help you in getting started with different
NLP, DL, and ML topics.

## Required reading for week 1:

* [DeepBug paper](https://arxiv.org/abs/1805.11683), by Pradel and Sen [@Pradel2018]
* [Discussion presentation template](discussion-template.html)
