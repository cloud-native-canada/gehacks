### Challenge 4: Refine prompts using Gemini for Main and Sub-Agent

**Introduction:**

The prompt is the brain of your agent. Crafting the right instructions ensures the agent uses tools correctly and stays in character.

**Description:**

Write the System Instructions (prompts) for both the Main Agent and your analytical Sub-Agent. Use a conversational but explicit style to define roles, output expectations, and tool boundaries.

**Success Criteria:**

- The Main Agent prompt correctly handles employee queries and schedules calendar events.
- The Main Agent prompt explicitly routing manager-level queries to the sub-agent.
- The Sub-Agent prompt includes accurate identity resolution (using the user's email or specified team name).

**Learning Resources:**

- [Prompting best practices for AI agents](https://docs.cloud.google.com/gemini/enterprise/docs/agent-designer/create-agent#best_practices_for_creating_agents)
- [Best practices for writing prompts to create an agent](https://docs.cloud.google.com/gemini/enterprise/docs/agent-designer/create-agent#best_practices_for_writing_prompts)
- [Google Cloud: Prompt design strategies (Role, Context, Output formatting)](https://cloud.google.com/vertex-ai/generative-ai/docs/learn/prompts/prompt-design-strategies)
- [Google AI: Core prompting principles (Gemini models)](https://ai.google.dev/gemini-api/docs/prompting-strategies)

**Tips:**

- Use the "Role" and "Output Expectations" framework to organize your prompts.
- Be explicit about tool usage (e.g., "Use the Google Calendar Tool to open a slot").
- Leverage tools like the Gemini web app, the Gemini CLI, or other LLMs to help you brainstorm, draft, and refine your system prompts before testing them in Agent Designer.
