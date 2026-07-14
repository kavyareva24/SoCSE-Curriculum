# B25CS0303 — Computer Organization and Architecture
## Unit 1: Basic Computer Organization — Formative Assessment Activities
### 5 Quizzes (10 Questions Each) + 1 Mini Project

---

## QUIZ 1: Computer Components & Functional Units
**Topics:** CPU, ALU, Control Unit, Registers, Memory types  
**Duration:** 15 minutes  
**Question Count:** 10  
**Format:** Mix of MCQ, True/False, Fill-in-the-blank  
**Difficulty Level:** Beginner (Recall/Understand)

### Questions:

**Q1. Multiple Choice**
Which of the following is the primary function of the CPU?
- A) Store data permanently
- B) Fetch, decode, and execute instructions
- C) Display output on screen
- D) Convert AC to DC power

**Answer:** B

---

**Q2. Multiple Choice**
The ALU (Arithmetic Logic Unit) is responsible for:
- A) Storing instructions
- B) Controlling program flow
- C) Performing arithmetic and logical operations
- D) Managing input/output devices

**Answer:** C

---

**Q3. True/False**
The Control Unit decodes instructions and generates control signals to direct the operation of the CPU.

**Answer:** True

---

**Q4. Fill-in-the-Blank**
The _________ stores the memory address of the next instruction to be fetched.

**Answer Key:** Program Counter (PC) / Instruction Pointer

---

**Q5. Multiple Choice**
Which of the following is a CPU register?
- A) Hard Disk
- B) Cache
- C) Accumulator (ACC)
- D) RAM

**Answer:** C

---

**Q6. True/False**
Registers are slower than RAM but faster than the CPU's control unit.

**Answer:** False (Registers are actually faster than RAM)

---

**Q7. Fill-in-the-Blank**
The _________ is the functional unit that stores intermediate results during computation.

**Answer Key:** Accumulator / Register

---

**Q8. Multiple Choice**
What is the primary purpose of the Control Unit (CU)?
- A) Perform calculations
- B) Store data
- C) Decode instructions and generate control signals
- D) Display results

**Answer:** C

---

**Q9. True/False**
In a von Neumann architecture, instructions and data are stored in the same memory.

**Answer:** True

---

**Q10. Multiple Choice**
Which functional unit fetches instructions from memory?
- A) ALU
- B) Control Unit
- C) Memory Interface Unit
- D) Registers

**Answer:** C (or B, depending on definition — accept both)

---

## QUIZ 2: Fetch-Decode-Execute Cycle
**Topics:** Instruction cycle phases, timing, PC updates  
**Duration:** 15 minutes  
**Question Count:** 10  
**Format:** Mix of MCQ, Fill-in-the-blank, Sequence ordering  
**Difficulty Level:** Beginner (Understand/Apply)

### Questions:

**Q1. Fill-in-the-Blank (Sequence)**
The three main phases of the instruction cycle are: _________, _________, and _________.

**Answer Key:** Fetch, Decode, Execute (accept in order)

---

**Q2. Multiple Choice**
During which phase of the instruction cycle is the instruction retrieved from memory?
- A) Decode phase
- B) Execute phase
- C) Fetch phase
- D) Writeback phase

**Answer:** C

---

**Q3. True/False**
In the Decode phase, the CPU executes the arithmetic or logical operation specified by the instruction.

**Answer:** False (This happens in Execute phase)

---

**Q4. Fill-in-the-Blank**
During the Fetch phase, the address of the next instruction is held in the _________.

**Answer Key:** Program Counter (PC)

---

**Q5. Multiple Choice**
What happens to the Program Counter (PC) after an instruction is fetched?
- A) It is reset to zero
- B) It is incremented to point to the next instruction
- C) It is decremented
- D) It remains the same

**Answer:** B

---

**Q6. True/False**
The Execute phase is where the CPU decodes the instruction's opcode and operands.

**Answer:** False (This is the Decode phase)

---

**Q7. Fill-in-the-Blank**
In the _________ phase, the instruction is interpreted and control signals are generated.

**Answer Key:** Decode

---

**Q8. Multiple Choice**
Which phase of the instruction cycle involves performing calculations or logical operations?
- A) Fetch
- B) Decode
- C) Execute
- D) Store

**Answer:** C

---

**Q9. True/False**
The fetch-decode-execute cycle repeats continuously until the CPU encounters a HALT instruction or is interrupted.

**Answer:** True

---

