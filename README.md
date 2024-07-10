# 1. Overview of software quality and testing
Software testing is a growing field - becoming extremely important as software touches more of what we do on a daily basis.

As software become complex, testing become more and more important.

Testing results in programmers producing better code.

Entry level software developers will be hired as testers first.

## Why testing and what is testing
- To find bugs
- A methodical investigation conducted to provide information on a software

### Types of testing and application
**V-Model / Waterfall**:
1. Requirement analysis
  - Acceptance test design
2. System design
  - System test design
3. Architecture design
  - Integration test design
4. Module design
  - Unit test design
5. Coding
6. Unit test
7. Integration test
8. System test
9. Acceptance design

-----

## Quality Assurance (QA)
A systematic monitoring and evaluation of different aspects of a product to ensure that quality standards are met

The goal of QA is to ensure that processes and procedures are followed and to improve the process with the goal to eventually improve the end product

- Reduce the probability of bugs slip into the software in the first place

### Programmers Involvement
- Programmers are involved in testing
- Programmers build well documented and formatted codes

-----

## ISO Certification
- International Standards Organization
- ISO 9000 process is the standard of QA
  - ISO 9001, ISO 9000-3 applies to software development

### Main goals of ISO 9000 process
1. Targets the development process
  - How does an organization complete its work
2. Proper organization process to achieve quality
  - What needs to be done
  - Does not enforce a particular method

**ISO 9000 & 9000-3**
- Configuration management
- Change control
- Development planning
- Design & implementation
- Testing & validation
- Maintenance

-----

## Software Testing Careers
- Test Technician
- Test Engineer
- Software Tester
- Test Automation Specialist
- Test Lead – Test plan developer/manager
- Test Manager – Oversees all testing within an organization 
- QA Engineer

Many software development jobs, also list software testing as a part of the job requirements

### Traits
- Like to Explore
- Likes to Troubleshoot
- Relentless
- Creative – Develop tests that will expose problems
- “Somewhat” of a Perfectionist
- Tactful
- Diplomatic
- Persuasive – Needs to convince people of the importance of correcting the bugs.
- Attention to detail

-----

## Quality of software
- Accurate/Complete Documentation 
- UI follows standards for the device/OS
- Behaves Accurately
- Behaves Predictably
- Behaves Reliably
- Behaves Consistently
- Does what the user/specification says it should do.

### Testing phase of development
**Waterfall**: once development is complete
**Agile/Spiral**: integrated throughout the development cycle

### Testing limitations
- Not all bugs will be found / fixed in any significantly large system
- You can’t write tests for all cases 
- Some bugs are too risky to fix
- It may not be worth it to fix the bug 

-----

# 2. Software Specification

A description of the correct operation of an application
- A list of requirements

## Specification and Documentation Testing
- Specifications usually have bugs
- Documentation usually have bugs
- The 1st chance for review
- Finding bugs at this stage is the most cost effective

### Spec & Doc testing reveals:
- Logic errors that would be much more expensive to fix
- Find gaps in understanding (client, developer, PM)
- Fully understand the scope and requirements
- Referred as: **Static black-box testing**
- Have clients involved early on
- No code exists at this point

#### 3 ways to evaluate the specification
- Put yourself in the place of the customer
- Research existing standards & guidelines
- Review & test similar software
  - Not always possible, but often possible

### Specification review questions
- Is it complete & accurate
- Is it consistent
- Is the information relevant to our product
- Is it feasible
- Is the spec code/technology free
- Can the specification be tested
  - Is it complete and specific enough to be tested

-----

## Types of documentation

**Manual**——Based on:
- Specification (the expected results)
- Based on correct operation (observed results)
- Supplied less frequently than in the past

**Completed Examples**:
- Tutorials that describe program operation

**Video Tutorials**
- Often supplied as the quick way to get started with application
- Becoming a preference for many users
- Sometimes used as training for new users

### Testing documentation

**Manuals**:
- Read manual for correctness
- Expect user review - Domain Knowledge
- Novice user review - Determines ease of use

**Completed Examples / Tutorials / Video**:
- Best tested by a novice, experts tend to gloss over "obvious" items for them
- Find user errors

-----

