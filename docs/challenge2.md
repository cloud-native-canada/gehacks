### Challenge 2: Discover data using Gemini Enterprise Connectors

**Introduction:**

After close assessment of the aggregated training compliance report presented by managers it was found that over 50% of employees are not compliant with training requirements. Company leadership decided to implement a training scheduler agent to help employees and managers track and complete their mandatory training before end of March deadline.

The training scheduler agent will help employees and managers track and complete their mandatory training. It will also help managers to schedule time for their employees to complete their mandatory training.

Before an agent can act, it needs access to information in datawarehouse. You role is to prepare prompts that you agent can use to fetch data from datawarehouse. You need to make sure the data is accurate and good quality. 

**Description:**

In this challenge, you will use Gemini Enterprise search capabilities in order to craft a prompt for a Data Store connectors (BigQuery and Google Drive) that will allow your agent to fetch data from datawarehouse.

The data source are stored in BigQuery Data Warehouse `learning_campaign_tracker_admin` and spread across various Google drives across organization.

**Success Criteria:**

* Develop set of prompts that you agent can use to fetch data from datawarehouse.
* Ensure the data is accurate and good quality.


**Learning Resources:**

* [Gemini Enterprise Use Case: Personalized Onboarding](https://docs.cloud.google.com/gemini/enterprise/docs/use-case-personalized-onboarding)
* [Gemini Enterprise Use Case: Onboarding Training](https://docs.cloud.google.com/gemini/enterprise/docs/use-case-onboarding-training)

**Tips:**

* Use BigQuery connector `learning_campaign_tracker_admin` for plain English data retrieval.
* Use Google Drive connector for plain English data retrieval.