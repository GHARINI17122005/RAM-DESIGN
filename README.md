# RAM-DESIGN

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: HARINI G

*INTERN ID*: CT04DR2924

*DOMAIN*: VLSI

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*:

I worked on the design and simulation of a simple synchronous RAM module that supports both read and write operations, using Verilog HDL and an industry-standard Electronic Design Automation (EDA) tool. The objective of this task was to understand the internal working of memory blocks, synchronous data transfer, and clock-driven digital systems while also developing the ability to verify hardware functionality through simulation. The RAM module I designed was organized as an array of memory locations that stored data synchronously on the rising edge of the clock. It featured essential signals such as a clock input, write enable (WE), read enable (RE), a memory address, data input, and data output. In a synchronous RAM, both read and write operations depend entirely on the clock edge, making it predictable, stable, and suitable for high-speed digital systems. When the write enable signal is high, the data present on the input line is written to the addressed memory location at the rising clock edge, ensuring that no unwanted writes occur during glitches or unstable periods. Similarly, the read enable signal triggers the RAM to place the stored data onto the output bus on the next rising clock edge, ensuring that the output remains stable and aligned with the system timing. This behaviour demonstrates how synchronous memory ensures data consistency and prevents asynchronous hazards, which is crucial when RAM is used as part of a larger processor or digital circuit. After coding the RAM module, I developed a detailed Verilog testbench to validate its functionality. The testbench generated a clock signal, applied several write cycles with different addresses and data patterns, and then performed corresponding read cycles to verify whether the data was stored and retrieved accurately. It also checked if the RAM maintained previous values when write enable was inactive, and ensured the output bus displayed valid data only during read cycles. After completing both module and testbench coding, I moved on to the simulation phase using the EDA tool provided during my internship. The EDA environment played a crucial role in compiling the Verilog files, checking syntax, and executing the simulation efficiently. One of the most valuable aspects of the tool was its waveform viewer, which allowed me to closely observe clock transitions, address changes, data writes, and output responses. I imported all the Verilog files, compiled the RAM module and the testbench without errors, and then launched the simulation. In the waveform window, I monitored how the write enable signal controlled the storing of data into memory and verified that data appeared at the correct address on the rising clock edge. During read cycles, I confirmed that the stored values appeared on the output bus only after the correct clock transition, thereby validating synchronous behaviour. The EDA tool also allowed me to zoom into timing intervals, trace specific memory addresses, and analyse waveforms in detail, which helped me fully verify each operation. I captured simulation screenshots and documented the entire read-write process in my report. Overall, this internship project significantly enhanced my understanding of synchronous memory design, timing control, and hardware verification workflows. I am grateful to Codtech for providing me with this excellent opportunity to explore RAM design, improve my technical capabilities, and gain real-world experience in digital system development and simulation.

*OUTPUT*:

![Image](https://github.com/user-attachments/assets/eb8b0221-8b58-4225-aa44-ae76e3a16734)
