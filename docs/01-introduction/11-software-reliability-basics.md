# Software Reliability Basics

> **Unit 1: Introduction** | **Type:** Extra (theory topic) | **Status:** ✅ Content ready (revise and quiz pending)
>
> **Covers:** Reliability definition, MTTF, MTTR, MTBF, availability, factors
>
> **Best reference books:** Pressman, Aggarwal & Singh, Sommerville

---

## 1. Exam-Ready Definition
**Software reliability** is the probability that software will operate without failure for a specified time under specified conditions in a specified environment.

## 2. Core Concept
**Metrics**

| Metric | Meaning |
|---|---|
| MTTF (Mean Time To Failure) | Average operating time until the next failure |
| MTTR (Mean Time To Repair) | Average time to fix a failure and resume service |
| MTBF (Mean Time Between Failures) | MTTF + MTTR |
| Availability | MTTF / (MTTF + MTTR) x 100 (as a percentage) |
| ROCOF | Rate of occurrence of failures |
| POFOD | Probability of failure on demand |

**Why software reliability differs from hardware:** software failures are due to *design faults*, not wear. Fixing a fault generally *improves* reliability, while hardware repair only restores it.

**Factors affecting reliability:** quality of requirements and design, testing effort, code complexity, operational environment, usage profile.

## 3. Diagram

```
Up ---- MTTF ----|Fail|-- MTTR --|Up ---- MTTF ----|Fail| ...
|<------------ MTBF ------------>|
```

## 4. Advantages, Disadvantages and Comparisons
Reliability models (several exist) help predict failure behaviour, but they depend on good failure data, which is hard to obtain.

## 5. Key Points for Revision
- MTBF = MTTF + MTTR.
- Availability = MTTF / (MTTF + MTTR).
- Reliability is a probability.
- Software failure = design fault, not wear.

## 6. Likely Exam Questions

**2 Marks**
- Define software reliability.
- Define MTTF and MTTR.

**5 Marks**
- Differentiate hardware and software reliability.
- Numerical on MTBF and availability.

**10 Marks**
- Explain software reliability, its metrics and factors with a numerical.

*Answer outlines:*
- Definition -> metric table -> timeline diagram -> factors -> numerical.

## 7. Project Link
State a **reliability target** for your project, e.g. "at most one failure per 100 hours of use, repair within 1 hour", and compute the implied availability.

## 8. Solved Numerical (Step by Step)
**Given:** MTTF = 200 hours, MTTR = 10 hours.
1. MTBF = MTTF + MTTR = 200 + 10 = **210 hours**.
2. Availability = MTTF / (MTTF + MTTR) = 200 / 210 = 0.9524.
3. Availability = **95.24 %**.

## 9. Practice Problem
MTTF = 450 hours and MTTR = 50 hours. Find MTBF and availability.
*(Answer: MTBF = 500 hours, availability = 90 %.)*

## 10. Quick Check Questions
1. Write the formula for MTBF.
2. What does availability measure?
3. Why does fixing a software fault improve reliability but repairing hardware only restores it?

<details><summary>Answers</summary>

1. MTBF = MTTF + MTTR.
2. The fraction of time the system is operational.
3. A software failure is a design fault that is removed permanently; hardware repair just replaces a worn part.
</details>

## 11. Common Exam Mistakes and Confusing Pairs
- **MTTF vs MTBF**: MTBF includes repair time.
- Forgetting the 100 multiplier for percentage availability.
- Treating reliability as a yes/no instead of a probability.
