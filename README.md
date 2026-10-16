# 📘 Software Engineering Handbook

A structured, topic-wise handbook for **Software Engineering (SET/CS/BT/C503)**, prepared for 5th semester students of **HNBGU (Hemvati Nandan Bahuguna Garhwal University)**. The notes follow the university syllabus unit by unit and are built from standard reference books, with a strong focus on university exam preparation and a hands-on semester project.

---

## 📂 Repository Structure

```
software-engineering-handbook/
│
├── README.md
├── LICENSE
│
├── docs/
│   ├── 01-introduction/
│   ├── 02-requirements-and-design/
│   ├── 03-measurement-and-metrics/
│   ├── 04-software-testing/
│   └── 05-software-maintenance/
│
├── project/
│   ├── 01-process-model-selection.md
│   ├── 02-feasibility-and-srs.md
│   ├── 03-dfd-erd-decision-tables.md
│   ├── 04-design-document.md
│   ├── 05-metrics-and-estimation.md
│   ├── 06-test-plan-and-test-cases.md
│   └── 07-maintenance-and-scm-plan.md
│
├── numericals/
│   └── solved-and-practice-problems.md
│
├── pyqs/
│   └── university-pyqs-unitwise.md
│
├── revision/
│   ├── flashcards.md
│   └── cheat-sheets.md
│
├── assets/
│   └── images/
│
└── resources/
    └── reference-books.md
```

---

## 📑 Chapter-wise File List

Topics marked **(extra)** are not named in the official syllabus but are included because they are commonly asked in exams, vivas, or are needed for the semester project.

### docs/01-introduction/

| File Name | Topic |
|---|---|
| 01-what-is-software-engineering.md | Definition, layered technology (process, methods, tools) |
| 02-software-components-and-characteristics.md | Software components, software characteristics |
| 03-software-crisis-and-myths.md | Software crisis, causes, software myths (extra) |
| 04-software-engineering-processes.md | Software process, product, project, SDLC phases |
| 05-se-vs-conventional-engineering.md | Similarities and differences from conventional engineering |
| 06-software-quality-attributes.md | Quality attributes, McCall, Boehm, ISO 9126 models (extra) |
| 07-software-quality-assurance.md | SQA activities, SQA plans |
| 08-verification-and-validation.md | Verification vs Validation |
| 09-reviews-walkthroughs-inspections.md | Reviews, walkthroughs, inspections (extra) |
| 10-software-quality-frameworks.md | Quality frameworks, CMM/CMMI, ISO 9001, Six Sigma (extra) |
| 11-software-reliability-basics.md | MTTF, MTBF, MTTR, availability (extra) |
| 12-waterfall-and-prototype-models.md | Waterfall Model, Prototype Model |
| 13-spiral-and-evolutionary-models.md | Spiral Model, Evolutionary Development Models |
| 14-iterative-enhancement-incremental-rad-v-models.md | Iterative Enhancement, Incremental, RAD, V-Model (extra) |
| 15-agile-overview.md | Agile, Scrum, XP overview (extra) |
| 16-model-comparison-and-risk-management.md | Model comparison table, basic risk management (extra) |

### docs/02-requirements-and-design/

| File Name | Topic |
|---|---|
| 01-requirements-elicitation.md | Elicitation techniques: interviews, questionnaires, FAST, use cases |
| 02-analysis-documentation-review-management.md | Analysis, documentation, review and management of user needs |
| 03-functional-and-non-functional-requirements.md | Functional vs non-functional requirements (extra) |
| 04-feasibility-study.md | Technical, economic, operational, schedule feasibility |
| 05-information-modeling-and-data-dictionary.md | Information modeling, data dictionary (extra) |
| 06-data-flow-diagrams.md | DFD notations, levels, rules, balancing |
| 07-entity-relationship-diagrams.md | ERD for requirements modeling |
| 08-decision-tables-and-trees.md | Decision tables, decision trees (extra) |
| 09-srs-document.md | SRS characteristics, IEEE 830 structure |
| 10-architectural-design.md | Architectural design, architectural styles (extra) |
| 11-modularization-and-design-principles.md | Modularization, abstraction, information hiding, refinement |
| 12-design-structure-charts.md | Structure charts, fan-in, fan-out |
| 13-pseudo-code-and-flow-charts.md | Pseudo code, flow charts |
| 14-coupling-and-cohesion.md | Coupling and cohesion types, measures, comparison |
| 15-function-oriented-design.md | Function-oriented design approach |
| 16-object-oriented-design.md | Object-oriented design, basic UML (extra) |
| 17-top-down-and-bottom-up-design.md | Top-down vs bottom-up design strategies |
| 18-user-interface-design.md | UI design principles and golden rules (extra) |

### docs/03-measurement-and-metrics/

