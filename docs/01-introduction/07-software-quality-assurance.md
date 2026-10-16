# Software Quality Assurance and SQA Plans

> **Unit 1: Introduction** | **Type:** Syllabus | **Status:** ✅ Content ready (revise and quiz pending)
>
> **Covers:** SQA, SQA activities, QA vs QC, SQA plan
>
> **Best reference books:** Pressman, Aggarwal & Singh, Sommerville

---

## 1. Exam-Ready Definition
**Software Quality Assurance (SQA)** is a set of planned, systematic activities that ensure the software *process* and *products* conform to the specified requirements and standards.
An **SQA plan** is the document that describes how those activities will be carried out for a project.

## 2. Core Concept
**SQA activities**
- Defining and enforcing standards and procedures.
- Technical reviews, inspections and audits.
- Monitoring testing activities.
- Process monitoring and improvement.
- Defect tracking and reporting.
- Change and configuration control.
- Collecting and analysing quality metrics.
- Training.

**Quality Assurance vs Quality Control vs Testing**

| Term | Focus | Nature |
|---|---|---|
| Quality Assurance (QA) | The **process**; prevent defects | Preventive |
| Quality Control (QC) | The **product**; detect defects | Detective |
| Testing | Executing the software to find defects | A QC activity |

**Typical contents of an SQA plan** (IEEE-style; exact headings vary by edition): purpose and scope, reference documents, management and responsibilities, documentation to be produced, standards and metrics, reviews and audits, testing, problem reporting and corrective action, tools and techniques, configuration control, records, training, risk management.

## 3. Diagram

```
Standards -> Process followed? --(audit)--> Product conforms? --(review/test)--> Release
              (QA: prevention)                (QC: detection)
```

## 4. Advantages, Disadvantages and Comparisons

| Benefits | Costs |
|---|---|
| Fewer defects in later phases | Extra effort and cost early |
| Better customer confidence | Needs trained staff |
| Cheaper maintenance | Can be seen as overhead |

## 5. Key Points for Revision
- SQA covers the process *and* the product.
- QA = prevention, QC = detection.
- SQA plan documents what, who, when and how for quality.
- Reviews and audits are core SQA activities.

## 6. Likely Exam Questions

**2 Marks**
- Define SQA.
- Differentiate QA and QC (any two points).

**5 Marks**
- Explain SQA activities.
- What are the contents of an SQA plan?

**10 Marks**
- Explain SQA in detail: objectives, activities, QA vs QC and the SQA plan.

*Answer outlines:*
- Definition -> objectives -> activities list -> QA/QC table -> plan contents -> benefits.

## 7. Project Link
Write a **one-page mini SQA plan** for your project: who reviews, which standards (naming, coding), how defects are logged.

## 8. Quick Check Questions
1. Is QA preventive or detective?
2. Name three SQA activities.
3. Is testing a QA or QC activity?
4. What does an SQA plan describe?

<details><summary>Answers</summary>

1. Preventive.
2. Reviews, audits, standards enforcement, metrics collection (any three).
3. QC.
4. How quality will be ensured: activities, responsibilities, standards, reviews, reporting.
</details>

## 9. Common Exam Mistakes and Confusing Pairs
- **QA vs QC vs Testing**: do not treat them as the same.
- Saying SQA is "only testing".