## Spec & Doc testing challenges

**Printed / Electronic Manuals**
- Users don't read
- Printing can be expensive
- Can quickly become out of date

**Completed Examples / Tutorials / Video**
- Based on previous versions
- Need version control to keep in check
- Video can also quickly become out of date
- UI changes resulting in manual update

-----

# 3. Exploratory Testing

Often thought of as a black box testing technique

Can be considered as a test approach that can be applied to any test technique, at any stage in the development

However, the key is the active engagement of the tester

## Exploratory Testing - Blackbox Testing
Access the program without source code available

Executed by applying an input that will produce a known response, and evaluate the response for correctness
- Independent/External validation

### Test to Pass
Normal data that a user would enter into an application
- Without error
- Not malicious
- Not attempting to break it
- The program should produce correct output

### Test to Fail
- Opposite of test to pass
- User is not using the program as expected
- An error message or correct guidance is expected

### Test case outcome
- Pass / Fail
- During test to fail, if the fail-case failed properly, then it's a pass

-----

### Test Cases
- A set / group of test data input

### Boundary Testing
- Used for an input that accepts a range of values
- Saves time
- Bugs are likely to occur at the bounds of an array

**Example of Boundary Testing**
- Just on lower boundary
- Just below lower boundary
- Just on higher boundary
- Just above higher boundary

-----

# 4. Test Plans
**To identify**:
- Requirements
- Resources
- Scheduling
- Involves the team (developers/marketing/management)

Key to success is communicating

## Test Plan Planning / Brainstorming
1. Purpose of the testing
2. What is in the testing scope?
  - What will be tested
  - what will be omitted
  - Degree or level?
3. What type of testing?
  - Unit testing
  - Integration Testing (Interface with existing systems)
  - Systems Testing
  - End User Testing / Acceptance Testing
4. Who will test it?
  - Programmers?
  - Testing Team?
  - Customers?
5. What are the quality goals?
  - "Must have" features working
  - "Nice to have" features working?
  - Max # of bugs found in the last iteration
  - Severe bug exists?

-----

## Test plan document
Actual look and feel of the document are company dependent

### Test plan - Starting and Stopping Testing
**ENTRY**
- Under what conditions can testing start?
  - Will we do it throughout the cycle?
  - Do we wait for development to complete? 
  - Documentation complete? 

