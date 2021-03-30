# CS-210: Final Exam

Tuesday, 26 January 2021, 8:15 - 11:15

This exam is open book in the sense that you are allowed to consult the PDF slides for all lectures in this course.

The exam consists of a list of programming assignments that you should solve in order, using the usual tools from the class (git, sbt, and your favorite text editor). Each student will be given a unique question order. We do not expect that you can necessarily solve all questions in this limited time, but you should do your best.

In addition to problem statements, each problem comes with a set of automated tests, just like for the labs. If your solution passes all the given tests, it is most likely correct and you can expect to obtain a full grade for that question. Also make sure to follow any additional requirements listed in the problem statement. Some of those requirements, such as avoiding the use of vars, are not covered by our automated tests and will be graded manually.

The TAs will be available on Discord during the exam. In case you have questions or need help, don’t hesitate to contact one of the TAs using Discord’s private messages or our public Discord channel. It is your responsibility to ensure that you have access to reliable internet connection, hardware, and software for the duration of the exam. Also make sure that you are comfortable using the usual tools from the class, so that you can focus on the exam.

*No cheating*: Each student must solve the exam individually. Consulting with anyone except the teaching staff of this course during the exam or making your solution available to anyone is considered cheating and a reason for disciplinary action. We will use plagiarism detection tools on your solution. We reserve the right to follow up with some of you on Zoom after the scheduled slot and ask you about solutions to your or similar questions, whether or not we suspect you cheated; this possibility is a normal part of the examination this year.

## How to obtain questions

Assignments will be available online at the start of the exam. Please clone the following repository to have access to problem statements in case you lose your internet connection:

```
git clone https://github.com/lampepfl/cs210-2020-exam.git
```

Each assignment is published similarly to labs: the problem statements are given as markdown files in the following directory: https://github.com/lampepfl/cs210-2020-exam/tree/main/exam; the code skeleton for each problem is available in a separate branch of your private GitLab repository. Each student will receive a list of links to their questions before the exam by email.

## How to submit questions

Your answers are submitted by pushing your code on GitLab, just like the labs. After you submit your solution, you will receive a preliminary grade for that question. This information will be available in the GitLab CI. The tests executed on the CI are identical to those you can run locally. For detailed information, refer to labs submission instructions: https://gitlab.epfl.ch/lamp/cs210/-/blob/master/labs/grading-and-submission.md#committing-and-pushing-your-code.

You are allowed to push multiple times for the same question (only the last commit will be considered). Furthermore, you are allowed to go back to your previous questions and submit your answers out of order. We still recommend you to solve the exam in order, to avoid negative points (see examples in the last section).

## How to run tests

Refer to labs submission instructions for detailed information on how to run tests: https://gitlab.epfl.ch/lamp/cs210/-/blob/master/labs/grading-and-submission.md#local-tests-and-grading

## Recommended workflow summary

After you have obtained a question, do the following:

1. read the requirements carefully
2. write the solution taking the requirements into account
3. make sure your solution compiles
4. make sure your solution passes the local tests on your machine; if it does not, repeat previous steps
5. submit your solution using git
6. start working on the next question

If you feel you are spending more time on the question and will likely not solve it, then go to step 6 to get a chance at solving the subsequent question. Note that you will be losing 3 points if you do not solve a question, so take this into account.

## How do we grade the exam

Each question you solve correctly gives you **10** points. A question is solved correctly if it passes all the tests including those we made available to you (a maximum grade of 10/10), and the solution fulfills all the requirements listed in the problem statement (such as not using vars). If you do not manage to solve a particular question, you can skip to the next one. Skipped questions, as well as partially correct solutions, are penalized with **-3** points (a grade of 9/10 is considered incorrect and thus equivalent to skipping that question).

Here are some examples of how we compute grades given the following question order:

Q1, Q2, Q3, Q4, Q5, Q6, Q7, Q8, Q9, Q10

**Example 1**:
You successfully solved questions Q1 and Q2, you partially solved or skipped question Q3, and you successfully solved questions Q4 and Q5. You will get `10+10-3+10+10 = 37` points.

**Example 2**:
You skipped the first five questions and successfully solved questions Q6 and Q7. You will get `-3-3-3-3-3+10+10 = 5` points.

**Example 3**:
You skipped the first seven questions and successfully solved question Q8. You will get `-3-3-3-3-3-3-3+10 = -11` points, which will be rounded up to zero.

Given the exam format, those points will then be converted to traditional grades depending on the overall exam performance. Our aim is that a student who mastered the material can solve approximately 7 questions in this time period (taking into account small variations in question difficulty) and obtain a maximum grade, if they did not skip any questions. This estimate is provided only to help your time planning.
