# ITS Education Course Architecture

## Purpose

This document defines the standard structure of ITS Education programs.

It connects the master curriculum map to the detailed Level 1–4 course-development chats.

The hierarchy is:

**Institute → Level → Course → Module → Session → Project → Assessment → Portfolio**

Individual level chats develop the detailed content. This document defines the architecture they should follow.

---

# 1. Institute structure

ITS Education is organized into four primary developmental levels:

| Level | Identity | Primary purpose |
|---|---|---|
| Level 1 | Explorer | Discover technology through guided building and experimentation |
| Level 2 | Maker | Understand systems and build functional projects |
| Level 3 | Junior Engineer | Design and integrate engineering systems |
| Level 4 | Young Engineer | Independently engineer complete systems and products |

A level may contain one or more courses as the institute develops.

---

# 2. Course

A **course** is a defined learning program with:

- Target level
- Target student profile
- Prerequisites
- Duration
- Learning outcomes
- Modules
- Sessions
- Projects
- Assessment
- Portfolio evidence
- Completion requirements
- Progression relationship to the next course or level

A course should have a clear beginning, progression and completion point.

---

# 3. Module

A **module** is a coherent group of sessions organized around a technical or engineering theme.

Examples:

- Electricity and circuits
- Electronics components
- Sensors
- Motors and actuators
- Microcontrollers
- Programming
- Robotics
- Engineering design

Modules should build toward projects rather than operate as isolated theory units.

---

# 4. Session

A **session** is one classroom learning unit.

Each session should define:

- Session number
- Title
- Duration
- Learning objectives
- Concepts
- Vocabulary
- Demonstration
- Experiment
- Project activity
- Materials/equipment
- Safety requirements
- Teacher preparation
- Student evidence
- Assessment
- Extension/support options

The standard session structure should remain compatible with the institute teaching methodology:

**Concept → Demonstration → Experiment → Project → Debugging/Presentation → Reflection**

The exact timing can vary by course.

---

# 5. Project

Projects are the main application layer.

Each significant project should define:

- Problem or goal
- Learning objectives
- Required concepts
- Components/materials
- Tools
- Safety
- System architecture
- Build procedure
- Testing
- Debugging
- Improvement challenge
- Extension challenge
- Student explanation
- Assessment
- Evidence required

Project difficulty and openness must increase from Level 1 to Level 4.

---

# 6. Assessment

Assessment should exist at multiple levels:

### Session assessment
Checks whether the student understood and can perform the current skill.

### Project assessment
Checks whether the student can build, test, debug, explain and improve the project.

### Course assessment
Checks the complete set of course competencies.

### Level progression assessment
Determines whether the student has demonstrated the competencies required for the next level.

Assessment should measure demonstrated capability rather than attendance or copying.

---

# 7. Portfolio

Every course contributes evidence to the student's long-term portfolio.

Possible evidence includes:

- Engineering notebook pages
- Circuit sketches
- Programs
- Photos/videos of projects
- Project reports
- Test results
- Debugging records
- Design iterations
- Teacher observations
- Student explanations
- Final project evidence

The portfolio should show **growth**, not simply a collection of finished objects.

---

# 8. Course naming

Course names should be:

- Short
- Consistent
- Easy for students and parents to understand
- Stable enough for version control
- Connected to the level

Recommended internal pattern:

**[Subject/Theme] — Level [Number]**

Examples:

- Electronics & Programming — Level 1
- Electronics & Robotics — Level 2
- Robotics & Engineering — Level 3
- Embedded Systems & Engineering — Level 4

Specific course names can be finalized separately as the level programs are developed.

---

# 9. Prerequisites

Each course should define:

### Entry requirements

What the student should already know or be able to do.

### Recommended prior course

The normal course or level that prepares the student.

### Alternative entry route

When appropriate, a student may enter through an assessment demonstrating equivalent competencies.

### Exit requirements

What the student should be able to do after completing the course.

Prerequisites should increasingly be competency-based rather than age-only.

---

# 10. Course dependency model

The intended progression is:

**Level 1 foundations**
↓
**Level 2 making**
↓
**Level 3 engineering**
↓
**Level 4 advanced engineering**

However, not every future course must be strictly linear.

Specialized courses may branch from demonstrated competencies.

Example:

**Level 3 core engineering**
→ Robotics specialization  
→ Embedded systems specialization  
→ IoT specialization  
→ Advanced electronics specialization