**EXIT**
- When are we done? 
  - Quality achievement level has been obtained 
  - Bug detect frequency (i.e. # bugs/week)
  - Scheduling requirement – Deadlines

### Test plan - Resource Planning
Resources that should be defined in a Testing project.

- People **
- Equipment **
- Office Space 
- Software / Tools specific for the testing **
  - Reporting / Tracking software
- Outsourcing companies 
- Miscellaneous Supplies
  - Domain Reference material
  - Domain training material
- ** - important for small testing projects

### Test plan - Integration into Project

Testing must be integrated into the SDLC process, therefore:

1. list how the scheduling could be placed into the project.

**Hard Date scheduling**
- Fix start and stop dates.  
- **Advantages**
  - Eases scheduling / resource allocation
  - Only real solution for outsourcing situations
- **Disadvantages**
  - Difficult to control entry and exit conditions from a quality perspective.
  - Delays can compromise the testing process

2. list the second way the scheduling could be placed into the project.

**Relative Dates**
- **Advantages= **
  - Start date not set until “Entry Condition” for the test cycle is met.
  - Original estimates for testing time should be closer to reality.
- **Disadvantages**
  - Shifted time may not optimize resources.  
  - Testing team may be allocated to other projects in future——end up in a time crunch.

### Test plan - Classifying bugs

**When is it a bug**?
- Use project documents to confirm the expected behavior/result
- Project Specification may be used as the guiding document

**Bug classifications**:
1. Software doesn't work as specified
2. Software does something that the specification did not specify
3. Software does something that the specification says not to do

**Non-standard bugs**:
- Any unspecified / incorrect behavior should be reported
  - Simple: inconsistency in formatting, spelling
  - Major: crash, exceptions, BSOD
- General, the programmer failed to consider all cases when these bugs occur

-----

# 5. Web Site Testing

1. Web sites have a potential large audience
2. They are public
3. Quality of site reflect on the company
4. Need to be professional 

## Gray box testing
Partial view into the code on a web-page 
- HTML is visible some CSS/JavaScript may also be visible
- PHP is not visible at all——Blackbox

### Gray box testing - Items to review:

**Standard/modern tagging**
- Responsive design implemented for mobile devices

**Outdated features**
- These not well supported in new devices 

**Unwanted info in production code**
- Comments

-----

## High-quality website characteristics

**Unique**
- Content is mostly unique
- Content contains detail
- Content describes both sides of a story

**Expertise**
- Content is produced by experts
- Content is based on research and or experience

**Accessibility**
- A high-quality website supports all users regardless of device

**Usability**
- Can read / navigate the website easily

**Attention to detail**
- Free of spelling and grammatical errors

**Technically works**
- Links, Forms, User interaction work as specified

**SEO Optimization**
- Can be easily found on search engines

-----

## Website Testing
Testing of website by using a combination of different hardware and software
- Desktop / Mobile
- Important in a fractured hardware/software environment

Current Web/Mobile device environment is challenging for testing

### Compatibility checklist
1. Hardware platform 
  - Mobile vs desktop experience
2. Browser manufacturer 
  - Browser version
3. Plug-ins
  - If site relies on plug-ins, are they widely available
4. Speed 
  - Becoming less of an issue
  - 3% of Canadians STILL have no access to high speed

-----

## Strategies for website testing

- Review Market conditions
- Start at most popular and work to least popular
- Research tools to cut down workload

### Automation of testing
- Reduces time on testing.  
- Allow tester to focus on developing tests

**Things on website that can be automated**:
- Link Checking
- Spell Checking
- Form Validation Checking / Results Checking
  - Selenium / WebDriver
  - Katalon Automation
- Performance checking 
  - https://home.wpm.neustar.biz/  
  - http://www.webperformance.com/

-----

# 6. Bug Reporting & Resolution

## Relative Bug Cost
- Requirements:         $1
- Design:               $5
- Code:                 $10
- Development Testing:  $20
- Acceptance Testing:   $50
- In operation:         $150+

## Aspects of bug reporting
- When it is reported
- An effective description

### Effective Bug Description - user perspective
- Include OS Version, Software Build
- One bug per report
- Step-by-Step process to reproduce the bug

### Effective Bug Description - tester perspective
- Program Identification
- Version Information
- Date
- Reported by
- Suspected type of bug (Coding, Design, User Interface, Documentation)
- Reproducible (Y/N)
- Steps to reproduce
- Suggestions for correction 
- Summary

### Effective Bug Description - dev perspective
- Assigned to
- Status (Open/Closed)
- Priority
- Resolution 
  - Pending
  - Deferred
  - Withdrawn
  - Fixed
  - As Designed
  - Need more Info
  - Can't reproduce
- Resolved by with Date
- Solution Tested and confirmed with Date
- Version / Build should be included with the fix

-----

## Example Bug Workflow

### Step 1: Open

When a tester discovers an issue, they create a new bug report with the following details:

- Description of the problem
- Steps to reproduce the issue
- Expected results
- Actual results
- Test environment

The tester submits the report to the development team for review.

### Step 2: Resolved

Once the development team receives the bug report, they create a new task in their project management tool. They then assign the task to the relevant developer or team member. The developer will analyze the bug report and create a solution for the problem.

### Step 3: Review

The developer will then implement the solution and test the bug to ensure it is fixed. If the solution works as expected, they will update the task status to "Resolved" in the project management tool.

### Step 4: Defer

If the solution does not work as expected, the developer will update the task status to "Defer" in the project management tool. This indicates that the bug is still open and requires further investigation.

### Step 5: Closed

Once the issue is resolved, the developer will update the task status to "Closed" in the project management tool. This signifies that the bug is no longer open and the issue has been addressed.

-----

## Responsibilities

The programmer is responsible to confirm the bug report:

- Not a Bug (as designed)
  - Move to Closed
- Bug——Defer or Resolve

The tester must confirm the bug resolution or fix: 
- The applied fix worked - Move to Close
- Still a Bug——Fix did not work/incomplete
  - Move back to Open
