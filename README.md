# GATE 2027 CS/IT — Master Study Plan

**Today:** Sat, Sep 5, 2026  **Exam (expected):** Feb 6–7, 2027  **Runway:** 22 weeks

---

## How This Plan Works

Two hour-budgets are baked in, since your daily availability may shift:

- **Primary — 6–8 hrs/day.** The week-by-week pacing below assumes this.
- **Compressed — 4–5 hrs/day.** Cut PYQ *volume* per sitting, not the loop stages. Every stage still happens every day — you just solve fewer PYQs and let a topic spill an extra day if it needs to.

Non-negotiable, every day, all 22 weeks: **Learn → Test with examples → Solve PYQs → Review errors.** This document tells you *what* to study *when*. The loop itself never changes — see Part 4.

Section weightage referenced below comes from a full tag-by-tag read of your actual 2026 CS2 paper (cross-checked against CS1), not estimates.

---

## Part 1 — 5-Month Macro Plan

| Month | Weeks | Dates | Subject(s) |
|---|---|---|---|
| 1 | 1–4 | Sep 5 – Oct 2 | Engineering Mathematics — finish Linear Algebra → Discrete Math → Calculus → Probability & Statistics |
| 2 | 5–8 | Oct 3 – Oct 30 | Digital Logic → Programming & Data Structures → Algorithms Pt.1 |
| 3 | 9–12 | Oct 31 – Nov 27 | Algorithms Pt.2 → Theory of Computation → COA Pt.1 |
| 4 | 13–17 | Nov 28 – Jan 1 | COA Pt.2 → Operating Systems → DBMS |
| 5 | 18–22 | Jan 2 – Feb 5 | Computer Networks → Compiler Design → **Full Revision + Mocks (Wk 21–22)** |

Algorithms straddles the Month 2/3 boundary — that's fine, real learning doesn't respect calendar months, and the adjustment rules in Part 4 cover it.

**Why this order, not the video's tier list:** Math first because you're already mid-way through it and it underpins Theory of Computation and parts of Algorithms. Programming & Data Structures before Algorithms because you can't analyze what you can't build. Digital Logic before Computer Organization because ALU/control-unit design assumes Boolean algebra. Theory of Computation before Compiler Design because lexical analysis and parsing are literally regular languages and CFGs in disguise. This is dependency order, not a marks-ranked tier list.

---

## Part 2 — Month 1 Detail: Engineering Mathematics (Sep 5 – Oct 2)

| Week | Dates | Focus | Exit target |
|---|---|---|---|
| 1 | Sep 5–11 | **Finish Linear Algebra:** Determinants, Systems of Linear Equations, Eigenvalues & Eigenvectors, LU Decomposition | Full Linear Algebra PYQ set (2022–2026) solved, error notebook started |
| 2 | Sep 12–18 | Discrete Math Pt.1: Propositional & First-Order Logic, Sets/Relations/Functions, Posets & Lattices, Monoids & Groups | Topic-wise PYQs solved for each sub-area |
| 3 | Sep 19–25 | Discrete Math Pt.2: Graphs (connectivity, matching, colouring), Combinatorics (counting, recurrence relations, generating functions) | Topic-wise PYQs solved |
| 4 | Sep 26–Oct 2 | Calculus (limits, continuity, differentiability, maxima/minima, mean value theorem, integration) + Probability & Statistics (distributions, mean/median/mode/SD, conditional probability, Bayes) | Full Engineering Math mixed PYQ sweep, error notebook consolidated |

Matrix multiplication, special matrix types, and rank are already solid from what we've covered. Week 1 closes out the rest of Linear Algebra.

---

## Part 3 — Week 1 Detail: Finishing Linear Algebra (Sep 5–11)

| Day | Date | Topic | Loop |
|---|---|---|---|
| 1 | Sat Sep 5 | Determinants — properties, cofactor expansion, the det(kA)=kⁿ·det(A) trap, determinants of triangular matrices | Learn + practice examples |
| 2 | Sun Sep 6 | Determinants, applied | PYQs (2022–2026) + error log |
| 3 | Mon Sep 7 | Systems of Linear Equations — Gaussian elimination, consistency via rank, homogeneous vs. non-homogeneous | Learn + practice examples |
| 4 | Tue Sep 8 | Systems of Linear Equations | PYQs + error log |
| 5 | Wed Sep 9 | Eigenvalues & Eigenvectors — characteristic equation, trace/determinant shortcuts, reading eigenvalues off diagonal/triangular matrices | Learn + practice examples |
| 6 | Thu Sep 10 | Eigenvalues PYQs + LU Decomposition — when it exists, how to compute it, why it's used | PYQs + learn LU |
| 7 | Fri Sep 11 | Full Linear Algebra mixed PYQ set, all sub-topics combined | PYQs + close out the error notebook entry for the whole topic |

Day 1 starts whenever you say go.

---

## Part 4 — Daily Loop Template (reuse this for all 22 weeks)

| Stage | 6–8 hr day | 4–5 hr day | What it means |
|---|---|---|---|
| Learn | ~2.5–3 hrs | ~1.5–2 hrs | Intuition → definition → why it works → GATE angle |
| Test with examples | ~1 hr | ~30–45 min | 4–6 practice examples, solved before looking at any answer |
| Solve PYQs | ~2–2.5 hrs | ~1–1.5 hrs | Topic-specific PYQs, 2022–2026 |
| Review errors | ~45 min–1 hr | ~30–45 min | Every miss logged: concept gap vs. calculation slip vs. misread question |

**Error notebook format** — keep it this simple, don't overbuild it:

`Topic | Question source | What I got wrong | Why | Correct approach in one line`

Example: `Linear Algebra | 2023 PYQ | Used det(kA)=k·det(A) | Forgot the scalar hits every row | Always check matrix size n before scaling a determinant`

---

## General Aptitude — Running Thread, Not a Block

15 fixed marks, non-technical, no dedicated week. Starting Month 2, do 20–30 minutes of GA practice every 2–3 days. Increase to daily once you hit Weeks 21–22. Don't touch it in Month 1 — Math needs the room.

---

## Adjustment Rules

- A subject running long eats into the *next* week, never into Weeks 21–22. Those two weeks are protected — full-syllabus mixed PYQs and mock tests only, no exceptions.
- A subject finishing early? Pull the next one forward. Don't idle.
- If you're consistently blowing past a week's PYQ target, that's a signal to log in the error notebook too — it usually means calculation speed, not concept gaps.

---

**Feb 6–7, 2027 — GATE 2027 CS.** Everything above ends there.