The branching model should be introduced only when the core pathway is sufficiently developed.

---

# 11. Course design rule

Every course should answer:

1. Who is this course for?
2. What should students already know?
3. What will students learn?
4. What will students build?
5. What will students be able to explain?
6. What will students be able to debug?
7. What decisions will students make independently?
8. What evidence will demonstrate learning?
9. What can students do after completing the course?
10. What course or level does this prepare them for?

---

# 12. Course progression model

A course should normally progress through:

**Foundation → Guided Practice → Integration → Project → Independent Application → Assessment**

At higher levels:

**Problem → Requirements → Design → Prototype → Integration → Test → Debug → Iterate → Present**

The appropriate model depends on the level and course.

---

# 13. Guidance progression

Teacher guidance should decrease as students progress.

| Level | Typical course structure |
|---|---|
| Level 1 | Demonstration + guided experiment + guided project |
| Level 2 | Concept + experiment + structured project + choices |
| Level 3 | Engineering challenge + design + prototype + testing |
| Level 4 | Problem definition + independent engineering + validation |

This is an architecture principle, not a fixed lesson script.

---

# 14. Course workload architecture

Each course must explicitly define:

- Number of sessions
- Session duration
- Sessions per week
- Total classroom hours
- Expected project time
- Assessment time
- Required preparation
- Required equipment
- Required student materials

The actual values are determined separately for each course.

The existing Level 1 pilot uses:

**24 sessions × 90 minutes = 36 classroom hours**

This is a Level 1 pilot configuration, not a universal requirement for all future courses.

---

# 15. Course quality gates

Before a course is considered ready for pilot use, it should pass these gates:

### Gate 1 — Curriculum alignment
The course fits the master curriculum and progression framework.

### Gate 2 — Learning outcomes
Outcomes are measurable and appropriate for the level.

### Gate 3 — Project alignment
Projects directly develop the intended competencies.

### Gate 4 — Equipment feasibility
All required equipment and materials are defined and available or planned.

### Gate 5 — Safety
Risks and safety procedures are defined.

### Gate 6 — Assessment
Student evidence and assessment criteria are defined.

### Gate 7 — Teacher readiness
Teacher preparation and guidance are defined.

### Gate 8 — Student materials
Required notebook/workbook/project materials exist.

### Gate 9 — Practical validation
The course has been reviewed or physically dry-run where appropriate.

### Gate 10 — Pilot evaluation
After delivery, actual results are used to revise the course.

---

# 16. Course release lifecycle

The standard lifecycle is:

**Architecture**
→ **Draft**
→ **Technical review**
→ **Educational review**
→ **Materials/BOM review**
→ **Teacher preparation**
→ **Dry run**
→ **Pilot**
→ **Evaluation**
→ **Revision**
→ **Release**

A course should not be considered permanently finished after its first draft.

---

# 17. Version control

Each course should maintain:

- Course README
- Course version
- Change history
- Lesson plans
- Project specifications
- Assessment
- Student materials
- Teacher materials
- Equipment/BOM
- Safety documentation

Changes that materially affect learning outcomes, safety, equipment or assessment should trigger a course version update.

---

# 18. Standard course directory

A future course should follow a structure similar to:

```text
02_COURSES/
└── level-X/
    └── course-name/
        ├── README.md
        ├── course-overview.md
        ├── learning-outcomes.md
        ├── prerequisites.md
        ├── modules/
        ├── lesson-plans/
        ├── projects/
        ├── assessment/
        ├── student-materials/
        ├── teacher-guide/
        ├── equipment-bom.md
        ├── safety.md
        └── CHANGELOG.md
```

The exact directory can evolve as the repository grows.

---

# 19. Relationship to the master map

The master documents have distinct roles:

### Curriculum Map
**What develops across the institute?**

### Progression Framework
**What must students demonstrate to progress?**

### Course Architecture
**How do we organize the learning programs that produce that progression?**

### Level Course Chat
**What exactly do we teach and build?**

### BMC / Business Chat
**How does the institute operate as a business?**

This separation prevents detailed course design from changing the overall institute architecture accidentally.

---

# 20. Master course rule

Every course must contribute to the same long-term pathway:

**Discover → Build → Program → Understand → Design → Create**

and:

**Learn → Experiment → Build → Break → Debug → Understand → Improve → Create**

The content becomes more advanced, but the underlying educational architecture remains consistent.
