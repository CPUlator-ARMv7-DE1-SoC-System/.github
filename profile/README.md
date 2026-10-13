![Organization banner](assets/armv7-dev-trace-banner.svg)

# Dev-Trace for the CPUlator ARMv7 DE1-SoC-System

**An ongoing journey of learning, experimenting, and understanding C through CPUlator.**

## About the Project

Dev-Trace is a structured record of my progress in learning C and deepening my understanding of low-level programming using the CPUlator ARMv7 DE1-SoC System simulator.

The project documents my experiments, the problems I encounter, the solutions I develop, and the insights I gain along the way. Rather than simply collecting finished code, I want to preserve the thought process on how I approach a problem, explore possible solutions, and learn from the results.

The project is also intended to inspire others interested in C programming, computer systems, and interacting with hardware through CPUlator.

## Why CPUlator?

CPUlator provides an accessible environment for exploring C programming and low-level computer systems without the need to set up a complete development toolchain locally.

Some of its key advantages are:

- **Hardware-oriented learning:** CPUlator simulates a processor and its associated peripherals, allowing experiments with memory-mapped I/O, registers, interrupts, and hardware interaction in a controlled environment.
- **No local toolchain required:** The simulator runs in a web browser, so there is no need to download and configure a separate IDE, compiler, or hardware simulator to get started.
- **Immediate experimentation:** Code can be written, executed, and debugged directly in the browser, making it easy to test ideas, investigate unexpected behavior, and refine solutions.
- **Visual feedback:** Simulated devices such as LEDs, switches, buttons, seven-segment displays, and the VGA pixel buffer make the connection between code and hardware behavior easier to observe.
- **A safe learning environment:** Experiments can be performed without requiring a physical DE1-SoC board, making it easier to explore unfamiliar concepts and recover from mistakes.

CPUlator therefore serves as a practical bridge between learning C as a programming language and understanding how software interacts with a processor and its peripherals.

Although simulation cannot capture every detail or limitation of physical hardware, it provides a convenient starting point for developing the concepts and problem-solving skills needed for low-level programming.

## Project Structure & Learning Path

The project is divided into six groups, each focusing on a particular set of I/O devices or use cases. The groups are numbered to reflect the intended progression in complexity. As the project advances, later groups may build upon concepts, techniques, and solutions explored in earlier ones.

| No. | Group | Focus |
|---:|---|---|
| 01 | [Management](https://github.com/CPUlator-ARMv7-DE1-SoC-System/Management.git) | Working with the LEDs and seven-segment displays and exploring ways to coordinate and schedule multiple devices, including controlling which devices can operate simultaneously and which must operate exclusively. |
| 02 | [Displays](https://github.com/CPUlator-ARMv7-DE1-SoC-System/Displays.git) | Working with the VGA pixel buffer to explore visual output and display control. |
| 03 | [Timer](https://github.com/CPUlator-ARMv7-DE1-SoC-System/Timer.git) | Exploring timer devices, timing mechanisms, and time-dependent program behavior. |
| 04 | [Carworld_UART](https://github.com/CPUlator-ARMv7-DE1-SoC-System/Timer.git) | Experiments involving Carworld and UART-based communication. |
| 05 | [Audio](https://github.com/CPUlator-ARMv7-DE1-SoC-System/Timer.git) | Exploring audio devices, sound output, and audio-related programming concepts. |
| 06 | [Console](https://github.com/CPUlator-ARMv7-DE1-SoC-System/Timer.git) | Developing a simple console that combines keyboard and mouse input with the JTAG UART. |

*The numbering represents the intended learning progression, not necessarily a strict dependency between every group.*

## Learning Approach

The focus is not only on what works, but also on understanding why it works.

Throughout the project, I aim to document:

- **The problem:** What I want to achieve or understand.
- **The approach:** How I break down the problem and develop a solution.
- **The implementation:** How the solution is translated into C and interacts with the simulated hardware.
- **The reasoning:** Why I chose a particular approach and what alternatives I considered.
- **The lessons learned:** What the experiment taught me and what I would improve or explore next.

Where appropriate, later experiments incorporate ideas and techniques from previous groups, allowing individual concepts to evolve into more elaborate implementations.

## Project Philosophy

Dev-Trace is a work in progress and reflects my personal learning journey. Some solutions may be experimental, some may evolve over time, and others may serve as stepping stones toward a better understanding of the underlying concepts.

The goal is to build knowledge incrementally, make the learning process visible, and share useful insights with others exploring similar topics.

**Learn by experimenting. Understand by questioning. Improve by tracing the process.**

---

*This project is educational and documents my ongoing exploration of C programming and the CPUlator ARMv7 DE1-SoC System.*
