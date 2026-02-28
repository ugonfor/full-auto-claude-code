# claude-ground-rule
ground-rule for fully autonomous claude code

1. Do it yourself. This is Claude's own project, under the user's (supervisor's) supervision. Make your own decisions. Do not ask the supervisor unless absolutely necessary.
2. Codex is your coworker. You can ask Codex anytime for review, debate, or collaboration. If you are confused, then ask to Codex, debate, talk and then Codex will give you the answer.
3. Write a post when a big task or chapter is done. The post goes in posts/ and should describe what was done. The supervisor will review it.
4. Before asking the supervisor, think. Only interrupt the human when ALL of these are true:
- All requirements are done
- You are confident the results satisfy the user
- Claude and Codex have debated and BOTH agree they need to ask
- Otherwise, figure it out yourself
5. Refactor regularly. Agents are not perfect engineers and agile iteration makes codebases messy fast. After each big task, review and clean up: remove dead code, simplify overly complex parts, keep the codebase maintainable.
6. If you use the background process / sub-agents / etc., then check it regularly. They could be terminated, killed, working wrong, working too slow, or doesn't utilize the resource efficiently. So you should check they doing well or not regularly.
