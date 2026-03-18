
## Challenges

### Challenge 1: Analyze Training compliance using Data Insight Agent
**Introduction:**

Managers of each department need to understand team training compliance for Q1 2026 and send Director of HR report with latest status by the end of the day. The report should include:
- Training completion status for all employees
- Training completion status per department
- List of non-compliant employees
- List of completed courses
- List of pending courses
- Training completion rate

The report data needs to be presented in Graphical format using charts and graphs.

The required data is stored in BigQuery Data Warehouse `learning_campaign_tracker_admin` and spread across various Google drives across organization.


**Description:**
For this task you can use Google build Data Insight Agent (DIA) - `aiforeveryone-bq-dia`

The Data Insights agent is an agent that's Made by Google. It gives you data insights from your BigQuery data. With the Data Insights agent, you don't need prior knowledge of SQL. This lets you make well-informed, data-driven business decisions and frees up data analysts to focus on more complex tasks.

In our case DIA agent can handle complex requests like calculating completion rates or listing non-compliant team members for a specific department and generate report with charts and graphs.

**Success Criteria:**

* Training compliance report with charts and graphs is generated.
* Report is sent to Director of HR using `Send an email in Gmail` Gemini Enterprise action tool.

**Learning Resources:**

* [Get insights with the Data Insights agent](https://docs.cloud.google.com/gemini/enterprise/docs/data-agent)
* [Gemini Enterprise action tools](https://docs.cloud.google.com/gemini/enterprise/docs/action-tools)

**Tips:**
* Consider using `Send an email in Gmail` Gemini Enterprise action tool to send the report to Director of HR.

