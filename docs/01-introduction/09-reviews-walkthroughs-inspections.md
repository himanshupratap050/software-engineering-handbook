# Reviews, Walkthroughs and Inspections

> **Unit 1: Introduction** | **Type:** Extra (supports Verification) | **Status:** ✅ Content ready (revise and quiz pending)
>
> **Covers:** Formal technical review, walkthrough, inspection, roles and comparison
>
> **Best reference books:** Pressman, Aggarwal & Singh, Sommerville

---

## 1. Exam-Ready Definition
A **review** is a systematic examination of a work product (SRS, design, code) by people other than the author to find defects early. **Walkthrough** and **inspection** are two kinds of review that differ in formality.

## 2. Core Concept
- **Walkthrough:** informal. The *author* explains the product step by step to peers who raise questions. Goal: find defects and share understanding.
- **Inspection:** formal and rigorous, led by a trained *moderator*, uses checklists, fixed roles, documented defects and metrics.
- **Technical review:** formal team evaluation of a product against standards and specifications.

**Inspection process:** planning -> overview -> individual preparation -> inspection meeting -> rework -> follow-up.

**Roles:** moderator, author, reader, recorder, inspectors.

## 3. Diagram

```
Planning -> Overview -> Preparation -> Meeting -> Rework -> Follow-up
```

## 4. Advantages, Disadvantages and Comparisons

| Basis | Walkthrough | Inspection |
|---|---|---|
| Formality | Informal | Formal |
| Led by | Author | Trained moderator |
| Checklist | Not mandatory | Used |
| Defect record | Optional | Mandatory |
| Metrics | Rarely | Collected |
| Defect-finding power | Lower | Higher |

**Benefit:** defects found early are far cheaper to fix than defects found in testing or after release.

## 5. Key Points for Revision
- Reviews are static verification techniques.
- Inspection is the most formal and effective.
- The author does not lead an inspection.
- Rework and follow-up close the loop.

## 6. Likely Exam Questions

**2 Marks**
- What is an inspection?

**5 Marks**
- Differentiate walkthrough and inspection.

**10 Marks**
- Explain the inspection process with roles and benefits.

*Answer outlines:*
- Definition -> six steps -> roles -> comparison table -> benefits.

## 7. Project Link
Do a **peer walkthrough** of your SRS with one classmate and log 5 defects found.

## 8. Quick Check Questions
1. Who leads an inspection?
2. Name two roles in an inspection.
3. Which review type is the most formal?
4. Why are reviews cost effective?

<details><summary>Answers</summary>

1. A trained moderator.
2. Moderator, author, reader, recorder, inspector (any two).
3. Inspection.
4. They find defects early when fixing is cheap.
</details>

## 9. Common Exam Mistakes and Confusing Pairs
- Saying the **author** leads an inspection (he leads the walkthrough).
- Treating reviews as testing; reviews do not execute code.
