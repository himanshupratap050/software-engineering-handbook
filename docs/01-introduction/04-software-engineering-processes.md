# Software Engineering Processes and SDLC

> **Unit 1: Introduction** | **Type:** Syllabus (process) + extra (SDLC detail) | **Status:** ✅ Content ready (revise and quiz pending)
>
> **Covers:** Software process, framework activities, umbrella activities, SDLC phases, process vs product vs project
>
> **Best reference books:** Pressman, Aggarwal & Singh, Sommerville

---

## 1. Exam-Ready Definition
A **software process** is a structured set of activities, actions and tasks required to build a quality software product.
The **SDLC (Software Development Life Cycle)** is the sequence of phases a software product passes through from idea to retirement.

## 2. Core Concept
**Generic framework activities** (Pressman): Communication, Planning, Modeling, Construction, Deployment.

**Umbrella activities** that run through the whole process: project tracking and control, risk management, software quality assurance, technical reviews, measurement, configuration management, reusability management, work-product preparation.

**Typical SDLC phases**

| Phase | Output |
|---|---|
| Feasibility study | Feasibility report |
| Requirements analysis and specification | SRS document |
| Design | Design document (architecture, modules) |
| Coding / implementation | Source code |
| Testing | Test reports, defect-free build |
| Deployment | Installed system |
| Maintenance | Corrected / enhanced versions |

**Process vs Product vs Project**

| Term | Meaning | Example |
|---|---|---|
| Process | The way work is done (activities, methods) | Waterfall, Scrum |
| Product | The software that is delivered | Library Management System |
| Project | A time-bound effort to build a product using a process | Building the system in one semester |

## 3. Diagram

```
Feasibility -> Requirements -> Design -> Coding -> Testing -> Deployment -> Maintenance
                  (umbrella: planning, SQA, reviews, SCM, risk, measurement ...)
```

## 4. Advantages, Disadvantages and Comparisons
- A defined process gives **repeatability, visibility and control**.
- Too rigid a process creates overhead; the process must be *tailored* to the project.

## 5. Key Points for Revision
- Five framework activities: communication, planning, modeling, construction, deployment.
- Umbrella activities apply across all phases.
- SDLC = phases; process model = how the phases are organised.
- Process, product and project are three different things.

## 6. Likely Exam Questions

**2 Marks**
- What is a software process?
- Name the SDLC phases.

**5 Marks**
- Explain generic framework activities and umbrella activities.
- Differentiate process, product and project.

**10 Marks**
- Explain the software development life cycle with the output of each phase.

*Answer outlines:*
- Define SDLC -> diagram -> each phase with input/output -> umbrella activities -> importance of a defined process.

## 7. Project Link
Draw your project's SDLC with a **date range for each phase** and put it in `project/01-process-model-selection.md`.

## 8. Quick Check Questions
1. Name the five generic framework activities.
2. Give two umbrella activities.
3. What is the main output of the requirements phase?
4. Is "Waterfall" a process, a product or a project?

<details><summary>Answers</summary>

1. Communication, planning, modeling, construction, deployment.
2. Any two: risk management, SQA, reviews, SCM, measurement, tracking.
3. SRS document.
4. A process (model).
</details>

## 9. Common Exam Mistakes and Confusing Pairs
- Confusing **SDLC** (phases) with **process model** (organisation of phases).
- Treating umbrella activities as a separate phase; they run *throughout*.