**Q10. Multiple Choice**
What is stored in the Instruction Register (IR) during the Fetch phase?
- A) The result of the previous instruction
- B) The address of the next instruction
- C) The instruction fetched from memory
- D) The current value of the accumulator

**Answer:** C

---

## QUIZ 3: Memory Organization & Storage Hierarchy
**Topics:** Memory types, capacity, access time, cache concept basics  
**Duration:** 15 minutes  
**Question Count:** 10  
**Format:** Mix of MCQ, True/False, Fill-in-the-blank  
**Difficulty Level:** Beginner (Understand/Apply)

### Questions:

**Q1. Multiple Choice**
Which of the following memory types is the fastest?
- A) RAM
- B) Cache
- C) Hard Disk
- D) USB Flash Drive

**Answer:** B

---

**Q2. True/False**
Larger capacity memory (like RAM) is generally faster than smaller capacity memory (like registers).

**Answer:** False (Smaller is faster)

---

**Q3. Fill-in-the-Blank**
The memory hierarchy follows the principle of _________, where frequently accessed data is stored in faster memory levels.

**Answer Key:** Locality (or Temporal Locality / Spatial Locality)

---

**Q4. Multiple Choice**
What is the primary advantage of using cache memory in a computer?
- A) It has the largest storage capacity
- B) It is the cheapest memory type
- C) It reduces access time by storing frequently used data
- D) It is nonvolatile

**Answer:** C

---

**Q5. True/False**
ROM (Read-Only Memory) is generally faster than RAM.

**Answer:** False (RAM is typically faster than ROM)

---

**Q6. Fill-in-the-Blank**
The _________ is the smallest and fastest type of memory in a computer, typically located on the CPU itself.

**Answer Key:** Register

---

**Q7. Multiple Choice**
Arrange the following in order of increasing access time (fastest to slowest):
- A) Disk, RAM, Cache, Registers
- B) Registers, Cache, RAM, Disk
- C) RAM, Cache, Disk, Registers
- D) Cache, Registers, RAM, Disk

**Answer:** B

---

**Q8. True/False**
Hard disk storage is considered volatile memory.

**Answer:** False (Hard disk is nonvolatile; RAM is volatile)

---

**Q9. Fill-in-the-Blank**
Data in _________ memory is lost when the computer is powered off.

**Answer Key:** Volatile / RAM

---

**Q10. Multiple Choice**
Which memory type is primarily used for long-term storage of programs and data?
- A) Cache
- B) Registers
- C) Hard Disk / SSD
- D) RAM

**Answer:** C

---

## QUIZ 4: Registers & Data Paths
**Topics:** Register types, functions, data movement, instruction fetch/storage  
**Duration:** 15 minutes  
**Question Count:** 10  
**Format:** Mix of MCQ, Fill-in-the-blank, True/False  
**Difficulty Level:** Beginner (Understand/Apply)

### Questions:

**Q1. Multiple Choice**
What is the primary purpose of the Program Counter (PC) register?
- A) Store the result of calculations
- B) Hold the address of the next instruction to be fetched
- C) Store temporary data during execution
- D) Count the number of instructions executed

**Answer:** B

---

**Q2. Fill-in-the-Blank**
The _________ register holds the instruction currently being executed by the CPU.

**Answer Key:** Instruction Register (IR)

---

**Q3. True/False**
The Accumulator (ACC) is a general-purpose register used for storing intermediate results.

**Answer:** True

---

**Q4. Multiple Choice**
Which of the following registers is incremented automatically after each instruction fetch?
- A) Instruction Register
- B) Accumulator
- C) Program Counter
- D) Memory Address Register

**Answer:** C

---

**Q5. Fill-in-the-Blank**
The _________ holds the address of the memory location being accessed.

**Answer Key:** Memory Address Register (MAR) / Address Register

---

**Q6. True/False**
The Memory Data Register (MDR) stores the data that is read from or written to memory.

**Answer:** True

---

**Q7. Multiple Choice**
How many bits is a typical data path width in a 32-bit processor?
- A) 16 bits
- B) 32 bits
- C) 64 bits
- D) 8 bits

**Answer:** B

---

**Q8. Fill-in-the-Blank**
The pathway through which data flows between the CPU, registers, ALU, and memory is called the _________.

**Answer Key:** Data Path / Data Bus (accept both)

---

**Q9. True/False**
A register can store multiple instructions simultaneously.

**Answer:** False (A register typically stores one unit of data at a time)

---

**Q10. Multiple Choice**
Which register is used to hold the operands during an ALU operation?
- A) Program Counter
- B) Instruction Register
- C) Accumulator
- D) Memory Data Register

