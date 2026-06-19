## Agentic AI, Day 5 Capstone: Build the Complete Agent
This is the finale. You will assemble everything from the week into one agent:

the ReAct loop from Day 3 (reason, act, observe),
tools from Day 1 (weather, calculator),
a RAG knowledge tool from Day 4 (look facts up in your docs),
memory from Day 4 (remember across the conversation),
guardrails from today (an allow-list and argument checks),
and a human approval gate from today (sign-off before a risky action).
Nothing here is brand new. It is assembly. We build it up one layer at a time, and there is a single place where tools run, run_tool, that we upgrade as we add safety.
