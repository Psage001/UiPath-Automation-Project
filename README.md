# CMPG323-Project-4-38467992
CMPG323-Project 4
# UiPath Automation Project

This repository contains a UiPath project that automates data interaction between Excel and a web application. The project reads data from an Excel file, manipulates it within a DataTable, interacts with a web API by creating records, and performs UI automation tasks such as clicking buttons, handling datepickers, and working with dropdown lists. It also includes functionalities to update or delete records and integrates with UiPath Orchestrator. Additionally, the project updates a "Test Result" tab in Excel to track the automation results.

## Getting Started

These instructions will guide you on how to get a copy of the project and run it on your local machine for development and testing purposes.

### Prerequisites

Before you start, ensure you have the following software installed on your system:

- UiPath Studio (Version: Specify the version you're using)
- Microsoft Excel

### Installation

Follow these steps to get the project set up:

1. Clone the repository to your local machine using git clone <repository-url>.
2. Launch UiPath Studio and open the project.
3. Ensure that all the necessary packages are installed (UiPath.Excel.Activities, UiPath.System.Activities, UiPath.UIAutomation.Activities, etc.).
4. Configure the Excel file path and web API details in the project's configuration file or Orchestrator Assets.

## Usage

To use this project:

1. Open the Main.xaml file in UiPath Studio.
2. Update the input Excel file path in the 'ExcelFilePath' variable.
3. If necessary, update the API endpoint URLs and authentication details.
4. Run the project from UiPath Studio or publish it to the UiPath Orchestrator for triggering from there.
5. The robot will read the data from Excel, interact with the web application, and update the test results in the specified Excel tab.

## Features

- Excel Integration: Reads data from Excel and updates the "Test Result" tab.
- Data Manipulation: Uses DataTables for in-memory data manipulation.
- Web Automation: Creates records in the web application, clicks buttons, selects dates from datepickers, and chooses options from dropdown lists.
- CRUD Operations: Updates and deletes records in the web application.
- Orchestrator Integration: Publishes the project to UiPath Orchestrator.
- Error Handling: Implements robust error handling and logging.

- 
## Reference list

1. *UiPath Documentation*: The official UiPath documentation is a comprehensive resource that covers all activities and their properties. (https://docs.uipath.com/)

2. *UiPath Forum*: A community forum where you can ask questions and find answers on various UiPath topics. (https://forum.uipath.com/)

3. *UiPath Academy*: Offers training materials and tutorials on various UiPath functionalities. (https://academy.uipath.com/)

4. *Excel Activities Guide*: A guide on how to automate Excel with UiPath. (https://docs.uipath.com/activities/docs/excel-application-scope)

5. *DataTable Activities Guide*: Documentation on how to manipulate data stored in DataTables. (https://docs.uipath.com/activities/docs/datatable-activities)

6. *HTTP Request Activity Guide*: A guide on how to use the HTTP Request activity to interact with a web API. (https://docs.uipath.com/activities/docs/http-request)

7. *Working with UI Elements*: A guide on automating UI elements on a web page. (https://docs.uipath.com/studio/docs/ui-automation)

8. *Orchestrator Guide*: Learn how to deploy, manage, and log workflows with UiPath Orchestrator. (https://docs.uipath.com/orchestrator)

9. *Publishing a Project*: A tutorial on how to publish your automation project. (https://docs.uipath.com/studio/docs/publishing-a-project)

10. *Error Handling in UiPath*: A guide on how to handle errors in your automations. (https://docs.uipath.com/studio/docs/exception-handling)

11. *Debugging in UiPath*: Learn how to debug your workflows. (https://docs.uipath.com/studio/docs/debugging)

12. *UiPath Best Practices*: An article on best practices in UiPath. (https://docs.uipath.com/studio/docs/best-practices)

13. *Using Arguments in Workflows*: Understand how to pass data between workflows. (https://docs.uipath.com/studio/docs/using-arguments)

14. *Automation Cloud Guide*: How to manage your UiPath Automation Cloud account. (https://docs.uipath.com/automation-cloud)

15. *UiPath Marketplace*: Find ready-made components for your project. (https://marketplace.uipath.com/)

16. *Logging and Tracing*: Learn about logging and tracing in UiPath. (https://docs.uipath.com/studio/docs/logging-and-tracing)

17. *Selectors in UiPath*: Understand selectors and how they work. (https://docs.uipath.com/studio/docs/selectors)

18. *Building Bots with UiPath Studio*: A step-by-step guide to creating bots in UiPath Studio. (https://docs.uipath.com/studio/docs/building-bots)

19. *Data Scraping Guide*: Learn how to extract data from websites or applications. (https://docs.uipath.com/studio/docs/data-scraping)

20. *File Change Trigger*: Trigger a workflow by monitoring changes in a directory. (https://docs.uipath.com/activities/docs/monitor-events)

21. *Working with JSON in UiPath*: A guide on parsing and using JSON data. (https://docs.uipath.com/activities/docs/json)

22. *UiPath RPA Coding Standards*: Coding standards in UiPath RPA development. (https://docs.uipath.com/studio/docs/rpa-coding-standards)

23. *Using Variables*: A guide on variable types and scopes. (https://docs.uipath.com/studio/docs/variables)

24. *Advanced Ui Interaction*: Learn about advanced UI automation concepts. (https://docs.uipath.com/studio/docs/advanced-ui-interaction)

25. *Automating Web Applications*: A guide on automating tasks in web applications. (https://docs.uipath.com/studio/docs/web-automation)

