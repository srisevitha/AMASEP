# AMASEP
Autonomous Multi-Agent Software Engineering Platform automates the software development lifecycle from a single plain-English prompt—eliminating the manual step-by-step prompting required by standard AI chat interfaces.

Four specialized agents powered by Gemini 2.0 Flash collaborate in a closed feedback loop to mimic a real-world engineering team:

Planner: Decomposes requirements into a structured development plan.

Coder: Generates production-ready code based on the architectural plan.

Tester: Executes code inside a live Python subprocess sandbox and validates correctness via automated tests.

Reviewer: Audits code quality, identifies bugs, and automatically re-routes critically flawed code back to the Coder for self-correction without human intervention.

Built with FastAPI, WebSockets, SQLite, React, and Tailwind CSS, the platform streams live agent activity to a real-time dashboard and delivers a complete development plan, executable code, test results, and a full review report.
