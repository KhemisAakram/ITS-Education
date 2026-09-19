# Level 1 Project Validation Matrix

**Status:** Planning validation — not a claim that original detailed project files were recovered.

## Validation basis
This review compares the 24 production project drafts against:
- the Level 1 laboratory BOM
- the Level 1 assessment system
- the established 24-session project sequence

The BOM confirms planned quantities for breadboards, Arduino-compatible boards, motors, servos, motor drivers, sensors, LEDs, resistors, buttons, potentiometers, buzzers, USB cables, power solutions, and shared equipment. Exact part numbers, suppliers, and prices remain unfrozen.

The assessment system requires evidence of understanding, function, safe working, testing, debugging, improvement, communication, and independence across eight domains.

## Matrix

| Project | BOM coverage | Assessment coverage | Main validation status |
|---|---|---|---|
| P-001 LED Circuit | Confirmed | Electronics, Engineering, Safety, Testing | Ready for detailed classroom validation |
| P-002 LED Indicator | Confirmed | Electronics, Debugging, Communication | Ready for detailed classroom validation |
| P-003 Push-Button LED | Confirmed | Electronics, Debugging, Communication | Ready for detailed classroom validation |
| P-004 Mini Traffic Light | Confirmed | Electronics, Engineering, Testing | Validate whether sequence is manual or programmed |
| P-005 LED Control Experiment | Confirmed | Electronics, Testing, Communication | Validate resistor-value set before use |
| P-006 Brightness Controller | Confirmed | Electronics, Testing, Improvement | Validate potentiometer circuit design |
| P-007 Electronic Doorbell | Confirmed | Electronics, Actuators, Communication | Validate buzzer specification and supply |
| P-008 Mini Electronic Security Alarm | Confirmed | Electronics, Engineering, Debugging | Define exact trigger mechanism |
| P-009 Sensor Experiment | Confirmed in general | Sensors, Testing, Communication | Select exact introductory sensor |
| P-010 Automatic Night Light | Confirmed | Sensors, Electronics, Engineering | Define exact light-sensor implementation |
| P-011 Simple Temperature Monitor | Confirmed in general | Sensors, Communication, Testing | Select exact temperature-sensor implementation |
| P-012 Mini Sensor Challenge | Confirmed in general | Sensors, Engineering, Debugging | Define approved sensor/output combinations |
| P-013 Mini Motor System | Confirmed | Actuators, Engineering, Safety | Validate motor power arrangement |
| P-014 Controlled Motor System | Confirmed | Actuators, Electronics, Debugging | Define exact control method |
| P-015 Servo-Controlled Mechanism | Confirmed | Actuators, Engineering, Safety | Validate servo supply and mechanical load |
| P-016 Automatic Gate | Confirmed | Engineering, Actuators, Debugging | Define trigger/control implementation |
| P-017 Programmable LED | Confirmed | Programming, Electronics, Debugging | Freeze board, software, and pin convention |
| P-018 Button-Controlled Programmable System | Confirmed | Programming, Electronics, Debugging | Freeze button input circuit and pin convention |
| P-019 Programmable Light System | Confirmed | Programming, Communication, Testing | Freeze loop/timing requirements |
| P-020 Smart Sensor Device | Confirmed | Sensors, Programming, Engineering | Freeze sensor, output, and response rule |
| P-021 Simple Two-Wheel Robot | Confirmed | Robotics, Actuators, Engineering, Safety | Validate chassis, driver, battery, and motor pairing |
| P-022 Sensor-Controlled Robot | Confirmed | Robotics, Sensors, Programming, Debugging | Freeze sensor type and behavior target |
| P-023 Student Invention | Uses approved inventory | All relevant domains | Teacher approval and risk review required |
| P-024 Maker Demonstration Day | Existing project + documentation | All eight domains as applicable | Final rubric/evidence checklist required |

## Cross-project findings

### 1. Equipment compatibility
The planned BOM supports the overall Level 1 sequence. The following categories are explicitly represented:
- LEDs/resistors
- buttons/potentiometers
- buzzers
- light and temperature sensors
- distance sensors
- DC motors
- servos
- motor drivers
- Arduino-compatible boards
- breadboards and USB cables
- power solutions
- multimeters
- shared specialist equipment

However, the BOM does not yet freeze exact models, electrical ratings, pinouts, or supplier-specific alternatives.

### 2. Assessment compatibility
The project system can provide evidence for the assessment framework because projects include build, test, debugging, explanation, improvement, and independence evidence.

The later projects provide the strongest evidence for programming, robotics, and engineering. Earlier projects should not be forced to assess domains that have not yet been taught.

### 3. Safety validation
The drafts contain project-level safety prompts, but the repository still needs a formal **Level 1 laboratory safety standard** covering:
- low-voltage power rules
- short-circuit prevention
- motor/servo moving-part rules
- battery handling
- USB/computer safety
- soldering rules
- tool use
- damaged components
- teacher approval for modified power arrangements
- emergency response

### 4. Prerequisite validation
The progression is internally coherent at the curriculum level:
- basic circuits precede sensors
- sensors precede integrated sensor systems
- motors precede robotics
- microcontrollers precede programmed sensor/robot systems
- open invention follows the taught technical sequence

Exact prerequisite checks must still be performed against the final lesson-plan procedures once those procedures are restored or finalized.

## Required pre-pilot actions

1. Freeze exact Level 1 component specifications.
2. Map each project to exact BOM item IDs.
3. Define exact circuit diagrams and, where relevant, pin assignments.
4. Validate power arrangements for every motor, servo, sensor, and controller project.
5. Create the Level 1 laboratory safety standard.
6. Create project-specific teacher setup/checklists.
7. Define the minimum evidence required for each project.
8. Define the P-023 approval/risk process.
9. Define the P-024 final assessment checklist.
10. Perform a complete dry-run of P-001 through P-024 using the planned equipment.

## Readiness rule

The project system should be considered **pilot-ready only after** the exact component/electrical specifications, safety procedures, teacher setup instructions, and project evidence requirements have been validated in a physical dry run.

