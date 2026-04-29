# Guichengbin

Graduate student in Integrated Circuit Engineering at East China Normal University. I work around compiler performance, game/workload benchmarking, embedded systems, and AI-assisted engineering workflows.

I like projects where the result can be measured: a faster frame-time trace, a reproducible benchmark run, a cleaner profiling pipeline, or a hardware prototype that actually moves.

## What I Am Working On

- Compiler and runtime performance analysis
- Game and benchmark profiling on real workloads
- AI-assisted tools for engineering diagnosis and report generation
- Embedded systems, visual tracking, and hardware-software prototypes

## Experience

### Intel, Compiler and AI Engineer Intern

Worked on SPEC CPU2017 performance analysis, profiling automation, and game compatibility validation.

- Analyzed SPEC CPU2017 benchmark behavior across configs, threads/copies, and affinity settings.
- Integrated VTune, perf, and PinTool into a profpin-based workflow for collecting IPC, RSS, bandwidth, memory access, and opcode-mix metrics.
- Produced reusable scripts and process documentation, with related work reused for SPEC CPU2026 research.
- Validated Intel APO-related game scenarios, collected logs, organized defects, and supported reproduction/regression checks.

## Selected Projects

### Unity BossRoom Compiler Replacement and GameAssembly.dll Benchmarking

Rebuilt Unity's BossRoom demo workflow to compare MSVC and Intel compiler outputs in a real game-like workload.

- Pulled and studied the Unity BossRoom sample, then broke down its build/runtime structure around IL2CPP and native binary generation.
- Replaced the MSVC compiler path with the Intel compiler for the native build stage.
- Swapped the final `GameAssembly.dll` and used CapFrameX to compare runtime performance.
- Observed a small but measurable performance gain, using frame-time/FPS data rather than subjective gameplay impressions.

### SPEC CPU2017 Profiling Workflow

Built a reusable profiling process around SPEC CPU2017 during my Intel internship.

- Compared benchmark behavior under different configs, thread/copy counts, and affinity settings.
- Automated metric collection with VTune, perf, and PinTool.
- Turned profiling results into reproducible analysis notes and scripts for future benchmark work.

### Moving Target Control and Auto-Tracking System

Led an OpenMV + gimbal tracking system for an electronic design competition.

- Built the image recognition and control pipeline, including color/shape/edge detection, MCU communication, and target tracking logic.
- Achieved 95% line-following accuracy and completed target tracking within 1 second after recognition.
- Won National Second Prize in the National Undergraduate Electronics Design Contest and Shanghai First Prize in the TI Cup.

## Technical Stack

- Languages: C, Python
- Performance: VTune, perf, PinTool, SPEC CPU2017, CapFrameX
- Game/runtime: Unity, IL2CPP, `GameAssembly.dll`, MSVC, Intel compiler
- Embedded: STM32, ARM, FPGA, OpenMV
- Tools: Linux, MATLAB, Multisim, Proteus

## Education

- M.Eng. in Integrated Circuit Engineering, East China Normal University
- B.Eng. in Electronic Information Engineering, Shanghai Normal University

## Contact

- Email: Lyoaser@gmail.com
