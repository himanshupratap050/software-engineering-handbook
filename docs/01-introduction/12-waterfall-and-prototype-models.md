# Waterfall and Prototype Models

> **Unit 1: Introduction** | **Type:** Syllabus | **Status:** ✅ Content ready (revise and quiz pending)
>
> **Covers:** Waterfall model, Prototype model, advantages, disadvantages, when to use
>
> **Best reference books:** Pressman, Aggarwal & Singh, Sommerville

---

## 1. Exam-Ready Definition
The **Waterfall model** is a linear sequential life cycle in which each phase must finish before the next begins.
The **Prototype model** builds a working sample of the system early, lets the user evaluate it, and refines requirements from the feedback.

## 2. Core Concept

**Waterfall phases:** Requirements analysis and specification -> Design -> Implementation (coding and unit testing) -> Integration and system testing -> Deployment -> Maintenance.
Each phase produces documents that are reviewed before moving on. The classical model has no going back; the *iterative waterfall* allows feedback to the previous phase.

**Prototype model steps:** quick requirements gathering -> quick design -> build prototype -> customer evaluation -> refine requirements -> repeat -> build the actual product.
Prototypes can be **throwaway** (discarded after requirements are clear) or **evolutionary** (grow into the final product).

## 3. Diagram

```
Waterfall:                         Prototype:
Requirements                       Requirements (quick)
     |                                  |
   Design                           Quick design
     |                                  |
   Coding                       +-> Build prototype
     |                          |       |
   Testing                      |   Customer evaluation
     |                          +-- refine (loop)
 Maintenance                            |
                                  Final product
```

## 4. Advantages, Disadvantages and Comparisons

| | Waterfall | Prototype |
|---|---|---|
| Advantages | Simple, easy to manage, good documentation, clear milestones | Reduces requirement risk, early user feedback, better user satisfaction |
| Disadvantages | Rigid, late testing, working software only at the end, poor with changing requirements | Can increase cost and time, users may mistake it for the final product, poor design from quick builds |
| Best when | Requirements are clear and stable | Requirements are unclear or the UI is important |

## 5. Key Points for Revision
- Waterfall is linear; testing starts late.
- Prototype handles unclear requirements.
- Throwaway vs evolutionary prototypes.
- Waterfall = documents driven; prototype = feedback driven.

## 6. Likely Exam Questions

**2 Marks**
- Name the phases of the waterfall model.
- What is a throwaway prototype?

**5 Marks**
- Explain the waterfall model with advantages and disadvantages.

**10 Marks**
- Compare the waterfall and prototype models and state when each is suitable.

*Answer outlines:*
- Diagram -> phases -> pros/cons -> prototype steps -> comparison table -> suitability.

## 7. Project Link
Decide whether your project suits waterfall or prototyping, and write **two reasons** in `project/01-process-model-selection.md`.

## 8. Quick Check Questions
1. In which model is working software available only at the end?
2. Which model is better when requirements are unclear?
3. Name the two kinds of prototype.
4. Why can the prototype model increase cost?

<details><summary>Answers</summary>

1. Waterfall.
2. Prototype.
3. Throwaway and evolutionary.
4. Repeated rebuilding, user change requests and extra effort on the prototype.
</details>

## 9. Common Exam Mistakes and Confusing Pairs
- Drawing waterfall with back arrows but calling it classical (that is *iterative waterfall*).
- Mixing **prototype** with the **final product**.
