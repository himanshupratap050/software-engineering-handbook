# Verification and Validation

> **Unit 1: Introduction** | **Type:** Syllabus | **Status:** ✅ Content ready (revise and quiz pending)
>
> **Covers:** Verification, validation, differences, relation to testing and reviews
>
> **Best reference books:** Pressman, Aggarwal & Singh, Sommerville

---

## 1. Exam-Ready Definition
**Verification** checks whether the product is being built *correctly*, i.e. each phase's output conforms to the previous phase's specification. (*"Are we building the product right?"*)
**Validation** checks whether the *right product* is being built, i.e. the final software meets the user's actual needs. (*"Are we building the right product?"*)

## 2. Core Concept
- Verification works mostly on documents and code **without executing** it: reviews, walkthroughs, inspections (static techniques).
- Validation works on the **running software**: testing against user requirements (dynamic techniques), ending with acceptance testing.

**Example:** Verification checks that the design document matches the SRS. Validation checks that the finished app really lets a student issue a library book as the librarian expects.

## 3. Diagram

```
User needs -> SRS -> Design -> Code -> Software
        \_______ Verification (each step vs previous) _______/
 Validation: Software ----checked against----> User needs
```

## 4. Advantages, Disadvantages and Comparisons

| Basis | Verification | Validation |
|---|---|---|
| Question | Are we building the product right? | Are we building the right product? |
| Checks | Conformance to specification | Conformance to user needs |
| Technique | Static (review, inspection, walkthrough) | Dynamic (testing) |
| Execution of code | Not required | Required |
| When | Throughout development, early | Mainly after code is built |
| Done by | Developers, QA team | Testers, users |

## 5. Key Points for Revision
- Verification = "right way", Validation = "right product".
- Both are needed; a product can pass verification yet fail validation (built correctly from a wrong SRS).
- Verification is static, validation is dynamic.

## 6. Likely Exam Questions

**2 Marks**
- Define verification and validation.

**5 Marks**
- Differentiate verification and validation with examples.

**10 Marks**
- Explain V&V activities across the life cycle, with techniques and a comparison.

*Answer outlines:*
- Definitions -> boehm one-liners -> table -> example -> techniques -> conclusion that both are needed.

## 7. Project Link
In your project plan, list which deliverable is **verified** (SRS review, design review) and which is **validated** (demo to a user or teacher).

## 8. Quick Check Questions
1. Which one needs code execution: verification or validation?
2. Walkthroughs belong to which one?
3. Can software pass verification but fail validation? Explain.
4. Which one asks "right product"?

<details><summary>Answers</summary>

1. Validation.
2. Verification.
3. Yes: it matches a faulty SRS but does not meet the real user need.
4. Validation.
</details>

## 9. Common Exam Mistakes and Confusing Pairs
- Swapping the two one-line definitions.
- Saying "testing is verification". Testing is mainly **validation**.
- Forgetting that both apply to *all* phases.
