# Experiment 3 - GDB Debugging and Data Structure Analysis

---

# Objective

This lab focuses on compiling and debugging programs using the GNU Debugger (GDB). It helps in understanding the core concepts of Computer Architecture, memory addressing, and execution flow.

The experiment covers:

- Basic GDB commands
- Compiling C programs using GDB
- Debugging Stack, Queue, and Linked List programs
- Understanding memory and variable tracking during execution

---

# Background Study

The GNU Debugger (GDB) is a powerful debugging tool used for programs written in languages like C and C++.

GDB allows programmers to:

- Execute programs line-by-line
- Set breakpoints during execution
- Inspect variable values and memory
- Trace function calls and program flow
- Analyze runtime behavior of programs

To enable debugging, programs must be compiled using the `-g` flag.

---

# Key Concepts

## Breakpoint

A breakpoint is a point where program execution pauses for inspection.

### Example

```bash
break main
