# EPF Cohort 7 — Learning Timeline & Tasks

**Start:** June 9, 2026  
**End:** November 15, 2026 (Devconnect Mumbai showcase)  
**Duration:** ~23 weeks / 5 months  
**Time commitment:** 1.5–3 hrs/day

---

## Weekly Rhythm (every week, recurring)

| Day | Activity | Time |
|-----|----------|------|
| Monday | Standup call — 15:00 UTC (`meet.ethereum.org/epf-standup`) | 1 hr |
| Monday | Review other fellows' dev updates + your own notes | 30 min |
| Wednesday | Office Hours call — 15:00 UTC (`meet.ethereum.org/epf-office-hours`) | 1 hr |
| Wednesday | Study session (reading block) | 1–2 hrs |
| Friday | Write weekly development update | 30–60 min |
| Tue/Thu/Sat | Deep study or project work | 1.5–2.5 hrs each |

> Check the [Office Hours agenda](https://github.com/eth-protocol-fellows/cohort-seven/issues) each week before Wednesday.

---

## Phase 0 — Prep (Jun 9 – Jun 30)

Goal: work through the EPS (Ethereum Protocol Studies) curriculum from epf.wiki as structured self-study.  
Start here: https://epf.wiki/#/eps/intro

### Week 1 — Jun 9–15 — EPS Week 0: Prerequisites + Setup

**Setup**
- [ ] Join R&D Discord — contact @joshdavislight or @taxmeifyoucan for invite
- [ ] Join EPS Discord: https://discord.gg/8RPnPGEyjYZ
- [ ] Open a PR adding yourself to `development-updates.md`
- [ ] Attend Monday standup Jun 9 at 15:00 UTC — listen only

**EPS Week 0 Pre-Reading** (https://epf.wiki/#/eps/week0)
- [ ] Cryptography basics — hashing and public key cryptography fundamentals
- [ ] Merkle trees — watch a video tutorial on how they work
- [ ] Networking & P2P — distributed systems and peer-to-peer basics
- [ ] Ethereum from a user/dapp perspective — ethereum.org intro
- [ ] Watch the EPS Town Hall recording: https://www.youtube.com/watch?v=7L1270CWjXw

### Week 2 — Jun 16–22 — EPS Session 1: Protocol Intro

**EPS Session 1** (https://epf.wiki/#/eps/week1)
- [ ] Watch "Ethereum Protocol 101" by Mario Havel on StreamEth
- [ ] Read: Inevitable Ethereum — World Computer: https://inevitableeth.com/site/content
- [ ] Watch: Ethereum in 30 minutes (Vitalik): https://youtu.be/UihMqcj-cqc
- [ ] Read: ethereum.org developer docs (overview): https://ethereum.org/en/developers/docs/
- [ ] Read: Cypherpunk Manifesto (historical context)
- [ ] Explore: ethroadmap.com (current Ethereum landscape)
- [ ] Read: EIP-1 — how Ethereum Improvement Proposals work: https://eips.ethereum.org/EIPS/eip-1
- [ ] Attend Wednesday Office Hours Jun 17 at 15:00 UTC

**Optional deeper reading:**
- The Infinite Machine (book — early Ethereum story)
- Mastering Ethereum (book — foundational to technical)

### Week 3 — Jun 23–29 — EPS Session 2: Execution Layer

**EPS Session 2** (https://epf.wiki/#/eps/week2)
- [ ] Watch: Execution Layer Overview with lightclient on YouTube: https://www.youtube.com/watch?v=pniTkWo70OY
- [ ] Read: "Nodes and clients" — ethereum.org: https://ethereum.org/en/developers/docs/nodes-and-clients/
- [ ] EVM opcodes reference: https://www.evm.codes/ and https://ethervm.io/
- [ ] RLP encoding: https://medium.com/coinmonks/data-structure-in-ethereum-episode-1-recursive-length-prefix-rlp-encoding-decoding-d1016832f919
- [ ] Hexary Trie write-up: https://gist.github.com/ftruzzi/fe6c6735dbbfafa4994985879254a871
- [ ] JSON-RPC docs: https://ethereum.org/en/developers/docs/apis/json-rpc/
- [ ] Browse go-ethereum repository to see a production EL client: https://github.com/ethereum/go-ethereum
- [ ] Start Yellow Paper sections 1–4 with cheat sheet alongside
  - Paper: https://ethereum.github.io/yellowpaper/paper.pdf
  - Cheat sheet: https://github.com/benjaminion/YellowPaper_CheatSheet/blob/master/YPCheatSheet.pdf

---

## Phase 1 — Orientation (Jul 1 – Jul 31)

Goal: finish EPS core curriculum, pick a project area.

### Week 4 — Jul 1–6 — EPS Session 3: Consensus Layer

**EPS Session 3** (https://epf.wiki/#/eps/week3)
- [ ] Watch: "Overview of the CL" by Alex Stokes on YouTube
- [ ] Read: ethereum.org Proof-of-Stake docs: https://ethereum.org/en/developers/docs/consensus-mechanisms/pos/
- [ ] Read: Beacon Chain explainer (ethos.dev)
- [ ] Read: Why Proof of Stake? (Vitalik): https://vitalik.eth.limo/general/2020/11/06/pos2020.html
- [ ] Read: The Merge overview: https://ethereum.org/en/roadmap/merge/
- [ ] Read: LMD-GHOST fork choice: https://medium.com/@aditya.asgaonkar/bitwise-lmd-ghost-an-efficient-cbc-casper-fork-choice-rule-6db924e57d1f
- [ ] Read: Ben Edgington's eth2book Part 1: https://eth2book.info/
- [ ] Read: Annotated beacon spec by Vitalik: https://github.com/ethereum/annotated-spec/tree/master

### Week 5 — Jul 7–13 — EPS Session 4: Testing & Security

**EPS Session 4** (https://epf.wiki/#/eps/week4)
- [ ] Watch: Ethereum core testing infrastructure presentation on YouTube
- [ ] Read: execution-spec-tests docs: https://github.com/ethereum/execution-spec-tests
- [ ] Explore: hive testing framework: https://github.com/ethereum/hive
- [ ] Explore: ethereum/tests repo: https://github.com/ethereum/tests
- [ ] Explore: kurtosis devnet tooling: https://github.com/kurtosis-tech/kurtosis
- [ ] Try running a test locally against a client if possible

### Week 6 — Jul 14–20 — EPS Session 5: Research & Roadmap

**EPS Session 5** (https://epf.wiki/#/eps/week5)
- [ ] Watch: Domothy's roadmap overview on YouTube
- [ ] Read: ethereum.org roadmap: https://ethereum.org/en/roadmap/
- [ ] Read: domothy.com/roadmap/ for a clear breakdown
- [ ] Read: Delphi Digital "Hitchhiker's Guide to Ethereum"
- [ ] Read: Vitalik's Endgame article (2021)
- [ ] Read: Vitalik's six roadmap track posts (Merge/Surge/Scourge/Verge/Purge/Splurge, Oct 2024): https://vitalik.eth.limo/general/2024/10/17/futures2.html
- [ ] Read: Danksharding overview: https://ethereum.org/en/roadmap/danksharding/

### Week 7 — Jul 21–27 — Browse Project Ideas

- [ ] Read all of `projects/project-ideas.md` — mark 2–3 that interest you
- [ ] For each candidate, read its linked EIPs and GitHub repos
- [ ] Browse cohort 6 executed projects: https://github.com/eth-protocol-fellows/cohort-six/blob/master/projects/
- [ ] Browse cohort 5 executed projects: https://github.com/eth-protocol-fellows/cohort-five/blob/master/projects/
- [ ] Start lurking in the client team's Discord channels

**Project areas to evaluate:**

| Interest | Projects |
|----------|----------|
| Rust + execution | Reth: Partial Statefulness, Moonglass |
| Rust + consensus | Ream: PeerDAS DA Client, Ream: EL Integration, Grandine: FOCIL |
| Testing/infra | Ream: Black Box Interop, Ream: PQ Devnets |
| SSZ/data structures | Pureth: SSZ Execution Blocks, Decentralized CL Checkpoint Sync |
| Python/AI | Erigon: aglean |
| Optimization | Grandine: Attestation Packer, Grandine: Disk Usage |

### Week 8 — Jul 28 – Aug 3 — Commit to a Project + First Issues

- [ ] Narrow down to 1 project — write a one-paragraph "why this" note
- [ ] Clone and build the relevant client codebase locally
- [ ] Read relevant epf.wiki wiki sections on your chosen topic
- [ ] Find 1–2 good first issues: https://gfi.bordel.wtf
- [ ] Attempt at least one — even reading the code around it counts
- [ ] Post a brief intro in `#protocol-fellowship` Discord

---

## Phase 2 — Deep Dive + Proposal (Aug 4 – Sep 30)

Goal: become fluent in your project area; write and submit a proposal.

### Week 9 — Aug 4–10 — EPS Cryptography Module (Sessions 1–2)

The EPS 2026 cryptography module covers the math underpinning Ethereum's cryptography.
- [ ] Finite Groups & Fields — study notes + any available recording
- [ ] Discrete Fourier Transform — study notes + any available recording
- [ ] Read: Introduction to Modern Cryptography (relevant chapters): https://www.cs.umd.edu/~jkatz/imc.html
- [ ] Read the EIPs directly referenced by your chosen project
- [ ] Follow threads on ethresear.ch relevant to your area: https://ethresear.ch/
- [ ] Follow EIP discussion on ethereum-magicians.org: https://ethereum-magicians.org/

### Week 10 — Aug 11–17 — EPS Cryptography Module (Sessions 3–5)

- [ ] Elliptic Curves & Pairings — study notes + recording
- [ ] BLS Signatures — study notes + recording
- [ ] Proof Systems — study notes + recording
- [ ] Stateless Ethereum: https://blog.ethereum.org/2019/12/30/eth1x-files-state-of-stateless-ethereum/

### Week 11 — Aug 18–24 — EPS zkEVM / Lean Ethereum Module

- [ ] Lean Consensus Overview (Emile) — recording/notes
- [ ] Lean Client Architecture (Kolby) — recording/notes
- [ ] zkEVM Fundamentals (Cody Gunton & Ignacio Hagiopan) — recording/notes
- [ ] leanSpec and tooling — recording/notes
- [ ] Post-Quantum Cryptography (Justin Drake) — recording/notes
- [ ] leanSpec repo: https://github.com/leanEthereum/leanSpec

### Week 12 — Aug 25–31 — Deep Dive + Start Proposal

- [ ] Read all prior art and research posts linked in your chosen project idea
- [ ] Read relevant sections of Ben Edgington's book or annotated spec in depth
- [ ] Identify what is unsolved / what your project will contribute
- [ ] Read `projects/project-template.md` — understand the expected format
- [ ] Draft section 1: problem statement and motivation
- [ ] Draft section 2: proposed solution / approach

### Week 13 — Sep 1–7 — Develop Proposal

- [ ] Draft section 3: roadmap with milestones
- [ ] Draft section 4: open questions and risks
- [ ] Share draft in `#protocol-fellowship` Discord for early feedback

### Week 14 — Sep 8–14 — Refine & Submit Proposal

- [ ] Incorporate feedback from Discord
- [ ] Open a PR adding your proposal to `projects/`
- [ ] Approach a mentor only now — after the draft is ready (see `program-guide/mentors.md`)
- [ ] Add a comment to the Office Hours GitHub issue to discuss proposal Sep 10

### Week 15–16 — Sep 15–28 — Proposal Presentation + Final Feedback

- [ ] Present proposal to group on a standup or Office Hours call
- [ ] Incorporate final mentor/peer feedback
- [ ] Finalize project roadmap with week-by-week deliverables for Phase 3

---

## Phase 3 — Execute (Oct 1 – Nov 15)

Goal: ship deliverables, post weekly updates, present at Devconnect.

### Week 17 — Oct 1–5
- [ ] Begin project execution — first milestone
- [ ] Post dev update #1

### Week 18 — Oct 6–12
- [ ] Continue project work
- [ ] Post dev update #2

### Week 19 — Oct 13–19
- [ ] Mid-project check-in — are you on track with your roadmap?
- [ ] Post dev update #3

### Week 20 — Oct 20–26
- [ ] Continue project work
- [ ] Post dev update #4

### Week 21 — Oct 27 – Nov 2
- [ ] Continue project work
- [ ] Post dev update #5

### Week 22 — Nov 3–9
- [ ] Wrap up core deliverables
- [ ] Write project summary / final write-up draft
- [ ] Post dev update #6

### Week 23 — Nov 10–15 — Final Week
- [ ] Final dev update and project summary
- [ ] Prepare showcase presentation for Devconnect Mumbai
- [ ] **Nov 15 — Devconnect Mumbai: project showcase**

---

## Essential Links

| Resource | What it is |
|----------|------------|
| https://epf.wiki | Primary learning resource — start here |
| https://ethereum.org/en/developers/docs/ | Accessible protocol docs |
| https://eth2book.info/ | Best annotated beacon chain spec |
| https://eips.ethereum.org | All EIPs |
| https://ethresear.ch/ | Active research forum |
| https://ethereum-magicians.org/ | EIP discussion |
| https://gfi.bordel.wtf | Good first issues across all clients |
| https://github.com/eth-protocol-fellows/cohort-seven/issues | Office Hours agenda |
