# Software Components and Characteristics

> **Unit 1: Introduction** | **Type:** Syllabus | **Status:** ✅ Content ready (revise and quiz pending)
>
> **Covers:** Software components, software characteristics, software failure curve
>
> **Best reference books:** Pressman, Aggarwal & Singh, Sommerville

---

## 1. Exam-Ready Definition
**Software components** are the parts that make up a software product: *programs (instructions), data/data structures and documentation*.
**Software characteristics** are the properties that distinguish software from hardware: it is *developed (engineered), not manufactured*; it *does not wear out* but *deteriorates through change*; and most software is *custom built*.

## 2. Core Concept

**Components**

| Component | Description | Examples |
|---|---|---|
| Programs | Instructions that give the required function | Source code, executables |
| Data / data structures | Data the programs use and manage | Database tables, files, configuration |
| Documentation | Describes the construction and use | SRS, design document, test plan, user manual |

**Key characteristics**
1. **Software is developed or engineered, not manufactured.** The cost lies in design and development; copying is almost free. Quality problems are *design* problems.
2. **Software does not wear out.** No physical aging. But it **deteriorates** because of repeated changes that introduce new defects.
3. **Most software is custom built.** Reusable component-based construction is still limited, unlike hardware where standard parts are used.
4. **Software is logical, not physical.** It is invisible and intangible.

**Quality-related characteristics** (as listed in many Indian textbooks): functionality, reliability, usability, efficiency, maintainability, portability.

**Failure curves**
- *Hardware* follows the **bathtub curve**: high early failures (infant mortality), a low steady period, then rising failures due to wear-out.
- *Software* has no wear-out phase. In the **idealized curve** failures drop after early debugging and stay low. In the **actual curve**, every change causes a **spike** in failures, so the baseline slowly rises and the software deteriorates.

## 3. Diagram

```
Hardware (bathtub)               Software (actual)
failure                          failure
rate                             rate
 |\                    /          |\   /\    /\    / | \                  /           | \_/  \__/  \__/  \___  <- rises with changes
 |  \________________/            |
 +-----------------------> time   +-----------------------> time
  infant   useful life  wear-out    each spike = a change
```

## 4. Advantages, Disadvantages and Comparisons

| Hardware | Software |
|---|---|
| Manufactured | Developed / engineered |
| Wears out (physical aging) | Does not wear out, but deteriorates by change |
| Failure follows bathtub curve | Failure follows spike curve |
| Spare parts replace failed parts | No spare parts, defects must be fixed in design/code |
| Mostly assembled from standard components | Mostly custom built |

## 5. Key Points for Revision
- Components: programs, data, documentation.
- Software is engineered, does not wear out, and is mostly custom built.
- Software deteriorates due to change, not due to aging.
- Hardware: bathtub curve; Software: spike curve.

## 6. Likely Exam Questions

**2 Marks**
- List the components of software.
- Why does software not wear out?

**5 Marks**
- Explain the characteristics of software.
- Differentiate hardware and software failure curves.

**10 Marks**
- Discuss software components and characteristics with the failure curve diagrams for hardware and software.

*Answer outlines:*
- Components table -> 4 characteristics with one line each -> two curves with a diagram -> hardware vs software table.

## 7. Project Link
List the **documents** your project will produce (SRS, design, test plan, user manual). This becomes the checklist of your `project/` folder.

## 8. Quick Check Questions
1. Does software wear out? Explain in two lines.
2. Which hardware failure curve phase has no software equivalent?
3. Why is software called "custom built"?
4. Name any four documentation items.

<details><summary>Answers</summary>

1. No. It has no physical aging, but changes introduce defects so it deteriorates.
2. The wear-out phase.
3. Most software is built for specific needs rather than assembled from standard parts.
4. SRS, design document, test plan, user manual, etc.
</details>

## 9. Common Exam Mistakes and Confusing Pairs
- Saying "software wears out". Correct: it *deteriorates*.
- Drawing the bathtub curve for software.
- Forgetting **data** and **documentation** as components.
