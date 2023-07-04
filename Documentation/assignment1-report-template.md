>   **SENG 637- Dependability and Reliability of Software Systems**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group \#:       |  24 |
|-----------------|---|
| Student Names:  | Anita Santoshkumar Das  |
|                 | Archi Maheshkumar Patel  |
|                 |   |
|                 |   |

**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

Software testing is the crucial step in software development process. Here in this lab, we are testing an ATM system using different methods of software testing in v1.0 and v1.1. It includes going through different functionalities of the system and track bugs/ defects from it. We perform testing using Exploratory Testing, Manual Functional Testing and Regression Testing. The process of testing will be done step by step. Each and every functionality will be tested in order to find bugs. Main functionalities of  an ATM system like Withdraw, Deposit, Transfer, Insert card, generate receipt, etc will be checked in detail. Tracked defects are reported in Backlog system in order to save and generate report.

Before this lab, we only heard about the concepts like Exploratory Testing and Manual Functional Testing, but were not aware about it in detail. We had not experience in testing, but this lab helped us know almost everything important and necessary for software testing process. We learnt how to generate several test cases which help in finding bugs. We came to know about requirements, pros & cons, comparison about every testing methods.

# High-level description of the exploratory testing plan

We planned to analyze the system and try to know what are the features of the system and how the system works. Then, we checked the requirements of the system. We came to know about the basic flow of the system which include several steps; turn system ON, Insert card details, verifying it and proceed, choose transaction and generate receipt. Firstly we started the system by the given card i.e card no 1 and card no 2. Moreover we used the both PIN no to make system work. After that, we have to select the trasaction type among four transaction i.e withdrawl, deposit, transfer and balance inquiry. In withdrawl, there are three account present in which you can withraw from that particular account. Then enter amount that we want to withdraw but make sure the amount is not greater than our system contains. Finally, By doing step by step procedure we are willing to complete the test case and found bugs.

We first divide the task between us, analyze the system, cross-checked and then performed. We tested for the v1.0 and found the various bugs in this system. Then we noted  all the bugs which is present in v1.0. After that we tested the v1.1  and also noted the defects/bugs. By comparing this, v1.1 to the v1.0 what we experienced that v1.1 has some of the bugs that are resolved.

# Comparison of exploratory and manual functional testing

Exploratory testing involves investigation process which helps the testers to find more bugs than other testing methods, while in manual functional testing it involves confirmed testing. More, By doing exploratory testing it improves the test design but in manual functional testing it is controlling the tests. Exploratory testing provides the freedom in testing process, which is very convenient, while in manual functional testing we are bound to the flow and restricted to the predefined test-cases. In exploratory testing, the determination of the test case is done during testing but in manual functional testing the determination of the test case is done in advance or before testing. Exploratory Testing is more simpler than the scripted testing as it doesn’t require pre-tested cases and it is spontaneous. Exploratory testing uses creativity of the tester which can be more varied than the test cases of Manual Functional testing. The benefit we get in exploratory testing is that one bug draws towards other. Moreover, in exploratory testing, we can not predict number of bugs which will be very time consuming for improper or large systems. While, in Manual Funational testing we have definite number of test cases, thus limited number of bugs. Furthermore, in Exploratory, testing cannot be reproduced only the defects can be reproduced while in manual, the testing can be easily reproduced.

# Notes and discussion of the peer reviews of defect reports

The defect reports contain variety of test cases of v1.0. The defects were properly described and it was very clear to understand. Additionally, all the details were gathered in an accurate manner. For instance, 
a. The function being tested: Transfer.
b. The initial state of the system: System is displaying a request for the customer to type a dollar amount.
c. Steps to reproduce the defect/bug : Turn system ON -> then insert card number 1 -> enter PIN 42 -> choose transfer transaction type -> choose account checking from -> choose account savings to -> enter amount to transfer
d. What was the expected outcome: System prints a correct receipt showing amount and correct updated balance; System records transaction correctly in the log (showing both message to the bank and approval back).
e. What was the actual outcome: System prints a wrong receipt showing amount and wrong updated balance.

# How the pair testing was managed and team work/effort was divided 

We are a group of two members, divided our work in such a way which helped us to manage time. Pair testing is one of important steps in testing according to us as it involves two-way verification. It helps to correct one another when and where necessary. One has the control on computer, keyboard and mouse and performing several tasks while other was noted the bugs, asked questions and makes suggestions. There are many advantages by doing pair testing. To exemplify, we both applied our unique skills to find the bugs and by doing this we can gain more insight. We both collaborate as a team which will decide what is working well, what is not working, what need to be changed and fixed. One was working on 1.0 and found bugs and another was working on 1.1 and also found bugs. On the next day, we tested the system viceversa. So that we got to know the real bugs.This testing is crucial because it help the each team member to learn from each other and we both participants were equally contributed our thoughts, ideas and suggestions.

# Difficulties encountered, challenges overcome, and lessons learned

During testing of ATM system, we found several difficulties such as knowing the system deeply on our own. It is very important to know each and every feature of the system thoroughly in order to find even tiny bugs. The other difficulty is in how to report the bugs that we found during exploartory testing because it is not easy to explain the bug without predefined test cases. Moreover, in exploratory testing we cannot predict number of bugs, so we do not have particular cases to work on. In Manual Functional Testing, creativity of the tester is restricted by limited number of test cases which indirectly makes testing difficult during exploratory process.

We overcame this difficulties by knowing the requirements of the system deeply. This helped us to check the system for defects more and more. To make defect tracking efficient, we performed pair testing, then exploratory testing individually by both of us and lastly regression testing. We performed Exploratory testing before Manual Function testing so that the thought can be more broader.

By this lab, we learnt how to report bugs in defect tracking system. How to test several test cases, how to question yourself to find and identify bugs. This lab played a vital role in improving knowledge towards software testing. Moreover, we learnt how to work as a team, so we can give maximum output.

# Comments/feedback on the lab and lab document itself

It was a great experience working in this lab. This lab made us clear about different types of testing. Each type of testing plays significant role in its own way. Overall, the lab document gives clear idea about testing process.
