# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [x] Add datasets used to the `datasets/` folder

#### Files

- [x] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [x] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix`

#### Learning Objective

Objective: Create a Subtotal Measures based on the Balance Sheet layout and a Measure that will display the correct measure based on the line item of the layout and display it on the report.

#### Context

Merging multiple measures intoa single column is valuable to provide a user control over the report. This exercise combines understanding of measures created and Balance Sheet layout.  

#### Steps to be executed by the student (max 6)

Step1: Create a new measures for Current Assets, Fixed Assets, Total Assets, Current Liabilities, Non-Current Liabilities, and Libailities & Equity
Step2: Create a new measure called BSValues
Step3: Write a switch formula for every line that is not blank, unluding sub-totals
Step4: Save the measure
Step5: Display it on the report
Step6: Format the column to match the coloring of the description column


#### Exercise question:
Do the totals for Total Assets and Liabilities & Equity equal?

#### End goal:

![image](https://user-images.githubusercontent.com/43157508/215370021-7ee11907-db36-4cc4-bab3-36fe712f5d65.png)


## 2nd VM Exercise

#### Dataset

- [x] Add datasets used to the `datasets/` folder

#### Files

- [x] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-2-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [x] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix`

#### Learning Objective

Create a Balance Control Calculation as an automated check on whether Total Assets equial Liabilities & Equity. Check if the balances equal, and fix if they are not.

#### Context

This happens all the time in development of a balance sheet. Assets must always equal Liabilities & Equity. If they do not, the balance sheet is not balanced and there is a mistake in account mapping or a calculation.

#### Steps to be executed by the student (max 6)

Step1: Create a Balance Control measure that evaluates the difference between Total Assets and Liabilities & Equity
Step2: Place the Measure on a report, below the table
Step3: Find the cause of the difference.

#### Exercise question:
What is the reason for the Balance Sheet outage, and why does it not exactly equal any of the line amounts?

#### End goal:

![image](https://user-images.githubusercontent.com/43157508/215370883-6fa371a4-e442-480c-8a90-b2f70464f798.png)

