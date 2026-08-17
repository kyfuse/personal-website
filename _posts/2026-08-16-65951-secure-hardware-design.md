---
title: '6.5951: Secure Hardware Design'
---

This class was really cool. We got to hack real hardware! And do a bunch of mini-CTFs! And bash our head against the wall trying to get Spectre to work. :D

Research-oriented course on secure hardware design. Understand the critical security problems in modern hardware and common limitations of existing security solutions. Through a mix of lectures and paper discussions, learn the principles of various attacks and how to design effective hardware mitigations and hardware/software co-design solutions.
## Table of Contents
- **Lecture 1**: Intro, 6.191 Review  
- **Lecture 2**: Side Channels, Demo  
- **Recitation 1**: C Crash Course, CTF  
- **Lab 0**: Types of Bugs

- **Lab 1**: Website Fingerprinting, Side Channels with JavaScript  

- **Recitation 2**: Cache Details, Virtual Memory Review  
- **Lecture 3**: Cache Side Channels, Flush/Evict+Reload, Prime+Probe  
- **Lecture 4**: Out of Order Execution, Exception Handling, Meltdown, Spectre  
- **Lecture 5**: Attack Mitigations: Non-Interference, Constant-Time Programming  
- **Lecture 6**: Spectre Mitigations: Software, Spectre Mitigations: Hardware, Spectre Visualization  
- **Lab 2**: Flush + Reload, Prime + Probe, Chat Client  

- **Lecture 7**: Physical Attacks Intro, Physical Fault Injections, Physical Side Channels  
- **Recitation 3**: Power Trace Collection, Hamming Weight Leakage Model, CPA (Correlation Power Analysis)
- **Lab 3**: Lab Infrastructure, Flush + Reload, Basic Spectre, Advanced Spectre  

- **Lecture 8**: RowHammer, RowHammer in Practice, RowHammer in the Wild  
- **Lecture 9**: Physical Attack Mitigations, Fault Injection: Software Mitigations, RowHammer: Hardware Mitigations  
- **Lecture 10**: Trusted Hash Verification, Root of Trust  
- **Lab 4**: DRAM Geometry - Finding Bank Conflicts, Bank XOR-Function, Rowhammer, Mitigation Using Error Correcting Codes (ECCs)  

- **Lecture 11**: Software Bugs, Hardware Supported Mitigations  
- **Lab 5**: Breaking ASLR (Address Space Layout Randomization), ROP (Return Oriented Programming)

- **Lecture 12**: Hardware Errata, Specification Bugs, Fuzzing  
- **Recitation 4**: RISC-V ISA, Calling Convention, GDB, CSRs (Control and Status Registers), ROP Gadgets  
- **Shell Scripting**: Variables and Exporting, Wildcards and Quoting, Loops, Tests and Conditionals, Positional and Special Parameters, Functions and Libraries, sed and awk 
- **Lab 6**: Pretty Secure Processor (PSP), Fuzzing for Faulty Inputs and a Backdoor

- **Lecture 13**: Verification Intro, SAT Solvers, Formal Verification  
- **Recitation 5**: Verilog, Formal Verification, AIGER (And-Inverter Graph), Model Checking Practice  
- **Lecture 14**: The Trust Bootstrapping Problem, Intel Software Guard Extensions (SGX)  
- **Lab 7**: Find the Adder Bug, Find the Backdoor Instruction
