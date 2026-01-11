Stack-Based Multi-Pass Frequency Analyzer (CPU SIM)
📌 Overview

This project is a Computer Architecture Lab implementation of a stack-based frequency analyzer developed and executed using CPU SIM.

Unlike traditional programs that use arrays or hash tables, this system computes frequencies entirely using stack operations (PUSH and POP) in a custom assembly-like instruction set. The project also includes instruction-level and microinstruction-level support for stack memory behavior.

⚙️ Features

Runs on CPU SIM (custom CPU simulator)

Uses stack as the primary data structure

No arrays or direct indexing used

Multi-stage processing:

Input reading

Stack-based storage

Frequency computation by popping values

Custom machine instructions:

PUSH

POP

CALL

RETURN

Demonstrates:

Stack memory access

Instruction execution flow

Microinstruction sequencing

🧠 How It Works

Reads N input values

Pushes all values onto a data stack (reversing order)

Pops values one by one

Compares consecutive values to detect duplicates

Prints each number with its frequency

The current implementation correctly counts frequencies when identical values appear consecutively in stack pop order.
The project report also proposes a multi-pass stack-only extension for handling arbitrary input order and frequency sorting.

🛠️ Requirements

CPU SIM simulator installed

Basic understanding of:

Assembly language

Stack operations

Computer architecture concepts

▶️ How to Run

Open CPU SIM

Load the provided CPU configuration / instruction set

Load the assembly program file

Assemble the code

Run the program

Enter:

First: number of inputs N

Then: N integer values

View output frequencies in the console

📂 Project Structure
/
├── assembly_code.asm
├── cpu_instruction_set.txt
├── microinstructions.txt
├── screenshots/
├── CA LAB Final project report.pdf
└── README.md


(adjust filenames based on your actual repo)

🎓 Academic Context

Course: Computer Architecture Lab

Institution: Bahria University, Islamabad

Language: Custom Assembly (CPU SIM)

Data Structure: Stack

👨‍💻 Authors

Muhammad Qasim Azhar

Noman Khan

🚀 Future Improvements

Implement second stack for (value, frequency) pairs

Handle arbitrary input order

Add stack-based frequency sorting (ascending/descending)

Optimize multi-pass stack algorithm