| File Name | Topic |
|---|---|
| 01-metrics-basics.md | Measure, measurement, metric; product, process, project metrics (extra) |
| 02-size-oriented-measures.md | LOC, KLOC, size-oriented metrics |
| 03-halstead-software-science.md | Halstead's measures and formulas |
| 04-function-point-analysis.md | Function Point (FP) based measures, LOC vs FP |
| 05-control-flow-graphs.md | Control Flow Graph construction |
| 06-cyclomatic-complexity.md | McCabe's cyclomatic complexity |
| 07-estimation-of-cost-effort-schedule.md | Estimation basics: cost, effort, schedule/duration |
| 08-cocomo-model.md | Basic, Intermediate, Detailed COCOMO, project modes |
| 09-cocomo-ii-and-putnam-overview.md | COCOMO II, Putnam/SLIM overview (extra) |
| 10-project-scheduling.md | WBS, Gantt chart, PERT/CPM (extra) |

### docs/04-software-testing/

| File Name | Topic |
|---|---|
| 01-testing-objectives-and-principles.md | Testing objectives, principles, levels |
| 02-error-fault-failure-and-bug-life-cycle.md | Error, fault, failure, bug life cycle (extra) |
| 03-unit-testing.md | Unit testing, stubs and drivers |
| 04-integration-testing.md | Integration testing, big-bang, sandwich |
| 05-top-down-and-bottom-up-testing.md | Top-down and bottom-up testing strategies |
| 06-system-acceptance-alpha-beta-testing.md | System testing, acceptance testing, alpha and beta testing |
| 07-regression-testing.md | Regression testing |
| 08-functional-testing.md | Black-box: equivalence partitioning, boundary value analysis, cause-effect graphing |
| 09-structural-testing.md | White-box: statement, branch, condition, path coverage, basis path testing |
| 10-testing-for-functionality-and-performance.md | Functional testing vs performance, load, stress testing |
| 11-test-data-suite-and-test-cases.md | Test data suite preparation, test cases, test plan, test oracle |
| 12-static-testing-strategies.md | Static testing, code review, inspection |
| 13-debugging-and-mutation-testing.md | Debugging approaches, mutation testing overview (extra) |

### docs/05-software-maintenance/

| File Name | Topic |
|---|---|
| 01-need-and-categories-of-maintenance.md | Need for maintenance; corrective, preventive, perfective (and adaptive) |
| 02-cost-of-maintenance.md | Maintenance cost factors, Lehman's laws (extra) |
| 03-software-re-engineering.md | Software re-engineering |
| 04-reverse-engineering.md | Reverse engineering, re-engineering vs reverse engineering |
| 05-software-configuration-management.md | SCM activities, baselines, SCI, configuration audit (extra) |
| 06-change-control-process.md | Change control process |
| 07-software-version-control.md | Version control concepts, Git basics (extra) |
| 08-case-tools.md | CASE tools overview and classification |

---

## 🎯 Purpose

This handbook is built for HNBGU students who want concise, book-referenced Software Engineering notes instead of scattered internet material. Each `.md` file follows a consistent format:

1. **Exam-ready definition** (2-3 lines)
2. **Core concept** with a simple example
3. **Diagrams / tables** where useful (stored in `assets/images/`)
4. **Advantages, disadvantages and comparisons**
5. **Key points for revision**
6. **Likely exam questions** (2, 5 and 10 marks) with answer outlines
7. **Project link**: how the topic applies to the semester project
8. **Quick check questions** (3-5) at the end

Numerical topics (Halstead, Function Points, Cyclomatic Complexity, COCOMO) include step-by-step solved examples followed by a practice problem.

---

## 🛠️ Semester Project

One project is built alongside the theory. After each unit, a small task is added to the `project/` folder:

| After | Project Deliverable |
|---|---|
| Process models | Chosen process model with justification |
| Requirements | Feasibility study and SRS document |
| Modeling | Context DFD, Level 1 DFD, ERD, decision table |
| Design | Structure chart, module design, pseudo code |
| Metrics | LOC/FP count, cyclomatic complexity, COCOMO estimate |
| Testing | Test plan and test cases (black-box and white-box) |
| Maintenance | Version control setup and change request process |

---

## 📚 Reference Books

**Prescribed textbook (as per syllabus)**
1. K. K. Aggarwal and Yogesh Singh, *Software Engineering*, New Age International Publishers

**Syllabus references**
2. Roger S. Pressman, *Software Engineering: A Practitioner's Approach*, McGraw Hill
3. Ian Sommerville, *Software Engineering*, Addison Wesley

**Additional references**
4. Rajib Mall, *Fundamentals of Software Engineering*
5. Pankaj Jalote, *An Integrated Approach to Software Engineering*

---

## 🚧 Status

Work in progress. Chapters are being added topic-wise as the study progresses.

| Unit | Notes | Numericals | Project Task | Revision Pack |
|---|:---:|:---:|:---:|:---:|
| 01 Introduction | ⬜ | n/a | ⬜ | ⬜ |
| 02 Requirements and Design | ⬜ | n/a | ⬜ | ⬜ |
| 03 Measurement and Metrics | ⬜ | ⬜ | ⬜ | ⬜ |
| 04 Software Testing | ⬜ | ⬜ | ⬜ | ⬜ |
| 05 Software Maintenance | ⬜ | n/a | ⬜ | ⬜ |

---

## 🤝 Contribution

This is a personal study handbook, but suggestions and corrections are welcome via issues or pull requests.
