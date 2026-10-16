# Iterative Enhancement, Incremental, RAD and V Models

> **Unit 1: Introduction** | **Type:** Syllabus (iterative enhancement) + extra (others) | **Status:** ✅ Content ready (revise and quiz pending)
>
> **Covers:** Iterative enhancement model, incremental model, RAD model, V-model
>
> **Best reference books:** Pressman, Aggarwal & Singh, Sommerville

---

## 1. Exam-Ready Definition
**Iterative enhancement:** start with a simple implementation of a subset of requirements and enhance it version by version.
**Incremental model:** deliver the system in working increments, core functions first.
**RAD (Rapid Application Development):** a very short, component-based, parallel-team cycle.
**V-model:** a waterfall variant that pairs every development phase with a testing phase.

## 2. Core Concept
- **Iterative enhancement:** work from a *project control list* of tasks; each iteration designs, implements and analyses, then the list is revised. The whole product is *refined* each time.
- **Incremental:** the product is split into increments; each increment is a working part delivered to the user. The product *grows*.
- **Iterative vs Incremental:** iterative refines the same whole; incremental adds new pieces.
- **RAD phases:** business modeling, data modeling, process modeling, application generation, testing and turnover. Targets short cycles (commonly 60-90 days) with reusable components.
- **V-model pairs:** Requirements <-> Acceptance testing; High-level design <-> System testing; Detailed design <-> Integration testing; Coding <-> Unit testing.

## 3. Diagram

```
V-model
Requirements ----------------------> Acceptance test
  High-level design --------------> System test
    Detailed design ------------> Integration test
      Coding ---------------> Unit test
```

## 4. Advantages, Disadvantages and Comparisons

| Model | Advantages | Disadvantages |
|---|---|---|
| Iterative enhancement | Early working version, easier to test and change | Needs good initial design, final cost unclear |
| Incremental | Early delivery, lower risk, easier testing | Needs good planning and modular design |
| RAD | Fast delivery, reuse, user involvement | Needs skilled team, not for large or high-risk systems |
| V-model | Testing planned early, clear verification/validation | Rigid, no early prototype |

## 5. Key Points for Revision
- Iterative = refine whole; Incremental = add parts.
- RAD has five phases and short time-boxed cycles.
- V-model ties each design level to a test level.

## 6. Likely Exam Questions

**2 Marks**
- Differentiate iterative and incremental.
- Draw the V-model.

**5 Marks**
- Explain the iterative enhancement model.
- Explain RAD and its phases.

**10 Marks**
- Explain incremental, RAD and V models with advantages and limitations.

*Answer outlines:*
- Definition -> diagram -> phases -> pros/cons -> suitability.

## 7. Project Link
Split your project into **3 increments** (core, extended, final) and list the features in each.

## 8. Quick Check Questions
1. Which test level pairs with detailed design in the V-model?
2. How many phases does RAD have?
3. Which model delivers a working core first?
4. One limitation of RAD?

<details><summary>Answers</summary>

1. Integration testing.
2. Five.
3. Incremental.
4. Needs skilled team, unsuitable for large high-risk systems.
</details>

## 9. Common Exam Mistakes and Confusing Pairs
- **Iterative vs Incremental** confusion.
- Pairing wrong test levels in the V-model.
