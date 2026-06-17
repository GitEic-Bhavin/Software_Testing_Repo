Types of Testing
---

**1. Black Box Testing**

- You have to testing for frontend , backend components

- Whatever code has written behind this components that you dont have to look and that is not of your business.

- You just have to testing over this components and generate reports.

**2. White Box Testing**

- You have to make sense that how frontend , backend and all components coding working

- You have to test with concept of this code and generate reports.

**3. Regression Testing**

- Make ensure currently fixed bugs shouldn't face in future. How ?

If you have modules like Module A, Module B like frontend, backend

- While you fixed bugs of Module A and clinet meets requiremetns. Now you will starts testing for Module B as `Agile Model`.

- **When you test the previously delivered module, again, that is called as a regression testing**.

**4. Retesting**

- When you find bugs during testing , you will report to developer.
- Developer will fix issus by debugging and update module or code.
- You will re test that module or compoenets once developer has fixed.

- You will **Not Test Previous dependent all Modules** here.

- So, This is `Retesting`.

**5. Functional Testing**

- I have Taxi Booking applications.

- I will check for its functionality like  `wheather i am able to book taxi or not ?`

- `If i'm not able to book taxi, wheather applications raise a customer support ticket or not ?`


**6. Non-Functional Testing**

- I will check application for load , volume , stress.

- How much load, stress can handle by applications.

- Wheather application is standaloen during high traffic peak ?

- Wheather application crashing or able to process all trafficd and 0 downtime , high latency or low latency ?

- By performing load testing - Increase load like send multiple request like 80k to the applications.

**7. Security Testing**

- A security tester will look for how your applications is being secure.

- How your application may be compromise ?

- How your users credetials is storing into secure place or breaching credentials ?

**8. Usability Testing**

- **Checking whether an application is easy to use, easy to understand, and user-friendly for the end user**.

- The goal is not to find functional bugs. The goal is to verify that users can perform their tasks easily without confusion, frustration, or unnecessary steps.

**Functional Testing Question**

- Can the user transfer money successfully?

- Is the amount deducted correctly?

- Is the transaction recorded?

**Usability Testing Question**

- Is the "Transfer Money" button easy to find?

- Are the instructions clear?

- Can a new user complete the transfer without help?

- Is the screen cluttered with too many options?

**9. Smoke Testing**

- Once you tested all functionality, all components and its working well.

- Then you will not recheck , retest again for all of this before deliver to the customer

- You will ensure all functionality test results are healthy before deliver to the customer

- Just like we look into checksheet for all requirements with expected output and actual output after testing.

**10. Alpha Testing**

- Alpha Testing will always done from `Developer side` only.

- Once you tested whole applications components, functionality and before deliver to the customer

- You will call to developer which is working outside to your org.

- This external developer will test your builded and tested applications from their side.

- Bcz, This external developer have diff kind of experience level and understanding of testing.

- They may able to find out bugs, issues which has not found by our org testing team yet.

- Which will lead to prevent from reoccuring in the future by - pre-fixed it.

- 1 External developer may say, Your products can do this or this much functionality working well but if your add this feature it will become user-friendly and may become popular.

**11. Beta Testing**

- Beta testing is the type of testing which is done at the client offices or basically to the end users place.

- any feedback or any inputs they have is passed on to the company which has developed that particular product.

**12. Compliance Testing**

- If you will see there are lot of products which need security compliance.

- There are lot of products which really need to comply to some rules.

- So when you are actually testing such products, you need to make sure that they are following those

- `Compliance testing is the type of testing which is done on the products to make sure that the product complied to the specific rules and regulations`.

**13. Stress Testing**

**14. Volume Testing**

**15. Install Testing**

- Install application in the end user side and testing the applications.
- Installed successfully or not?

**16. UnInstall Testing**

- Uninstall applications.

**17. GUI Testing**

- Is done many times for your mobile app, web.

- UI is meet to as per clinet requirement or not ?

**18. Browser Compatibility Testing**

**19. Ad-Hoc Testing**

- 

