# P-013 — Mini Motor System

**Course:** Electronics & Programming — Level 1  
**Session:** 13 — Understanding Motors

> **Status:** Production draft derived from the established ITS Education project sequence and course framework. Exact board models, pin assignments, ratings, and lesson-specific code must be validated before classroom use.

## Purpose
Explore a motor as an actuator that produces motion.

## Learning objectives
- Identify the role of the controller and connected components.
- Assemble the hardware correctly.
- Run, observe, and modify the control behavior.
- Debug a simple hardware/software fault.
- Explain the signal flow.

## Required concepts
Actuator; rotation; mechanical output; power considerations.

## Components and materials
DC motor; suitable driver/power arrangement; breadboard or connection system; mechanical load.

## Tools
- Computer and approved programming environment
- USB cable
- Breadboard and jumper wires
- Multimeter where useful

## Safety
Do not drive motors directly from unsuitable controller pins; use the approved driver/power arrangement.

## System architecture
**Input (if applicable) → microcontroller program → output/actuator → power/return path**

Students should sketch both hardware and program logic.

## Build procedure
1. Identify board, components, inputs, and outputs.
2. Build and inspect the circuit.
3. Connect the controller safely.
4. Load the lesson program.
5. Test one function.
6. Modify one variable or program element.
7. Debug and retest.

**Project-specific focus:** Run motor safely; observe direction and load behavior; compare unloaded/loaded operation where appropriate.

## Testing
Run at least one baseline test and one student modification. Record expected versus observed behavior.

## Debugging
Use the ITS cycle:
**Observe → Describe → Hypothesize → Test → Identify → Correct → Test again**

Separate hardware checks from program checks.

## Improvement
Change program behavior, organization, interface, or presentation while preserving the core function.

## Student explanation
The student should identify inputs, outputs, controller role, important code behavior, one fault, and the debugging method.

## Teacher guide
Do not solve wiring or code errors immediately. Ask students to inspect, predict, and test.

## Assessment
Assess Programming, Electronics, Engineering, Debugging, and Communication as applicable.

## Required evidence
- Hardware sketch
- Program or annotated code
- Test result
- Debugging note
- Demonstration
- Reflection

## Success criteria
Motor operates safely and student explains electrical-to-mechanical output.

## Quality check
- [ ] Program runs as intended.
- [ ] Hardware is correctly connected.
- [ ] Student can explain input/output/control.
- [ ] Student modified or tested the program.
- [ ] Student documented debugging.
- [ ] Safety requirements were followed.
