# Session Summary — July 31, 2026

*Keel Watch Evaluation & Career Portfolio Update*

---

## Context

Continuation of the career pivot toward AI Program Management. Previous session built the full portfolio site, GitHub READMEs, and LinkedIn profile. This session evaluated Keel Watch for addition to the portfolio and updated all artifacts accordingly.

---

## What Was Done

### 1. Keel Watch Evaluation

Analyzed two zip files:

- `Keel Watch Branding and Feasibility.zip` — brand guidelines, SMB feasibility study (dated Jul 31, 2026), requirements doc
- `CoPilot-MCP.zip` — the full technical repo: Node.js pipeline, MCP server (stdio + HTTP), Dockerfile, Azure Container Apps deploy script, Kiro spec (requirements, design, tasks)

**Build status confirmed:** 33/43 tasks complete. All technical build done — pipeline, evidence ledger, extractors, brief/email generators, CLI orchestrator, MCP server, Docker container. Remaining 10 tasks are process steps (design partner engagement, delivery, debrief, go/no-go call).

**Portfolio verdict: Add it** — as Application 05. New technical patterns not represented elsewhere: PDF/contract extraction, evidence ledger architecture (grounding enforced structurally), MCP tool exposure.

**Commercial verdict: Proceed** — SMB feasibility study recommends a second design partner. Market gap is real (CLM software doesn't fit; realistic competitor is "nothing"). Three non-negotiables: cost-of-one-lost-client pricing, "not legal advice" disclaimer on every output, next pilot must be a real paid engagement.

Full evaluation saved to `artifacts/Keel_Watch_Evaluation.md`.

---

### 2. Portfolio Site Updated → `McCourt_Portfolio_Site_v2.html`

New **Application 05 card** added (inserted before the Investigator Agent shared-service card):

| Element | Content |
| --- | --- |
| Status pill | "Pilot-Ready · Design Partner Pending" |
| Stack chips | Node.js, AWS Bedrock, MCP Server (stdio + HTTP), pdf-parse, OpenAI-compatible, Azure Container Apps, @modelcontextprotocol/sdk |
| Proof bullets | Evidence ledger architecture · MCP tool wrapper (`check_contract_renewal_risk`) · Deliberate standalone architecture (33 tests) · Provider-agnostic LLM layer · Full feasibility + brand system |
| Scope note | Honest: pilot-ready, process steps remaining, KeelAI family framing |

**Role mapping updated** — AI Program / Delivery Manager card got a 4th bullet: *"SMB product: feasibility, brand, compliance posture (Keel Watch) → AI PM who can scope a product, not just ship a feature"*

---

### 3. Keel Watch GitHub README Written → `github-readmes/KeelWatch-README.md`

Full README including:

- ASCII pipeline architecture diagram
- Evidence ledger JSON example showing `sourceRef` structure
- MCP tool call JSON example
- Full stack table + build status table (33/43 ✅)
- Running instructions for all 3 modes: stdio (Claude Desktop), HTTP (local smoke test), Docker/Azure Container Apps
- Design decisions section (why standalone, why no auto-send, why cite everything, why not SignalCore)
- KeelAI family context

---

### 4. GitHub Profile README Updated → `github-readmes/GITHUB-PROFILE-README.md`

- Keel Watch added as 7th repo row: *"Contract renewal risk agent · MCP server (stdio + HTTP), AWS Bedrock, evidence-grounded output, Azure Container Apps | Pilot-Ready"*
- Count updated: "Four" → "Five independently-built applications"
- `MCP` added to the stack line

---

### 5. LinkedIn Profile Updated → `McCourt_LinkedIn_Profile.md`

Seven changes throughout the document:

- "Four" → **"Five"** in About section, Featured section, Independent Projects entry, outreach templates, and Quick Reference table
- **Keel Watch bullet** added to "What I've built" list (About section)
- **Keel Watch entry** added to Independent Projects experience block with full technical description
- `Model Context Protocol (MCP)` added to Skills section
- Stack line updated to include `Bedrock`, `MCP`, `Docker`
- Date updated to August 2026

---

### 6. GitHub Pinned Repos Plan Written → `GitHub_PinnedRepos_Plan.md`

| Slot | Repo | Rationale |
| --- | --- | --- |
| 1 | PM Agent | Featured build, names the target role |
| 2 | Investigator Agent | Deployed shared service, cross-cloud migration story |
| 3 | Northline | Active dev, parallel LLM orchestration |
| 4 | CareerIQ | Production, clean AWS serverless story |
| 5 | Delivery Insights | Production, zero-data-egress, Azure CI/CD |
| 6 | **Keel Watch** | Newest, evidence ledger + MCP, differentiating |

> Paceline drops off the 6-pin list — still public, still in portfolio.

Plan includes: per-repo secret audit checklist (git grep command), README drop-in map, profile repo setup steps, and order of operations with the key sequencing rule: *deploy Amplify first, then light up pins + LinkedIn URL + GitHub profile URL all at once*.

---

## Artifacts Produced

| File | Location |
| --- | --- |
| Keel Watch Evaluation | `artifacts/Keel_Watch_Evaluation.md` |
| Portfolio Site v2 (HTML) | `artifacts/McCourt_Portfolio_Site_v2.html` |
| Full career artifacts zip | `artifacts/McCourt_CareerArtifacts_Aug2026.zip` |
| Keel Watch GitHub README | inside zip → `github-readmes/KeelWatch-README.md` |
| Updated LinkedIn profile | inside zip → `McCourt_LinkedIn_Profile.md` |
| Updated GitHub profile README | inside zip → `github-readmes/GITHUB-PROFILE-README.md` |
| Pinned repos plan | inside zip → `GitHub_PinnedRepos_Plan.md` |

All artifacts also copied to `C:\Users\cmcco\Downloads\`.

---

## Zip Contents — `McCourt_CareerArtifacts_Aug2026.zip`

```
portfolio-site/
├── index.html              ← updated (App 05 Keel Watch card added)
├── amplify.yml
├── README.md
└── .gitignore
github-readmes/
├── GITHUB-PROFILE-README.md  ← updated (Keel Watch row, MCP in stack)
├── PMAgent-README.md
├── CareerIQ-README.md
├── DeliveryInsights-README.md
├── Northline-README.md
├── InvestigatorAgent-README.md
├── Paceline-README.md
└── KeelWatch-README.md       ← new
McCourt_LinkedIn_Profile.md   ← updated (Five apps, Keel Watch throughout)
McCourt_Portfolio_Site.html   ← updated standalone copy
GitHub_PinnedRepos_Plan.md    ← new

```

---

## Remaining Action Items

- [ ] Secret audit all 7 repos → make public → drop in READMEs
- [ ] Create `chrismc89` profile repo → paste `GITHUB-PROFILE-README.md`
- [ ] Push `portfolio-site/` to GitHub → connect Amplify → `portfolio.cmccourt.net`
- [ ] Once live: pin 6 repos (order above) · add URL to LinkedIn · add URL to GitHub profile
- [ ] Update LinkedIn profile from `McCourt_LinkedIn_Profile.md`
- [ ] Register PMI-CPMAI · grab Udemy prep course
- [ ] Find first Keel Watch design partner (paid engagement, however small)