**20. Recovery Testing**

**21. Backend Testing**

- Frontend and Backend

- We will not testing frontend to test backend. like we will not generate load, access web page to retrive data from database backend.

- We will directly test backend by executing query.

- If query success - test pass, If query failed - test failed.

**22. Exploratory Testing**

- Exploratory Testing is a software testing approach where the tester simultaneously:

* Learns the application
* Designs test scenarios
* Executes tests

without relying heavily on predefined test cases.

The tester actively explores the application like a real user to discover defects that may not be found through scripted testing.


## Simple Definition

> Exploratory Testing is "learning, test design, and test execution happening at the same time."


## Real-Life Example

Imagine you purchase a new smartphone.

Instead of reading the manual, you:

* Open different applications
* Change settings
* Connect to Wi-Fi
* Rotate the screen
* Install apps
* Press various buttons

While exploring, you may discover crashes, freezes, or unexpected behavior.

This is similar to Exploratory Testing.


# Traditional Testing vs Exploratory Testing

| Traditional Testing           | Exploratory Testing                       |
| ----------------------------- | ----------------------------------------- |
| Follows predefined test cases | No detailed test cases required           |
| Structured approach           | Flexible approach                         |
| Tests known scenarios         | Discovers unknown scenarios               |
| Focuses on validation         | Focuses on investigation                  |
| Less creativity required      | Requires creativity and critical thinking |


## Example: Login Functionality

### Scripted Testing

Test Case:

1. Enter valid username
2. Enter valid password
3. Click Login

Expected Result:

* User logs in successfully



### Exploratory Testing

Tester may try:

* Empty username
* Empty password
* Special characters
* Very long input values
* Refresh browser during login
* Multiple login clicks
* Multiple browser tabs

Goal:

* Discover unexpected defects


# Why Exploratory Testing is Important

Many bugs are not covered by documented test cases.

Example:

A user clicks the "Submit Order" button 10 times quickly.

Result:

* 10 duplicate orders are created.

Such issues are often discovered through exploratory testing.


# Key Characteristics

### Simultaneous Activities

The tester:

* Learns
* Thinks
* Tests

at the same time.

### User Perspective

The tester behaves like an actual end user.


### Flexible Testing

No strict dependency on written test cases.


### Creative Approach

The tester uses experience and curiosity to uncover defects.


# Skills Required for Exploratory Testing

## Curiosity

Ask:

> "What happens if I try this?"


## Analytical Thinking

Ask:

> "What can potentially fail here?"


## User Mindset

Think like an end user.


## Domain Knowledge

Understanding the business domain helps identify hidden defects.


# Common Areas to Explore

## Input Fields

Test:

* Blank values
* Special characters
* Invalid formats
* Long inputs


## Buttons

Test:

* Double click
* Rapid clicking
* Click during loading


## Navigation

Test:

* Browser back button
* Browser refresh
* Multiple tabs


## File Upload Features

Test:

* Large files
* Unsupported formats
* Corrupted files


## User Sessions

Test:

* Session timeout
* Multiple logins
* Logout behavior


# Advantages

- Finds hidden defects

- Mimics real user behavior

- Encourages critical thinking

- Useful when documentation is incomplete

- Detects issues missed by scripted testing


# Limitations

- Difficult to measure test coverage

- Depends heavily on tester skill

- Hard to reproduce if notes are not maintained

- Not suitable as the only testing approach

---

# Real Defect Example

Scenario:

1. Add product to cart
2. Open another browser tab
3. Remove product in first tab
4. Complete checkout in second tab

Expected Result:

* Checkout should fail or refresh cart

Actual Result:

* Order is placed for removed product

This is a defect commonly discovered during exploratory testing.


### Q1. What is Exploratory Testing?

**Answer:**

Exploratory Testing is a testing approach where testers learn the application, design test scenarios, and execute tests simultaneously without relying heavily on predefined test cases.


### Q2. Is Exploratory Testing Functional or Non-Functional Testing?

**Answer:**

It is a testing approach rather than a specific testing type. It can be used for both functional and non-functional testing activities.


