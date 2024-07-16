# Custom ISA Assembler and Simulator

This project aims to facilitate the assembly and simulation of programs written for a custom Instruction Set Architecture (ISA) with `matplotlib` visualizations to analyze the processor's registers and memory states.

#### Custom ISA Assembler 

The assembler's role is to translate assembly language code, written for the custom ISA, into machine code that the simulator can execute. It ensures the assembly code adheres to the syntax and semantics of the custom ISA.


#### Custom ISA Simulator 

The simulator executes the machine code generated by the assembler, mimicking the behavior of a processor designed for the custom ISA. It offers a virtual environment to test and debug programs before deployment on actual hardware.

## Getting Started
1. Install Matplotlib by running the following:
    
    ```bash
    pip install matplotlib
    ```
2. Write your program in the assembly language defined by the custom ISA.
3. Use `Project_Assembler.py` to assemble your program, converting it into machine code.
4. Run `SimpleSimulator.py` with the generated machine code to simulate the execution of your program.
5. Analyze the output, including the final state of the processor's registers and memory with visualizations provided from `matplotlib`.
