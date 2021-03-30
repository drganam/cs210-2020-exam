# CS-206: Midterm Exam

Wednesday, 14 April 2021, 14:15

This exam is open book in the sense that you are allowed to consult the PDF slides for all lectures in this course and the Functional Programming course. The exam will cover all the material seen in the class up to week 6 (included).

The exam consists of four programming assignments that you should solve using the usual tools from the class (git, sbt, and your favorite text editor). In addition to problem statements, each problem comes with a set of automated tests, just like for the labs. Your grade is determined by the number of these tests that pass. Also make sure to follow any additional requirements listed in the problem statement. Some of those requirements might not be covered by our automated tests and will be graded manually.

The TAs will be available on Discord during the exam. In case you have questions or need help, don’t hesitate to contact one of the TAs using Discord’s private messages or our public Discord channel. It is your responsibility to ensure that you have access to reliable internet connection, hardware, and software for the duration of the exam. Also make sure that you are comfortable using the usual tools from the class, so that you can focus on the exam.

Your answers are submitted by pushing your code on GitLab. Final 15 minutes of the exam are intended to account for the time necessary to upload your solutions and handle any technical difficulties. Late commits will not be graded, so make sure to use this time to carefully check that you submitted solutions to all of the questions.

*No cheating*: Each student must solve the exam individually. Consulting with anyone except the teaching staff of this course during the exam, copying solutions from the Internet, or making your solution available to anyone is considered cheating and a reason for disciplinary action. We will use plagiarism detection tools on your solutions. We reserve the right to follow up with some of you on Zoom after the scheduled slot and ask you about solutions to your or similar questions, whether or not we suspect you cheated; this possibility is a normal part of the examination this year.

## How to obtain questions

Assignments will be available online at the start of the exam. Please clone the following repository to have access to problem statements in case you lose your internet connection:

```
git clone TODO update link
```

Each assignment is published similarly to labs: the problem statements are given as markdown files in the following directory: TODO update links; the code skeleton for each problem is available in a separate branch of your private GitLab repository. Each student will receive a list of links to their questions before the exam by email.

## How to submit questions

Your answers are submitted by pushing your code on GitLab, just like the labs. After you submit your solution, you will receive a preliminary grade for that question. This information will be available in the GitLab CI. The tests executed on the CI are identical to those you can run locally. For detailed information, refer to labs submission instructions: https://gitlab.epfl.ch/lamp/cs210/-/blob/master/labs/grading-and-submission.md#committing-and-pushing-your-code.

You are allowed to push multiple times for the same question (only the last commit will be considered).

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

If you feel you are spending more time on the question and will likely not solve it, then go to step 6 to get a chance at solving the subsequent question. This way you will still get some points for the partially solved question. If you have time, you can go back to it later.

In the final 15 minutes of the exam, make sure that you submitted all your solutions.

## How do we grade the exam

Each question is worth 10 points. If you do not manage to solve a particular question, you can skip to the next one. This way you will get some points for partially correct solutions, as indicated in the grader output (a grade of 9/10 gives you 9 points for that question). 

You need to push your code to GitLab before the end of the exam to receive a grade. If you forget to submit your solution, your grade for that question will be zero.