**Answer:** C

---

## QUIZ 5: Comprehensive Unit 1 Review
**Topics:** Mixed topics — Components, Fetch-Decode-Execute, Memory, Registers, ALU  
**Duration:** 20 minutes  
**Question Count:** 10  
**Format:** Mix of MCQ, True/False, Fill-in-the-blank, Short answer  
**Difficulty Level:** Beginner (Recall/Understand/Apply)

### Questions:

**Q1. Multiple Choice**
Which functional unit is responsible for performing AND, OR, NOT, and arithmetic operations?
- A) Control Unit
- B) Arithmetic Logic Unit (ALU)
- C) Memory Unit
- D) Registers

**Answer:** B

---

**Q2. True/False**
In a single-cycle processor, each instruction is completed in one clock cycle.

**Answer:** True

---

**Q3. Fill-in-the-Blank**
The _________ coordinates and controls all other components of the CPU.

**Answer Key:** Control Unit

---

**Q4. Multiple Choice**
What is the typical sequence of events in the fetch-decode-execute cycle?
- A) Decode → Fetch → Execute
- B) Execute → Fetch → Decode
- C) Fetch → Decode → Execute
- D) Execute → Decode → Fetch

**Answer:** C

---

**Q5. Short Answer**
Name three types of registers found in a typical CPU.

**Answer Key:** (Any three of the following) Program Counter (PC), Accumulator (ACC), Instruction Register (IR), Memory Address Register (MAR), Memory Data Register (MDR), General-purpose registers

---

**Q6. True/False**
The faster the memory, the cheaper it is per unit of storage.

**Answer:** True

---

**Q7. Fill-in-the-Blank**
The _________ is the main memory of a computer and is directly accessible by the CPU.

**Answer Key:** RAM (Random Access Memory)

---

**Q8. Multiple Choice**
Which of the following best describes the role of the CPU in a computer?
- A) Permanent storage of data
- B) Display of information
- C) Fetching, decoding, and executing instructions
- D) Communication with external devices only

**Answer:** C

---

**Q9. True/False**
The Instruction Register (IR) contains the address of the data to be processed.

**Answer:** False (The MAR contains the address; the IR contains the instruction itself)

---

**Q10. Fill-in-the-Blank**
The principle that faster memory levels are smaller and more expensive per unit is called the _________ _________.

**Answer Key:** Memory Hierarchy / Storage Hierarchy

---

---

## MINI PROJECT 1: Circuit Logic Design with Logisim
### "Build a Simple 2-Bit Adder Circuit"

**Inspired by:** Nand2Tetris Project 2 (Boolean Arithmetic)

**Objective:** Students understand how basic logic gates combine to create functional circuits (ALU building blocks).

**Duration:** 1–2 hours (can be extended)

**Level:** Beginner (Hands-on application)

**Tools Required:** 
- Logisim (free, open-source circuit simulator)
- Installation link: https://sourceforge.net/projects/circuit/

---

### Project Description:

In this mini-project, you will **design and simulate a simple 2-bit adder circuit** using logic gates. This project builds intuition for how the ALU (Arithmetic Logic Unit) works at the gate level.

---

### Part A: Understanding the Task (Awareness Level)

**Background:**
- A **half-adder** is a basic circuit that adds two single bits and produces a sum and carry output.
- A **full-adder** extends this by accepting a carry-in from a previous operation.
- A **2-bit adder** chains two full-adders to add two 2-bit numbers.

**Example:**
```
Input A = 10 (binary) = 2 (decimal)
Input B = 01 (binary) = 1 (decimal)
Output = 11 (binary) = 3 (decimal)
```

---

### Part B: Circuit Design Requirements

**Step 1: Build a Half-Adder**
- Inputs: A (1 bit), B (1 bit)
- Outputs: Sum (1 bit), Carry (1 bit)
- Logic:
  - Sum = A XOR B
  - Carry = A AND B

**Deliverable:** Screenshot of half-adder circuit in Logisim

---

**Step 2: Build a Full-Adder**
- Inputs: A (1 bit), B (1 bit), Carry-in (1 bit)
- Outputs: Sum (1 bit), Carry-out (1 bit)
- Logic: Combine two half-adders and an OR gate

**Deliverable:** Screenshot of full-adder circuit in Logisim

---

**Step 3: Build a 2-Bit Adder**
- Chain two full-adders together
- Inputs: A[1:0] (2 bits), B[1:0] (2 bits)
- Output: Sum[2:0] (3 bits — includes final carry)

