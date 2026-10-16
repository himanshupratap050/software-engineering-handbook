# Spiral and Evolutionary Development Models

> **Unit 1: Introduction** | **Type:** Syllabus | **Status:** ✅ Content ready (revise and quiz pending)
>
> **Covers:** Spiral model (Boehm), evolutionary development, exploratory development
>
> **Best reference books:** Pressman, Aggarwal & Singh, Sommerville

---

## 1. Exam-Ready Definition
The **Spiral model** (Barry Boehm) is a risk-driven, iterative model in which each loop of the spiral passes through objective setting, risk analysis, development and planning.
**Evolutionary development** builds an initial version, exposes it to the user and keeps refining it through several versions until the system is acceptable.

## 2. Core Concept

**Spiral model - four quadrants per loop**
1. Determine objectives, alternatives and constraints.
2. Evaluate alternatives and identify and resolve **risks** (may use prototypes and simulation).
3. Develop and verify the next-level product.
4. Plan the next phase and review with the customer.

Radial distance = cumulative cost; angle = progress. The number of loops is not fixed.

**Evolutionary models**
- *Exploratory development:* start with the parts the customer understands, add features as the customer proposes them.
- *Throwaway prototyping:* build to understand requirements, then discard.

## 3. Diagram

```
        2. Risk analysis
     +---------------------+
1. Objectives          3. Develop & verify
     +---------------------+
        4. Plan next loop
   (spiral outward: more cost, more complete product)
```

## 4. Advantages, Disadvantages and Comparisons

| Model | Advantages | Disadvantages |
|---|---|---|
| Spiral | Risk handling, suits large and critical projects, flexible with change | Costly, needs risk expertise, complex to manage, not for small projects |
| Evolutionary | Handles changing requirements, early user feedback | Poor process visibility, system may become badly structured, hard to estimate |

## 5. Key Points for Revision
- Spiral = **risk-driven**, four quadrants.
- Suitable for large, high-risk projects.
- Evolutionary = build, show, refine.
- Evolutionary systems risk poor structure over time.

## 6. Likely Exam Questions

**2 Marks**
- Name the four quadrants of the spiral model.

**5 Marks**
- Explain the spiral model with its advantages and disadvantages.

**10 Marks**
- Compare waterfall, prototype and spiral models.

*Answer outlines:*
- Spiral diagram and quadrants -> role of risk -> merits/demerits -> evolutionary approach -> comparison.

## 7. Project Link
List **two risks** of your project and show in which spiral quadrant you would handle them.

## 8. Quick Check Questions
1. What does the radius of the spiral represent?
2. Which quadrant deals with risk?
3. Why is the spiral model not used for small projects?
4. Give one weakness of evolutionary development.

<details><summary>Answers</summary>

1. Cumulative cost.
2. Quadrant 2 (evaluate alternatives, identify and resolve risks).
3. Risk analysis effort makes it costly and complex.
4. Poor process visibility or poorly structured system.
</details>

## 9. Common Exam Mistakes and Confusing Pairs
- Calling spiral just "waterfall in loops". It is **risk driven**.
- Mixing **exploratory development** and **throwaway prototyping**.