### Q3. Can Exploratory Testing be performed without test cases?

**Answer:**

Yes. Exploratory Testing is often performed without predefined test cases and relies on tester experience, creativity, and investigation skills.


### Q4. What is the main objective of Exploratory Testing?

**Answer:**

To discover defects, risks, and unexpected behaviors that may not be identified through scripted testing.


# Quick Revision

| Question                     | Answer                                                             |
| ---------------------------- | ------------------------------------------------------------------ |
| What is Exploratory Testing? | Testing by exploring the application without predefined test cases |
| Main Goal?                   | Find hidden defects                                                |
| Who performs it?             | Testers using experience and creativity                            |
| Test Cases Required?         | No                                                                 |
| Biggest Advantage?           | Finds defects missed by scripted testing                           |
| Biggest Challenge?           | Coverage is difficult to measure                                   |

How to write Test Cases
---

Mobile Applications

| Testcase No | Assumptions | Testcase Criteria | Testcase Steps | Expected Results | Actual Results | Testcase Results |
| ----------- | ----------- | ----------------- | -------------- | ---------------- | -------------- | ---------------- |
| TC_001 | <Write your possibility to test> | <On which criteria you will test> | <Write your steps>  | <what should be results> | <what is actual results> | <Pass/Fail> |
| TC_001 | Mobile app is avaiable for the user to test | Check if the controls are as peruser spec / requirements | 1. Launch mobile app.     2. Check for the controls | The controls should be as per the user specification(Checking for the font, font style,colour, logo) | The controls are as per the user specification | Pass |

![alt text](tcma.png)

BugZilla
---

If `Expected Result` and `Actual Result` output are same , its `Pass`.

If `Expected Result` and `Actual Result` doesn't match its `Fail`. `Fail` == `Bug`.

- `Bug`, `Defact`, `Fail` are Same Things

- Once you find the `Bug` you have to raise and log the `Bug`.

- For that we will requires some software where we can log the Bug.

- Whenever you log the bug you will requires:
  
  1. Title the Bug - Name of bug
  2. Reporter - The name of reporter , who find out bug ?
  3. Priority of the Bug - Low, Medium, High
  4. Sevarity of Bug - 
  
    - `ShowStopper or Bocker` - Which we can't test of this bug. Like, you tested web url - you found 404 Error - which can't be test by tester. Will be done by Developer.

    - `Critical bug` - Some components/functionality not works, Apps slow downs.

    - `High Bug` - Low critical.

    - `Low/Enhancement`

  5. `Assigned to` - Who is actual working on it.

  6. `Date & Time` - While reported bug.

**BugZilla**

- It will helps you to generate `Bug Reports`.

- Like, `800 Bugs` has reported, `X no. of bugs has been resolved`, `Y no. of bugs has moved to released`, `Z no. of bugs are Pending`.

- You can manage bugs and Diff Project on this `BugZilla`.

- This is just like `Jira Tool` where we manage diff tickets, projects and we can track all ticket status.

- Create BugZilla account.

- Create bugs

- Give Bugs Title.

- Write steps for what did you performed ?

![alt text](bzsp.png)

- What is actual results and expected results

- Choose sevarity.

![alt text](bzrs.png)


- Raise bugs

- Set Priority P1 and choose higher number == Higher Priority

- Set sevarity

- Choose on which platform this bugs found on linux, windows ?

![alt text](bzfd.png)

- Add Assign to and put comment on this bugs

- ![alt text](bzcm.png)

WireFrame TestCase
---

- Wireframe Testing means reviewing and validating the wireframe (UI design blueprint) before actual development starts.

- A wireframe is a simple visual layout of a webpage, mobile app screen, or software screen showing:

  - Buttons
  - Text fields
  - Menus
  - Navigation flow
  - Page structure

- without colors, images, or actual functionality.

- Check all possibilities as we earlier did.

- **Test Case** - Individula rows in the test cases files

- **Test Script** - Whole page of test case files / Combine all Rows of test cases.

