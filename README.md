# Lab 12 USI Campus Connector

Read **Lab 12 USI Campus Connector.pdf** or its Markdown copy. Both parts are 50 points, total 100; due November 18, 2026 at 11:59 PM Central (America/Chicago).

## Start

Starter repository: https://github.com/cwillpinto/cs311-lab12-usi-campus-connector

1. Select **Use this template → Create a new repository** and choose your own GitHub account. Clone your new repository, then open its folder in VS Code.
2. Check `python --version` (3.11+). Only the standard library is required. Run `python run_campus.py`. The untouched starter stops at its intended `NotImplementedError` TODO.
3. Complete the four numbered written questions using the handout's worked-example and slide guidance.
4. Implement `build_graph`, recursive `has_path` and deque-based `bfs_shortest_path`. Rerun `python run_campus.py` after each phase; a later TODO can still stop an intermediate run.
5. Read every PASS/FAIL line. Once all 13 checks pass, enter your own USI username for the Success Token. Do not edit the verification suite.
6. Submit `Lab12_Theory.pdf` or `Lab12_Theory.md`, completed `run_campus.py` and the Success Token through Blackboard. Include the syllabus AI Usage note when applicable.

## Repository ownership

Push completed work to your own repository. Check `git remote -v` before pushing; `origin` must point to your account. Never push answers to the instructor starter.

If you prefer a direct clone, first create an empty repository under your account, then:

```sh
git clone https://github.com/cwillpinto/cs311-lab12-usi-campus-connector.git
cd cs311-lab12-usi-campus-connector
git remote rename origin upstream
git remote add origin <student-owned-repository-url>
git remote -v
git branch --show-current
git push -u origin main
```

Replace the placeholder with your own repository URL. Use your actual branch if it differs from `main`. A Blackboard starter ZIP is a fallback if GitHub is unavailable; extract the entire ZIP before running.

The token verifies only supplied checks. Method compliance and written reasoning are reviewed separately. The existing theory/source/token submission requirements are unchanged; no graded repository URL or commit item is added.

Connector groups connect every pair of their buildings in both directions. Real USI building names have fictional links; fewest links does not mean fastest or geographically shortest. Review slides 4–8, 11–30, 39–53 and 64–65.
