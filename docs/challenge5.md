### Challenge 5: Test Agent quality

**Introduction:**

Before sharing your creation, you must validate its behavior against different scenarios.

**Description:**

Use the Agent Designer simulator to test both the Employee Flow and the Manager Flow. Verify that identity resolution, data retrieval, calendar actions, and sub-agent routing work exactly as expected.

**Success Criteria:**

- **Employee Flow:** Main Agent accurately filters completed courses and successfully schedules a calendar event.
- **Manager & Admin Flow:** Sub-Agent correctly routes to the Data Insight Agent and returns accurate team metrics for any given department.

**Learning Resources:**

- Simulator built right into the bottom right of the Agent Designer interface

**Tips:**

- Try edge cases: Ask a manager question while pretending to be a standard employee to see if the agent responds correctly based on the prompt rules.

### Challenge 6: Share agent

**Introduction:**

An agent is only valuable if users can access it.

**Description:**

Publish your tested agent and make it available to all users in your organization, via Gemini Enterprise App interface.

**Success Criteria:**

- The agent is successfully published.
- End-users can access and interact with the agent.

**Learning Resources:**

- Google Cloud Docs: Publish and manage agents  [https://docs.cloud.google.com/gemini/enterprise/docs/agent-designer/publish-agent](https://docs.cloud.google.com/gemini/enterprise/docs/agent-designer/publish-agent)

**Tips:**

- Ensure your IAM permissions are configured so end-users have the correct access roles to invoke the published agent.