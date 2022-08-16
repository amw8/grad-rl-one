## CMPUT 655 Reinforcement Learning I (A Graduate-level Introduction)


## Schedule
[For the current schedule](schedule.md)

## Syllabus

This page!!!

### Term: 
Fall, 2022 

### Lecture Date and Time: 
TuThr 2:00 p.m. - 3:30 p.m.

### Lecture Location: 
ED 276

### Instruction Team:
Adam White (amw8@ualberta.ca)<br>
Vincent Liu<br>
Jordan Coblin<br>

### Office Hours:
Adam: Thursday directly after class (in 307 Athabasca Hall)<br>
TAs will hold a 2hr office hour slot every week<br>
Vincent: TBA<br>
Jordan: TBA

### TA Email Address:
????@gmail.com
(Do not presonally email the TAs. They will only respond via ????@gmail.com)

### Overview
This course provides an introduction to reinforcement learning, 
which focuses on the study and design of agents that interact with a complex, 
uncertain world to achieve a goal. 
We will emphasize agents that can make near-optimal decisions in a timely manner with incomplete information and limited computational resources. 
The course will cover Markov decision processes, reinforcement learning, planning, and function approximation (online supervised learning).

The course will use a recently created MOOC on Reinforcement Learning, created by the Instructors of this course. 
Much of the lecture material and assignments will come from the MOOC. 
In-class time will be largely spent on discussion and thinking about the material, with some supplementary lectures. 
The MOOC content will be covered more quickly (by mid October), 
so as to focus on research projects and reading RL papers in the second half of the course.

### Objectives
There are two primary goals for this course: 
to become an expert in the fundamentals of reinforcement learning and to complete asmall empirical research project in reinforcement learning.

By the end of the course, you will have a solid grasp of the main ideas in reinforcement learning, 
which is the primary approach to statistical decision-making. 
Any student who understands the material in this course will understand the foundations of much of modern probabilistic artificial intelligence (AI) and be prepared to take more advanced courses (in particular CMPUT 609: Reinforcement Learning II, and CMPUT 607: Theory for Reinforcement Learning), 
or to apply AI tools and ideas to real-world problems. 
That person will be able to apply these tools and ideas in novel situations 
– eg, to determine whether the methods apply to this situation, and if so, which will work most effectively. 
They will also be able to assess claims made by others, 
with respect to both software products and general frameworks, 
and also be able to appreciate some new research results.

The goal for the research project is to gain experience conducting a proper empirical study: specifying and answering a research question. 
Projects in courses have a tendency to be too big, 
and be largely incomplete by the end of the course. 
That will not be acceptable in this course. 
The goal here is to specify a small, 
feasible question that can be addressed thoroughly within the time-frame of the course. 
This means you have specified a clear question, and obtained clear evidence (thorough empirical study with controls and statistical significance).
#### I will provide a list of projects. You can pick one.

### Prerequisites
The course will use Python 3. We will use elementary ideas of probability, calculus, and linear algebra, such as expectations of random variables, conditional expectations, partial derivatives, vectors and matrices. Students should either be familiar with these topics or be ready to pick them up quickly as needed by consulting outside resources.

### Course Topics
With a focus on AI as the design of agents learning from experience to predict and control their environment, topics will include:

- Markov decision processes
- Planning by approximate dynamic programming
- Monte Carlo and Temporal Difference Learning for prediction
- Monte Carlo, Sarsa and Q-learning for control
- Dyna and planning with a learned model
- Prediction and control with function approximation
- Policy gradient methods

### Course Work and Evaluation
The primary evaluation will be from the project. You will have an initial draft of the project due in early November, to ensure you’ve specified a concrete and feasible project. The final project draft will be due on the last day of classes, and should be treated as a paper write-up that could be submitted to a venue (workshop, conference or journal). We will provide a list of projects, and who to approach to get more information about that project idea (e.g., Me, Martha, Marlos, Matt Taylor etc). You you will not specify your own project. Projects will be done in groups of 2-4 people.

The course work will come from the quizzes and assignments through the Coursera Platform. There will be one or two small programming assignments (notebook) and/or one or two multiple choice quizzes due each week, through the Coursera Platform. Each week, you have to complete the practice quizzes and submit a discussion question by midnight on Sunday, for discussion in class. That means you have to have completed the lectures and readings as well for that week. The course will have a midterm exam, that will come after completing the Mooc by mid October. The remainder of the course will be focused on projects.

There are 12 graded assignments. They are usually python notebooks, but sometimes it is a Graded Quiz or a Peer Review. All items will be due on Friday at midnight. Each graded assignment has equal weight (30/12).

- Assignments (graded on Coursera): 30%
- In-class Participation and discussion questions: 10%
- Midterm Exam: 15%
- Initial Draft of Project: 10%
- Final Draft of Project: 35%

### Course Materials
All course reading material will be available online. We will be using videos from the RL MOOC. We will be using the following textbook extensively: Sutton and Barto, Reinforcement Learning: An Introduction, MIT Press. The book is available from the bookstore or online as a pdf here: http://www.incompleteideas.net/book/the-book-2nd.html

### Academic Integrity
All assignments written and programming are to be done individually. No exceptions. Students must write their own answers and code. Students are permitted and encouraged to discuss assignment problems and the contents of the course. However, the discussion should always be about high-level ideas. Students should not discuss with each other (or tutors) while writing answers to written questions our programming. Absolutely no sharing of answers or code sharing with other students or tutors. All the sources used for problem solution must be acknowledged, e.g. web sites, books, research papers, personal communication with people, etc. The University of Alberta is committed to the highest standards of academic integrity and honesty. Students are expected to be familiar with these standards regarding academic honesty and to uphold the policies of the University in this respect. Students are particularly urged to familiarize themselves with the provisions of the Code of Student Behaviour and avoid any behaviour which could potentially result in suspicions of cheating, plagiarism, misrepresentation of facts and/or participation in an offence. Academic dishonesty is a serious offence and can result in suspension or expulsion from the University. (GFC 29 SEP 2003)

### FAQ on using Coursera
Error with Quiz Submission
If you get have any issues with submitting quizzes, try clearing the internet cache, closing all browser windows, and re-logging again to Coursera.

Jupyter Notebook Assignment Grading
Jupyter notebook assignments include local tests (included in the notebook), as well as grader tests that is hidden from the learners.

Please make sure your assignment passes all the local tests before submitting. Also, the solutions have to be general (i.e. not hard-coded) in order to pass the grader tests. Local test cases are not comprehensive, and even if you pass all the local tests, you may not get full marks.

Try to make your code general to work robustly for various cases. (e.g. using variable grid_w instead of value 12)

Error: Submit button is missing
On rare occasion you may face issues submitting jupyter notebook assignments. If the submit button is missing, please make sure you are only working on the notebook on a single device. If the problem still persists, try setting “?forceRefresh=true” in your notebook URL (reference: https://learner.coursera.help/hc/en-us/articles/360004995312-Solve-problems-with-Jupyter-Notebooks)
