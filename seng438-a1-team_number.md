>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: Group Number      |
|-----------------|
| Chun Lok Chan                |   
| Yousif Alomar              |   
| Aly Mohamed               |   
| Lujaina Eldelebshany                |   


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

This lab dives into the comparison between exploratory and manual bug testing, and increases our knowledge with testing platforms such as Jira/Azure DevOps. Team 10 preferred to use the Azure DevOps platform, and priot to this lab, all 4 teammates knew nothing about manual functing testing. However, intuitively, we knew that exploratory testing involved no concrete plan and simply 'using the software' in as many different ways as possible to try to 'break the code', or find bugs through functionality that shouldn't happen the way it does. It is also important to note that we recognize that exploratory testing involves a random process that does not have any sort of agenda, and can be kept track of through the functions that have already been tested, as opposed to a formal test suite. Therefore, the same functionality may be tested many times over, thereby extending the amount of time taken to complete exploratory testing, and risks the tester not being able to locate all the bugs, since no functionality table was predetermined. 

# High-level description of the exploratory testing plan

Plan: Testing all functions a little bit repetitively until their expected output is recognized, then comparing the received output to what is actually being output and ensuring they match
Functions being targeted: 
- Clearing the log
- Depositing money into either account accurately
- Withdrawing money into either account accurately (and managing over-withdrawals)
- Checking account information
- Checking the balance inquiry on the money market
- That using the correct pin for the correct card works consistently
- The ‘enter’, ‘clear’, and ‘cancel’ buttons work in all contexts as intended
- Showing the log doesn’t forget any parts of the log, or clear an earlier instance of the log

How you plan to come up with test cases: Just using the ATM and if there is a feature not working the way we as the testers expect it to, we identify it and log it as a bug. 


# Comparison of exploratory and manual functional testing
EXPLORATORY
benefit: dynamic and flexible, so if the system changes, the tests are easily accomodating. It also tests the system from the perspective of the user as opposed to someone who already knows the system's development. Very cost-effective since close to no planning time/resources are allocated to exploratory testing.
tradeoff: will take much longer time to complete exploratory testing that has the same quality standard as scripted manual function testing
effectiveness: Random testing makes this type of testing very effective due to more intuitive tests being completed, which more closely mimics user behaviour. 
efficiency: low efficiency for waterfall environments but high efficiency for agile environments since to test a singular function, exploratory testing has to cover only one or two features, so there is very limited variety between testable features that can potentially be missed in the user's perspective. However, waterfall development exploratory testing will put much pressure on the tester to think of many seperate cases where the system could fail, which puts much risk on something that may generate human error. 

SCRIPTED MANUAL FUNCTION
benefit: not random, so no potential bugs are being missed because they are all pre-written. This technique is also reliable and documented, which means the tests can be verified, looked back on, and do not have to be stored entirely within one person's experience and knowledge. 
tradeoff: no room to consider tests that have not been previously written, and are very rigid so these tests will not be well-accomodating to systems that change.
effectiveness: highly effectiveness, as having a clear head allows the tester to write a table of tests before the testing begins, so more of the 'all possible cases' are being tested. Additionally, scripted manual testing allows for regression testing to take place easily since functionality that was verified to work correctly before the system's features changed can be tracked to ensure they remain working properly. 
efficiency: high efficency since the tests completed using this technique are reliable and repeatable. Also, this technique allows testing to be completed by more than one tester at the same time since tests from the table (such as Appendix C) can be assigned to different human testers, with the results of the tests documented for all to see. 

# Notes and discussion of the peer reviews of defect reports
TODO
-   Note that you need to submit a report generated by your defect tracking
    system, containing all defects recorded in the system.

# How the pair testing was managed and team work/effort was divided 

Lujaina/Aly tested together (group 1), and Yousif/Chun (group 2) tested together. The team effort was divided equally between the group members, so group 1 completed testing on the 1.0 jar file, as well as the exploratory testing. Group 2 completed testing on the 1.1 jar file. Afterwards, regression testing was completed by the team as a whole. 

# Difficulties encountered, challenges overcome, and lessons learned
TODO
Text…

# Comments/feedback on the lab and lab document itself
TODO
Text…
