# Dev-Trace for the CPUlator ARMv7 DE1-SoC-System

**An ongoing journey of learning, experimenting, and understanding C through CPUlator.**

## About the Project

Dev-Trace is a structured record of my progress in learning C and deepening my understanding of low-level programming using the CPUlator ARMv7 DE1-SoC System simulator.

The project documents my experiments, the problems I encounter, the solutions I develop, and the insights I gain along the way. Rather than simply collecting finished code, I want to preserve the thought process behind it: how I approach a problem, explore possible solutions, and learn from the results.

The project is also intended to inspire others interested in C programming, computer systems, and interacting with hardware through CPUlator.

## Project Structure & Learning Path

The project is divided into six groups, each focusing on a particular set of I/O devices or use cases. The groups are numbered to reflect the intended progression in complexity. As the project advances, later groups may build upon concepts, techniques, and solutions explored in earlier ones.

| No. | Group | Focus |
|---:|---|---|
| 01 | [Management]([REPOSITORY_URL](https://github.com/CPUlator-ARMv7-DE1-SoC-System/Management.git)) | Exploring ways to coordinate and schedule multiple devices, including controlling which devices can operate simultaneously and which must operate exclusively. |
| 02 | [Displays]([REPOSITORY_URL](https://github.com/CPUlator-ARMv7-DE1-SoC-System/Displays.git)) | Working with the VGA pixel buffer, LEDs, and seven-segment displays to explore visual output and display control. |
| 03 | [Timer]([REPOSITORY_URL](https://github.com/CPUlator-ARMv7-DE1-SoC-System/Timer.git)) | Exploring timer devices, timing mechanisms, and time-dependent program behavior. |
| 04 | [Carworld_UART]([REPOSITORY_URL](https://github.com/CPUlator-ARMv7-DE1-SoC-System/Timer.git)) | Experiments involving Carworld and UART-based communication. |
| 05 | [Audio]([REPOSITORY_URL](https://github.com/CPUlator-ARMv7-DE1-SoC-System/Timer.git)) | Exploring audio devices, sound output, and audio-related programming concepts. |
| 06 | [Console]([REPOSITORY_URL](https://github.com/CPUlator-ARMv7-DE1-SoC-System/Timer.git)) | Developing a simple console that combines keyboard and mouse input with the JTAG UART. |

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
