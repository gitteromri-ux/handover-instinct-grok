# Change safety protocol (production-affecting actions)

1. Snapshot first: git branch/tag `backup/<yyyymmdd-hhmm>-<task>` or export of current config (GTM container JSON, AC automation export, Vercel deployment ID, Cloudflare rules JSON, Meta ad set settings). Record the rollback command.
2. Work on a branch or preview deployment, never directly on main/prod. Never force-push, delete repos, delete branches, delete projects, rewrite history, or bulk-edit multiple projects in one step.
3. Scope lock: list the exact files/settings to change. Touch nothing else. One project per change.
4. Verify on preview: HTTP 200, desktop + 390px mobile screenshots, console errors, network calls for tracking.
5. Approval gate: show the user preview link, diff summary, and rollback plan; wait for explicit "approve / go live".
6. Promote, then re-verify on production with the same checks. Post-deploy proof or it is not done.
7. If anything regresses, roll back immediately using the recorded command, then report.

Bulk actions across more than one project/repo/automation are forbidden unless the user explicitly lists every target.
