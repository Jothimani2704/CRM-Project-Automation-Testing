# Automation Testing Report – Securehands (Insurance-Based Company)

# Project Overview
* Company Name: Securehands
* Industry: Insurance
* Testing Type: End-to-End Automation Testing
  
# Tools & Frameworks Used:
* IDE: Visual Studio 2022
* Programming Language: .NET (C#)
* Test Framework: NUnit
* Automation Tool: Selenium
* Design Pattern: Page Object Model (POM)
  
# Objective
* The objective of this automation testing was to validate the functionality, stability, and efficiency of Securehands’ CRM system by automating end-to-end workflows. The automation process ensured minimal manual intervention while identifying critical issues.

# Scope of Testing
# Master Modules
* Product Module – Validation of product management functionality.
* Document Type Module – Ensuring proper classification and handling of document types.
* Document Store Module – Verifying document storage, retrieval, and security.
  
# Functional Modules Tested
* Login Module – User authentication, session handling, and security checks.
* Lead Module – Lead creation, updates, and assignment tracking.
* Prospect Module – Conversion of leads into prospects and follow-up management.
* Contact Module – Storing and managing customer contact details.
* Quotation Module – Generating, modifying, and validating insurance quotations.
* Proposal Module – Managing insurance proposals and approvals.
* Customer Module – Managing customer profiles, policies, and interactions.
* Policy Register Module – Verifying policy issuance, tracking, and modifications.
* Renewal Due Module – Ensuring policy renewal alerts and processing.
* User Module – Managing user accounts, permissions, and roles.
* Role Module – Role-based access control and authorization testing.
* Kanban View Module – Functionality of the visual workflow management.
* Dashboard Module – Ensuring proper analytics, reporting, and data visualization.
  
# Test Execution Summary
|Module	|Status	|Remarks |
|-------|-------|--------|
|Login Module	|✅ Passed	|Secure authentication verified|
|Lead Module	|✅ Passed	|Lead workflow working fine|
|Prospect Module	|✅ Passed	|Leads converted to prospects successfully|
|Contact Module	|✅ Passed	|No issues found|
|Quotation Module	|✅ Passed	|Quotes generated correctly|
|Proposal Module	|✅ Passed	|Functioning as expected|
|Customer Module	|✅ Passed	|No issues found|
|Policy Register Module	|⚠️ Issues Found	|Some policy updates not reflecting|
|Renewal Due Module	|⚠️ Issues Found	|Delayed renewal notifications observed|
|User Module	|✅ Passed	|No issues found|
|Role Module	|✅ Passed	|Permissions working correctly|
|Kanban View Module	|✅ Passed	|UI and workflow validated|
|Dashboard Module	|✅ Passed	|Data visualization accurate|

# Defects Identified
* Bug 1: Policy updates are not reflecting in real-time in the Policy Register Module.
* Bug 2: Delayed renewal notifications in the Renewal Due Module.
* Bug 3: Minor UI inconsistencies in the Kanban View Module.

# Key Findings & Observations
* Core functionalities across all modules are stable, with exceptions in policy updates and renewal alerts.
* Role-based access control is functioning as expected.
* UI responsiveness is consistent across tested browsers, except for minor glitches in the Kanban View.
* Automation scripts improved efficiency by reducing manual test effort.
  
# Conclusion & Recommendations
* Fix the identified defects in policy updates and renewal alerts.
* Enhance real-time synchronization of policy records.
* Optimize UI components in the Kanban View for a better experience.
* Consider integrating automation into CI/CD pipelines for continuous validation.
