# QA-Compass
QA Compass is a single-page web application that gives a QA intern one place to plan tests, write and run test cases, log bugs, run user acceptance testing (UAT), manage test data, and produce a test report. It follows the real QA lifecycle so that an intern learns the working process while using the tool.

# Problem it solves
Interns often track work in scattered spreadsheets, chat messages and notes. This causes missing evidence, inconsistent bug reports, no clear view of testing progress, and weak reports. The Hub puts everything in one consistent, beginner-friendly workspace.

# Target users
•	Primary: QA / software testing interns and students.
•	Secondary: mentors and supervisors who review the intern’s work and reports.

# Objectives
1.	Teach the QA lifecycle through use: understand requirements, plan, design cases, execute, report bugs, retest, regression, UAT sign-off, report.
2.	Standardise how test cases and bug reports are written.
3.	Give instant visibility of progress through a dashboard and an auto-generated report.
4.	Let the intern enter any data freely, with no fixed project required.
5.	Keep a learning record through the profile and daily log.
   
# Scope
In scope: profile, dashboard, test plans, test cases, bug tracking, UAT, dataset upload and editing, report generation, daily log, search, filtering, CSV export (copy), backup and restore.
Out of scope (current version): multi-user accounts, server database, real-time sharing, file or screenshot upload, automated test execution, email notifications, integrations with Jira or TestRail.

# Design principles
•	Light theme, clean cards, large readable text.
•	Everything is a form or an editable table, so there is nothing to code.
•	Dropdowns use standard QA vocabulary so interns learn the correct terms.
•	Responsive: the sidebar becomes a horizontal menu on phones.

# System map
Sidebar sections and what feeds the report:
•	Dashboard reads from Test Cases, Bugs, UAT and Test Plans.
•	Test Plans define scope and criteria for the work.
•	Test Cases hold execution status, the main source for pass rate.
•	Bugs link back to a test case through the Linked test case ID field.
•	UAT records business acceptance.
•	Reports combine Test Cases, Bugs and UAT.
•	Dataset Upload supports test data used by cases (not counted in the report).
•	Daily Log and Profile document the internship.
