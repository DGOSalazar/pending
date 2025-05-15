✅ Pull Request & Code Review Guidelines
🧑‍💻 1. Always tag a senior developer
Tag someone from Realtor.com who is either the code owner or very familiar with the impacted area.

This ensures better code context and review quality.

🧪 2. Open the PR after QE sign-off (if applicable)
If there’s a lot of changes in the PR during review, ask QE to test again before merging.

🧠 3. Reviewers ≠ Speed
The number of reviewers should match the complexity of the feature.

Don’t minimize the list just to get faster approvals.

🛠️ 4. Resolve all comments
You must address feedback from every reviewer.

Even if other reviewers approved the PR, unaddressed comments must still be resolved.

🤝 5. Too many comments? Pair up!
If one reviewer leaves several comments, consider scheduling a quick meeting or doing a pair review to clarify and move faster.

🔁 6. Involve other teams when needed
If your feature impacts another team, schedule a pair review with them before opening the PR.

This avoids surprises and makes the formal review smoother.

💡 7. Add comments for tricky code
If your code is not immediately obvious, add inline comments to explain the logic.

If the explanation is too long, you probably need to revisit or simplify the code.

Example:

kotlin
Copiar
Editar
// We store this flag here to persist user state across sessions.
🚫 8. Avoid persistent variables (unless necessary)
Keep the code stateless unless persistence is truly required.

🔄 9. One PR = One Purpose
Organize work into focused, incremental tickets and PRs. This helps QA test earlier and improves maintainability.

Example structure for a new feature:

📦 Ticket #1: Create module structure

📁 Ticket #2: Set up packages and base classes

🧩 Ticket #3: Build each component (e.g. form field, button)

🔡 Ticket #4: Add input logic for each field (e.g. Name input with validation)

This way, QE can test each part of the feature independently.

📆 10. PR still open by Thursday?
No pressure — move it to the next sprint.

If you spent time on discovery or research, create spike tickets to document and make the effort visible.

