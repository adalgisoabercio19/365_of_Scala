### fromthegates: from compilers to embedded

> Inspired by [From the Transistor](https://github.com/geohot/fromthetransistor)
>
> a lot of tutorials are hard to follow, and it's hard to understand [software 2.0](https://karpathy.medium.com/software-2-0-a64152b37c35) from first principles

### 10000 hours Syllabus

| Discipline                           | Description                                                        | Suggested Learning Stack                         | Practical Tools/Libraries                        | Hours  |
|--------------------------------------|--------------------------------------------------------------------|--------------------------------------------------|-------------------------------------------------|--------|
| Digital Logic Design                 | Basic building blocks of computer hardware                         | Logic Gates, Boolean Algebra, Karnaugh Maps      | Logisim, Digital Works, CircuitSim              | 200    |
| Embedded Systems                     | Basics of embedded system design                                    | Microcontrollers, Real-time Operating Systems    | Arduino, Raspberry Pi, FreeRTOS                 | 200    |
| Processor Design                     | Design and implementation of the CPU                                | ALU, Control Units, Pipelining                   | Verilog, VHDL, ModelSim, Synopsys               | 200    |
| Memory Hierarchy                     | Organization and management of memory                               | Cache, RAM, Virtual Memory                       | Cachegrind, DRAMSim, Gem5                       | 200    |
| Instruction Set Architecture (ISA)   | Interface between software and hardware                             | RISC, CISC, ARM, x86                             | QEMU, Simplescalar, ARM DS-5                    | 200    |
| Lexical Analysis                     | Converts source code into tokens                                    | Regular Expressions, Lexers, Flex                | Flex, ANTLR                                     | 300    |
| Syntax Analysis                      | Constructs syntax trees from tokens                                 | Context-Free Grammars, Parsers, Yacc/Bison       | Yacc, Bison, ANTLR                              | 300    |
| Semantic Analysis                    | Ensures syntactic structures have valid meaning                     | Symbol Tables, Type Checking                     | LLVM, Clang                                     | 300    |
| Intermediate Code Generation         | Translates syntax tree to intermediate code                         | Three-Address Code, Intermediate Representations | LLVM, Clang                                     | 300    |
| Optimization                         | Improves intermediate code for performance                          | Control Flow Analysis, Data Flow Analysis        | LLVM Optimizations, GCC                         | 300    |
| Code Generation                      | Converts intermediate code to machine code                          | Assembly Language, Target Machine Architectures  | LLVM, GCC, Clang                                | 300    |
| Code Optimization                    | Enhances generated machine code                                     | Loop Optimization, Inlining, Vectorization       | LLVM, GCC Optimizations                         | 300    |
| Runtime Environment                  | Manages code execution at runtime                                   | Memory Management, Garbage Collection            | JVM (Java), .NET CLR                            | 300    |
| Error Handling and Reporting         | Detects and reports errors in source code                           | Error Recovery, Debugging                        | GDB, Valgrind                                   | 300    |
| Compiler Tools                       | Software and libraries aiding in compiler construction              | LLVM, GCC, Clang                                 | LLVM, GCC, Clang, ANTLR                         | 300    |
| Parallel Processing                  | Techniques to increase processing speed                             | SIMD, MIMD, Multithreading                       | OpenMP, MPI, CUDA, OpenCL                       | 500    |
| Input/Output Systems                 | Management of data input and output                                 | I/O Devices, Buses, DMA                          | SystemVerilog, UVM, Synopsys Design Compiler    | 500    |
| Microarchitecture                    | Detailed design of processor components                             | Superscalar, Out-of-Order Execution              | Gem5, Simics, RTL simulation tools              | 500    |
| Performance Evaluation               | Measuring and improving system performance                          | Benchmarks, Profiling, Amdahl's Law              | SPEC CPU, Perf, Valgrind                        | 500    |
| Power Efficiency                     | Reducing power consumption of computer systems                      | Dynamic Voltage Scaling, Low-Power Design        | Cadence Voltus, Synopsys PrimeTime              | 500    |
| Emerging Technologies                | New advancements in computer architecture                           | Quantum Computing, Neuromorphic Computing        | IBM Qiskit, Intel Loihi, BrainScaleS            | 500    |
| Embedded System Design               | Design and implementation of embedded systems                       | Sensors, Actuators, Communication Protocols      | Arduino, Raspberry Pi, FreeRTOS                 | 1,000  |
| Compiler Implementation              | Building a compiler from scratch                                    | Full Compiler Design, Testing, Optimization      | LLVM, GCC, Clang                                | 1,000  |
| Real-Time Systems                    | Designing systems that respond to events within strict timing constraints | Real-Time Operating Systems (RTOS), Scheduling   | FreeRTOS, VxWorks, QNX                          | 500    |
| Embedded Linux                       | Using Linux in embedded systems                                     | Kernel Development, Device Drivers               | Yocto, Buildroot, U-Boot                        | 500    |
| Security in Embedded Systems         | Ensuring security in embedded hardware and software                 | Encryption, Secure Boot, Trusted Execution Environment | OpenSSL, TPM, ARM TrustZone                  | 500    |
| Wireless Communication               | Implementing wireless communication protocols                      | Bluetooth, Wi-Fi, Zigbee, LoRa                   | RF modules, Software-Defined Radio (SDR)        | 500    |
| Advanced Microcontrollers            | Working with advanced microcontrollers                              | ARM Cortex, PIC, AVR                             | ARM Keil, MPLAB, Atmel Studio                   | 500    |
| FPGA Design                          | Designing with Field-Programmable Gate Arrays                       | FPGA Architecture, HDL                           | Xilinx Vivado, Altera Quartus                   | 500    |
| Hardware Testing and Debugging       | Techniques for testing and debugging hardware                       | JTAG, Logic Analyzers, Oscilloscopes             | OpenOCD, Saleae Logic, Tektronix Oscilloscope   | 500    |
| Advanced Power Management            | Techniques for managing power consumption in embedded systems       | Dynamic Power Management, Low Power Modes        | PowerPlay, Power Analyzer Tools                 | 500    |