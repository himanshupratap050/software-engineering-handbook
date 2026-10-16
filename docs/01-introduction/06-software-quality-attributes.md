# Software Quality Attributes and Quality Models

> **Unit 1: Introduction** | **Type:** Syllabus (attributes) + extra (models) | **Status:** ✅ Content ready (revise and quiz pending)
>
> **Covers:** Quality attributes, McCall's, Boehm's and ISO 9126 quality models
>
> **Best reference books:** Pressman, Aggarwal & Singh, Sommerville

---

## 1. Exam-Ready Definition
**Software quality** is the degree to which software meets the stated and implied needs of its users (conformance to requirements and fitness for use).
**Quality attributes** are measurable characteristics through which quality is judged.

## 2. Core Concept

**Commonly listed attributes:** functionality, reliability, usability, efficiency, maintainability, portability.

**ISO 9126 (six characteristics)**

| Characteristic | Meaning |
|---|---|
| Functionality | Does it provide the required functions correctly? |
| Reliability | Does it keep performing under stated conditions? |
| Usability | Is it easy to learn and use? |
| Efficiency | Does it use time and resources well? |
| Maintainability | Is it easy to correct and modify? |
| Portability | Can it move to another environment easily? |

> ISO 9126 was later superseded by the ISO/IEC 25010 family, which also includes characteristics such as security and compatibility. The exact list differs by edition, so confirm with your prescribed textbook.

**McCall's quality model** groups factors by three perspectives:

| Perspective | Factors |
|---|---|
| Product operation | Correctness, Reliability, Efficiency, Integrity, Usability |
| Product revision | Maintainability, Flexibility, Testability |
| Product transition | Portability, Reusability, Interoperability |

**Boehm's model** is hierarchical: *general utility* depends on *as-is utility*, *maintainability* and *portability*. As-is utility is split into reliability, efficiency and human engineering (usability); maintainability into testability, understandability and modifiability.

## 3. Diagram

```
McCall:   Product Revision <--- Product Operation ---> Product Transition
          (change)             (day to day use)        (new environment)
```

## 4. Advantages, Disadvantages and Comparisons

| Model | Strength | Limitation |
|---|---|---|
| McCall | Clear grouping by life-cycle view | Some factors overlap |
| Boehm | Hierarchical, stresses maintainability | More complex to apply |
| ISO 9126 | International standard, six clear characteristics | Replaced by newer standard |

## 5. Key Points for Revision
- Quality = conformance to requirements + fitness for use.
- ISO 9126 has six characteristics.
- McCall has three perspectives and eleven factors.
- Boehm is hierarchical.

## 6. Likely Exam Questions

**2 Marks**
- Define software quality.
- Name the six ISO 9126 characteristics.

**5 Marks**
- Explain McCall's quality factors.

**10 Marks**
- Compare McCall's, Boehm's and ISO 9126 quality models.

*Answer outlines:*
- Quality definition -> list attributes -> McCall table -> Boehm hierarchy -> ISO 9126 table -> comparison table.

## 7. Project Link
Pick **three quality attributes** most important for your project (e.g. usability, reliability, portability) and write a measurable target for each (e.g. "a new user completes a booking in under 2 minutes").

## 8. Quick Check Questions
1. List the six ISO 9126 characteristics.
2. Under which McCall perspective do portability and reusability fall?
3. Which attribute is about ease of correcting faults?
4. Who proposed the hierarchical quality model with "general utility" at the top?

<details><summary>Answers</summary>

1. Functionality, reliability, usability, efficiency, maintainability, portability.
2. Product transition.
3. Maintainability.
4. Boehm.
</details>

## 9. Common Exam Mistakes and Confusing Pairs
- Mixing **reliability** (keeps working) with **correctness** (does what is specified).
- Placing factors under the wrong McCall perspective.
- Using the old six-characteristic list while claiming it is ISO 25010.
