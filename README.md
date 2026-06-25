SDLF Vs STLC
---

STLC - Software Testing Life Cycle

- The Software Testing Life Cycle (STLC) is strictly **focused on testing activities**. It `does not include` the actual development phase `where developers write code`.

- Instead, writing code belongs to the broader **Software Development Life Cycle (SDLC)**.

![alt text](stlc.png)


# Requirement Analysis Phase

## Overview

- test teams study requirements from a testing perspective to identify testable components. 

- During this critical phase, QA teams interact with stakeholders, including business analysts, product managers, and developers, to understand both functional and non-functional requirements comprehensively

## Activities
* Identify types of tests to be performed.
* Gather details about testing priorities and focus.
* Prepare Requirement Traceability Matrix (RTM).
* Identify test environment details where testing is supposed to be carried out.
* Automation feasibility analysis (if required).

## Deliverables
* RTM
* Automation feasibility repo


# Test Planning Phase (Test Strategy Phase)

## Overview
This phase is also called the **Test Strategy phase**. Typically, in this stage, a **Senior QA manager** will determine effort and cost estimates for the project and would prepare and finalize the **Test Plan**.

## Activities
* Preparation of test plan/strategy document for various types of testing
* Test tool selection
* Test effort estimation
* Resource planning and determining roles and responsibilities
* Training requirement

## Deliverables
* Test plan/strategy document
* Effort estimation document

 

# Test Case Development Phase

## Overview
- This phase involves creation, verification and rework of test cases and test scripts after the test plan is ready. 

- Test data, is identified/created and is reviewed and then reworked as well.

## Activities
* Create test cases, automation scripts (if applicable)
* Review and baseline test cases and scripts
* Create test data (If Test Environment is available)

## Deliverables
* Test cases/scripts
* Test data

  

# Test Environment Setup Phase

## Overview
Test environment decides the software and hardware conditions under which a work product is tested. Test environment set-up is one of the critical aspects of testing process and can be done in parallel with Test Case Development Stage. Test team may not be involved in this activity if the customer/development team provides the test environment in which case the test team is required to do a readiness check (smoke testing) of the given environment.

## Activities
* Understand the required architecture, environment set-up and prepare hardware and software requirement list for the Test Environment.
* Setup test Environment and test data
* Perform smoke test on the build

## Deliverables
* Environment ready with test data set up.
* Smoke Test Results.

  

# Test Execution Phase

## Overview
During this phase test team will carry out the testing based on test plans and test cases prepared.

## Activities
* Execute tests as per plan
* Document test results, and log defects for failed cases
* Map defects to test cases in RTM
* Retest the defect fixes
* Track the defects to closure

## Deliverables
* Completed RTM with execution status
* Test cases updated with results
* Defect reports

  

# Test Cycle Closure Phase

## Overview
Testing team will meet, discuss and analyze testing artifacts to identify strategies that have to be implemented in future, taking lessons from the current test cycle. The idea is to remove the process bottlenecks for future test cycles and share best practices for any similar projects in future.

## Activities
* Evaluate cycle completion criteria based on Time, Test coverage, Cost, Software, Critical Business Objectives, Quality.
* Prepare test metrics based on the above parameters.
* Document the learning out of the project.
* Prepare Test closure report.
* Qualitative and quantitative reporting of quality of the work product to the customer.
* Test result analysis to find out the defect distribution by type and severity.

## Deliverables
* Test Closure report
* Test metrics