**Deliverable:** Screenshot of 2-bit adder circuit; test output

---

### Part C: Simulation & Testing

**Test Cases:** Test your 2-bit adder with at least 5 test cases:

| Input A | Input B | Expected Output | Actual Output | Pass/Fail |
|---------|---------|-----------------|---------------|-----------|
| 00 | 00 | 000 | | |
| 01 | 01 | 010 | | |
| 10 | 01 | 011 | | |
| 11 | 11 | 110 | | |
| 10 | 10 | 100 | | |

---

### Part D: Reflection & Submission

**Written Reflection (1 paragraph):**
- How many gates did you use in total?
- What was the most complex part of building the circuit?
- How does this relate to the ALU in a real CPU?

**Submission Checklist:**
- ✅ Logisim circuit file (.circ) with clearly labeled components
- ✅ Screenshots of each stage (half-adder, full-adder, 2-bit adder)
- ✅ Test results table completed
- ✅ Written reflection (4–5 sentences)

---

### Grading Rubric:

| Criterion | Points | Rubric |
|-----------|--------|--------|
| **Circuit Correctness** | 30 | Half-adder works (10) + Full-adder works (10) + 2-bit adder works (10) |
| **Test Cases** | 20 | All 5 test cases documented and correct |
| **Documentation** | 20 | Clear labels, well-organized circuit, readable screenshots |
| **Reflection** | 15 | Thoughtful response connecting to course concepts |
| **Submission Quality** | 15 | File properly named, all required files included |
| **TOTAL** | **100** | |

---

### Learning Outcomes Addressed:

✅ **CO1:** Explain computer architecture fundamentals — students see how gates combine into functional units  
✅ **CO2:** Understand CPU organization at a deeper level — ALU is made of logic circuits  
✅ **Apply:** Students apply Boolean logic concepts to build a working circuit  

---

### Beginner Tips:

1. **Start simple:** Build and test the half-adder first before moving to full-adder.
2. **Use Logisim tutorials:** Familiarize yourself with the interface (drag gates, create wiring, test circuits).
3. **Label your inputs/outputs:** Makes the circuit easier to read and debug.
4. **Test incrementally:** After each component, verify it works before moving to the next.

---

### Extension (For Advanced Students):

- Build a 4-bit adder by chaining two 2-bit adders
- Design a subtraction circuit (using 2's complement)
- Implement an ALU that can perform ADD and AND operations

---

---

## Summary of Formative Assessment Activities

| Activity | Type | Duration | Questions | Difficulty | Format |
|----------|------|----------|-----------|------------|--------|
| Quiz 1 | Formative | 15 min | 10 | Beginner | MCQ + T/F + Fill-blank |
| Quiz 2 | Formative | 15 min | 10 | Beginner | MCQ + T/F + Sequence |
| Quiz 3 | Formative | 15 min | 10 | Beginner | MCQ + T/F + Fill-blank |
| Quiz 4 | Formative | 15 min | 10 | Beginner | MCQ + T/F + Fill-blank |
| Quiz 5 | Formative | 20 min | 10 | Beginner | Mixed (review) |
| Mini-Project 1 | Hands-on | 1–2 hrs | Design task | Beginner→Apply | Logisim circuit + reflection |

**Total Assessment Load:** ~90 minutes quizzes + 2 hours project = ~3.5 hours engagement

**Deployment:** 
- Quizzes 1–5: Google Classroom (auto-gradeable MCQ + T/F, manual review for fill-blanks/short answer)
- Mini-Project 1: Google Classroom assignment (submit .circ file + screenshots + reflection PDF)

---

## Answer Key Summary

| Quiz | Q1 | Q2 | Q3 | Q4 | Q5 | Q6 | Q7 | Q8 | Q9 | Q10 |
|------|----|----|----|----|----|----|----|----|----|----|
| **Quiz 1** | B | C | T | PC | C | F | Acc | C | T | C |
| **Quiz 2** | Fetch/Decode/Execute | C | F | PC | B | F | Decode | C | T | C |
| **Quiz 3** | B | F | Locality | C | F | Register | B | F | Volatile | C |
| **Quiz 4** | B | IR | T | C | MAR | T | B | Data Path | F | C |
| **Quiz 5** | B | T | Control Unit | C | (Any 3 registers) | T | RAM | C | F | Memory Hierarchy |

---

**End of Activities Document**

All activities are beginner-friendly (3rd semester level), formative-focused, and ready for Google Classroom deployment.
