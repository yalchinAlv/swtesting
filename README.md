# swtesting

1. Review
* Explain code inspection process.
    * Formal process
    * There are typically formal entry criteria a product has
to fulfill
    * The moderator leads the inspection (review)
meeting; the content is presented by a reviewer (not
the author!)
* major difference between walkthrough and code inspection.
    * walkthrough: informal, no time limit, author presents
    * code inspection: formal, time limit, reviewer presents
* Review advanteges and disadvanteges.
    * Cheaper defect elimination
    * Early defect detection!
    * Typical costs are ~ 10 % of the development budget
    * Savings are estimated to be about 14-25 % (extra effort
for the reviews already included)

2. Decision tables
* What are they explain?
* advanteges disadvanteges
* draw a decision table and get a test case out of it.

3. Chrome driver code snippet.
Uses object pattern to get some information out of webpage.
The test cases are green. But find 5 problems in the code.

4. unit test, integration, system, acceptance.
* (every one of them) -> What does it check? who checks it?
* The test from task number 3, on which test level does it execute? And why do you think so?
* What is a test oracle?
* 3 types of test oracle?

5. TestModel of stack given. Draw the full state machine of the stackmodel.
* Code snippet given, add adapter to the stackmodel. The exactly same snippet as in the exercises.

6. Evaluation of software quality metrics approaches: 
    * benchmarking
        * comparing a software project with other
excellent projects
        * If benchmark-base contains bad projects -> bad results
        * Can be carried out automatically -> Can be done more frequently
        * Lack of interpretation of results - by definition, as no expert has a look on
the data
    * expert
        * Expert uses results from static analysis as indicators
        * knows thresholds, which metrics / rules are important
        * Leads to detailed analysis of code
        * False-Positives are considered
        * Time consuming, high effort
        * Not objective; different experts will come to different
conclusions
    * formula
        * Normalizing measurement results
        * Normalization by relative code proportion affected
        * Normalization was supported by guidelines + four-eye principle

* Which one of them would you prefer and why?

7. Execution tree of some code given, if(a?) left right (if b?) left right, final. (very simple)
* How many test cases do you need? (multiple choice)
* Full statement coverage? 1,2,3,4
* Full decision coverage?1,2,3,4
* Full path coverage?1,2,3,4
* Mutation testing: If we mutation test the above codeexecutiion tree, will a statement coverage kill all mutants? yes no and why?
