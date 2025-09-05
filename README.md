JSONPlaceholder API Testing Project

📌 Overview
This project demonstrates manual API testing using the public JSONPlaceholder API. The purpose is to validate CRUD operations, error handling, and data integrity for posts, users, and todos endpoints.

Base URL: https://jsonplaceholder.typicode.com/

🛠️ Tools Used
1.Postman – For executing API requests and running validation scripts.
2.Excel – For Test Cases, RTM, and Bug Reports.
3.JSON – Postman environment and collection files.

🚀 Project Structure
jsonplaceholder-api-testing/
│── environment.json        # Postman environment variables
│── collection.json         # Postman collection with test scripts
│── TestPlan.md             # Test plan document
│── TestCases.xlsx          # 25 positive and negative test cases
│── BugReport.xlsx          # Logged bugs from test execution
│── RTM.xlsx                # Requirement Traceability Matrix
│── README.md               # Project documentation

🧪 Test Cases
Total: 25 (Positive and Negative)
Endpoints Covered:
    /posts → GET, POST, PUT, PATCH, DELETE
    /users → GET
    /todos → GET

Focus Areas:
    Status code verification
    Response payload validation
    Error handling for invalid requests

⚡ How to Use
1,Import Environment & Collection:
    Open Postman.
    Import environment.json and collection.json.
    Select the environment.

2.Execute Tests:
    Run requests manually or use the Postman runner.
    Observe status codes, response data, and validation scripts.

3.Record Results:
    Update TestCases.xlsx with actual results.
    Log defects in BugReport.xlsx as needed.

4.Traceability:
    Use RTM.xlsx to track which requirements are covered by test cases and associated bugs.

📊 Deliverables
    Postman environment and collection files.
    Test Plan (TestPlan.md)
    25 Manual Test Cases (TestCases.xlsx)
    Bug Report (BugReport.xlsx)
    Requirement Traceability Matrix (RTM.xlsx)

⚠️ Notes / Limitations
    JSONPlaceholder is a fake API; changes via POST, PUT, PATCH, DELETE are not persisted.
    Some negative test cases may not fail as expected due to the nature of the API.
    All known issues are documented in the Bug Report.

📄 References
1.JSONPlaceholder Official Website
https://jsonplaceholder.typicode.com/?utm_source=chatgpt.com

2.Postman Documentation
https://learning.postman.com/docs/introduction/overview/?utm_source=chatgpt.com
