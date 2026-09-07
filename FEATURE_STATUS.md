# Feature status — Semiconductors & hardware development

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 142 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 0 | 0 | Native records/view |
| Work items & projects | records | 0 | 0 | Native records/view |
| Contacts & parties | records | 0 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 2 | 0 | Native records/view |
| Reports & analytics | report | 3 | 0 | Native records/view |
| Activity & audit trail | audit | 5 | 0 | Native records/view |
| Provider connections | integration | 1 | 0 | Provider request records only |
| Component master registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Approved supplier mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Quote agreement library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Purchase order ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Receipt invoice matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contract price validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commodity adder audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Broker premium review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NCNR term validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| MOQ price tier | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Currency conversion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Variance calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit reconciliation | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Part supplier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Foundry agreement library | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Product node and mask registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wafer-start reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wafer acceptance and scrap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Wafer-sort ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Good-die yield calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Yield guarantee validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Known-good-die reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Engineering lot separation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mask and NRE charge audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Expedite charge validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Foundry invoice recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Yield-loss claim generation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Foundry response workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Product node and supplier analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tape-out program registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mask set inventory | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Layer count validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| NRE milestone tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Engineering lot calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Respins responsibility | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Design change attribution | integration | 1 | 0 | Provider request records only |
| Waiver credit control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Tooling ownership evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Duplicate NRE detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Foundry dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Program node analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Yield Learning Center | records | 2 | 0 | Native records/view |
| Excursion War Room | records | 1 | 0 | Native records/view |
| Production Readiness | records | 1 | 0 | Native records/view |
| Observability | records | 1 | 0 | Native records/view |
| Audit Trail | records | 1 | 0 | Native records/view |
| AI Job Queue | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Model Registry | records | 1 | 0 | Native records/view |
| Approvals | records | 1 | 0 | Native records/view |
| RBAC Rules | records | 1 | 0 | Native records/view |
| Evidence Exports | records | 2 | 0 | Native records/view |
| Wafer Lots | records | 2 | 0 | Native records/view |
| Equipment Inventory | records | 1 | 0 | Native records/view |
| Facilities | records | 1 | 0 | Native records/view |
| Reticle Pod Queue | records | 1 | 0 | Native records/view |
| Maintenance | records | 2 | 0 | Native records/view |
| Shift Log Digest | records | 1 | 0 | Native records/view |
| Wafer Defects | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Process Parameters | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Yield Predictions | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Root Cause Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment Matching | records | 1 | 0 | Native records/view |
| Defect Patterns | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| SPC Alerts | records | 1 | 0 | Native records/view |
| Process Recipes | records | 1 | 0 | Native records/view |
| Quality Metrics | records | 1 | 0 | Native records/view |
| Process Optimization | records | 1 | 0 | Native records/view |
| Defect Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Equipment Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi-Objective Optimize | records | 1 | 0 | Native records/view |
| Missing Features Hub | records | 1 | 0 | Native records/view |
| Yield Model AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| RCA Automation | records | 2 | 0 | Native records/view |
| Parameter Recs | records | 1 | 0 | Native records/view |
| Defect Rate ML | records | 1 | 0 | Native records/view |
| Equipment Health AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recipe AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Realtime SPC | records | 1 | 0 | Native records/view |
| SECS/GEM Integration | integration | 1 | 0 | Provider request records only |
| Calibration Tracking | records | 1 | 0 | Native records/view |
| MES/ERP Integration | integration | 1 | 0 | Provider request records only |
| Audit/RBAC | records | 1 | 0 | Native records/view |
| Yield by Parameters | records | 1 | 0 | Native records/view |
| Recipe Optimization | records | 1 | 0 | Native records/view |
| Predictive Maintenance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Defect Recognition | records | 1 | 0 | Native records/view |
| Multi-Objective AI | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dashboard | records | 1 | 0 | Native records/view |
| Users | records | 1 | 0 | Native records/view |
| Sessions | records | 1 | 0 | Native records/view |
| Password Resets | records | 1 | 0 | Native records/view |
| Email Verifications | records | 1 | 0 | Native records/view |
| Error Logs | records | 1 | 0 | Native records/view |
| Roles & Permissions | records | 1 | 0 | Native records/view |
| Security | records | 1 | 0 | Native records/view |
| Out.def | records | 1 | 0 | Native records/view |
| Out.gds | records | 1 | 0 | Native records/view |
| Lead Time Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier Recommendation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Bottleneck Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier Risk Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| BOM Cost Optimizer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Defect Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Demand Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Geopolitical Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Parts | records | 1 | 0 | Native records/view |
| Suppliers | records | 1 | 0 | Native records/view |
| Orders | records | 1 | 0 | Native records/view |
| Design Iterations | records | 1 | 0 | Native records/view |
| Quality Checks | records | 1 | 0 | Native records/view |
| Manufacturers | records | 1 | 0 | Native records/view |
| Export | records | 1 | 0 | Native records/view |
| Bom | records | 1 | 0 | Native records/view |
| Components | records | 1 | 0 | Native records/view |
| Landed cost | records | 1 | 0 | Native records/view |
| Cm lead times | records | 1 | 0 | Native records/view |
| Dfm | records | 1 | 0 | Native records/view |
| Ecn | records | 1 | 0 | Native records/view |
| Aql | records | 1 | 0 | Native records/view |
| Iteration speed | records | 1 | 0 | Native records/view |
| Golden sample control | records | 1 | 0 | Native records/view |
| Deployments | records | 1 | 0 | Native records/view |
| Librelane work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Control tower | records | 1 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 142 feature pages were visited in the browser; 140 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 68 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

68 original AI entries are now grouped into **6 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
