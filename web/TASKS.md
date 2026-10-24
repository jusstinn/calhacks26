# web/ tasks (THREAD_JUSTIN.md)

| Task | Lane | Status |
|---|---|---|
| J0 Scaffold: Vite, Tailwind 4, shadcn, theme, shell + nav, role switcher (`POST /api/session`), time scrubber (`POST /api/clock`, `GET /api/clock`), typed client, `useStream()`, error boundary, `pnpm dev/build/test/e2e` | A | done |
| J0b Mock world typed from CONTRACTS.md (`src/mocks/`): every §3 route, writes included, golden numbers under test | A | done |
| J1 Storm Run | A | done |
| J2 Flight File (`/flights`, `/flights/:id`) | A | done |
| J3 Questions | A | done |
| J10 Docs: DEMO_SCRIPT, VIDEO, QA, README, DEVPOST | B | done (Devpost numbers fill from `eval/proof.json`) |
| J4 Policies | B | done |
| J5 Trace (Live · Commits · Blame · Access · Controls) | B | done |
| J6 Liability & Close | B | done |
| J7 Judge's Desk | B | done |
| J8 Proof | B | done (reads `/eval`; mock values until F9) |
| J9 Recorded mode + Vercel | B | done: the demo recorded on the D10a real engine (5 steps, 8.5 MB); the preview serves it with no backend. Re-record after the server changes: `node scripts/record.mjs --base http://localhost:8000` plus `make record` |
| J11 `/pitch` slides | B | done |
| `/story`: the scroll story on Éowyn (beyond the plan) | B | done |
| Switch off mocks: `pnpm gen:api`, CP1 against the stub, then the server | A | done: contract check green; 43/46 e2e on the stub and on the real server (3 skip by design) |
| Record the demo and redeploy | B | done once; re-record at CP3 so the preview matches the final server |

Tests: `pnpm test` (221 unit), `pnpm e2e` (51 in 1.6 min, including `e2e/demo.spec.ts`, the 3:00 script clicked end to end).
