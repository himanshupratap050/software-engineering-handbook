# Model Comparison and Basic Risk Management

> **Unit 1: Introduction** | **Type:** Extra (wrap-up of Unit 1) | **Status:** ✅ Content ready (revise and quiz pending)
>
> **Covers:** Choosing a process model, comparison table, risk identification, projection, RMMM
>
> **Best reference books:** Pressman, Aggarwal & Singh, Sommerville

---

## 1. Exam-Ready Definition
**Risk** is an uncertain event that, if it occurs, harms the project's cost, schedule or quality. **Risk management** is identifying, assessing, planning for and monitoring risks.

## 2. Core Concept

**Comparison of life-cycle models**

| Basis | Waterfall | Prototype | Spiral | Incremental | RAD | Agile |
|---|---|---|---|---|---|---|
| Requirements | Clear, stable | Unclear | Evolving | Mostly clear | Clear, modular | Changing |
| Risk handling | Poor | Medium | Excellent | Medium | Medium | Medium |
| User involvement | Low | High | Medium | Medium | High | Very high |
| Working software | At end | Early (prototype) | Each loop | Each increment | Quickly | Each sprint |
| Cost / complexity | Low | Medium | High | Medium | Medium | Medium |
| Suited for | Small, well-defined | UI-heavy, unclear needs | Large, risky | Staged delivery | Short deadline | Fast-changing needs |

**Risk management steps**
1. **Identification:** list project, technical and business risks.
2. **Analysis / projection:** estimate *probability* and *impact*. **Risk exposure = probability x impact (loss)**.
3. **Planning (RMMM):** Risk **M**itigation, **M**onitoring and **M**anagement plan.
4. **Monitoring:** track risks and review regularly.

**Examples:** staff turnover, changing requirements, unrealistic schedule, new technology, poor estimates.

## 3. Diagram

```
Identify -> Analyse (prob x impact) -> Plan (RMMM) -> Monitor -> (repeat)
```

## 4. Advantages, Disadvantages and Comparisons
Choose the model by: requirement clarity, project size, risk level, deadline, customer availability.

## 5. Key Points for Revision
- No single best model; choose by project nature.
- Spiral is strongest in risk handling.
- Risk exposure = probability x impact.
- RMMM = mitigation, monitoring, management.

## 6. Likely Exam Questions

**2 Marks**
- Define risk and risk exposure.

**5 Marks**
- Explain risk management steps.

**10 Marks**
- Compare process models and justify which to use for a given project.

*Answer outlines:*
- Comparison table -> selection factors -> risk steps -> example.

## 7. Project Link
Create a **risk table** for your project: risk, probability, impact, exposure, mitigation. Save it in `project/01-process-model-selection.md`.

## 8. Solved Numerical (Step by Step)
A risk has probability 0.4 and a potential loss of Rs. 50,000.
Risk exposure = 0.4 x 50,000 = **Rs. 20,000**.

## 9. Practice Problem
Probability 0.25, loss Rs. 80,000. Find risk exposure. *(Answer: Rs. 20,000.)*

## 10. Quick Check Questions
1. Which model is best at handling risk?
2. Write the formula for risk exposure.
3. Expand RMMM.
4. Which model suits very unclear requirements with heavy UI?

<details><summary>Answers</summary>

1. Spiral.
2. Probability x impact.
3. Risk Mitigation, Monitoring and Management.
4. Prototype.
</details>

## 11. Common Exam Mistakes and Confusing Pairs
- Giving a comparison without **suitability** column.
- Mixing risk *probability* with risk *exposure*.
