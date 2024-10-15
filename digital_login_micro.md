# Engineering License Exam Preparation: Digital Logic and Microprocessor (AExE02)

## 2.1 Digital Logic

### **Number Systems**

**Description**:  
Number systems define how numbers are represented. Common number systems include:

- **Binary (Base 2)**: Uses digits 0 and 1.
- **Decimal (Base 10)**: Uses digits 0 to 9.
- **Hexadecimal (Base 16)**: Uses digits 0-9 and A-F.
- **Octal (Base 8)**: Uses digits 0-7.

**Conversions**:

- **Binary to Decimal**: Multiply each binary digit by \(2^n\), where \(n\) is its position from the right.
- **Decimal to Binary**: Divide the number by 2, noting remainders.
  
**Probable Questions**:

- Convert 101101 (binary) to decimal.
- Convert 47 (decimal) to binary.

**Solution Example**:

- **Binary to Decimal**:  
  \(101101_2 = 1 \times 2^5 + 0 \times 2^4 + 1 \times 2^3 + 1 \times 2^2 + 0 \times 2^1 + 1 \times 2^0 = 45_{10}\)
- **Decimal to Binary**:  
  \(47_{10} = 101111_2\)

---

### **Logic Levels and Gates**  

**Description**:  
Logic gates perform basic logical functions in digital circuits. The basic gates are:

- **AND** gate: Output is high if both inputs are high.
- **OR** gate: Output is high if at least one input is high.
- **NOT** gate: Inverts the input (output is opposite of input).
- **NAND**, **NOR**, **XOR**, **XNOR** gates are derived from basic gates.

**Truth Tables**:

- **AND Gate**:  

  | A | B | A AND B |
  |---|---|---------|
  | 0 | 0 |    0    |
  | 0 | 1 |    0    |
  | 1 | 0 |    0    |
  | 1 | 1 |    1    |
  
**Probable Questions**:

- What is the output of an XOR gate when both inputs are 1?
- Draw the truth table of a NAND gate.

**Answer Example**:

- **XOR Gate**:  
  When both inputs are 1, the XOR gate outputs 0.

---

### **Boolean Algebra**  

**Description**:  
Boolean algebra simplifies logical expressions. Basic rules include:

- **A + 0 = A**
- **A + A = A**
- **A · 1 = A**
- **A · 0 = 0**
- **\( \overline{A + B} = \overline{A} \cdot \overline{B} \)** (De Morgan's Law)

**Probable Questions**:

- Simplify the Boolean expression \(A \cdot \overline{A} + B\).

**Solution**:

- \(A \cdot \overline{A} + B = 0 + B = B\)

---

### **Sum-of-Products (SOP) and Product-of-Sums (POS) Methods**  

**Description**:

- **SOP**: A logical expression is written as a sum (OR) of product (AND) terms.
- **POS**: A logical expression is written as a product (AND) of sum (OR) terms.

**Probable Questions**:

- Convert the truth table into SOP form.

---

### **Karnaugh Maps (K-map)**  

**Description**:  
Karnaugh maps are used to simplify Boolean expressions. Group 1's in the K-map to form the simplest expression.

---

## 2.2 Combinational and Arithmetic Circuits

### **Multiplexers and Demultiplexers**  

**Description**:

- **Multiplexer (MUX)**: Selects one input from multiple inputs and passes it to a single output.
- **Demultiplexer (DEMUX)**: Takes one input and directs it to one of several outputs.

**Probable Questions**:

- Design a 4-to-1 multiplexer circuit using logic gates.
  
---

### **Binary Addition and Subtraction**  

**Description**:

- **Binary Addition**: Follows the same rules as decimal addition but uses base 2.
  - Example: \(101_2 + 110_2 = 1011_2\)
- **Binary Subtraction**: Involves borrowing, similar to decimal subtraction.
  
**Probable Questions**:

- Perform binary addition of \(1011_2 + 1101_2\).

**Solution**:

- \(1011_2 + 1101_2 = 11000_2\)

---

### **Signed and Unsigned Binary Numbers**  

**Description**:

- **Unsigned** numbers represent only positive values.
- **Signed** numbers use the most significant bit (MSB) as the sign bit (0 for positive, 1 for negative).

---

## 2.3 Sequential Logic Circuits

### **Flip-Flops**  

**Description**:  
Flip-flops store binary data. Types include:

- **RS Flip-Flop**: Stores a bit based on Set and Reset inputs.
- **D Flip-Flop**: Data input is stored at the clock's edge.
- **JK Flip-Flop**: Enhanced version of RS, where inputs can toggle the output.

**Probable Questions**:

- Describe the operation of a JK Flip-Flop.

---

### **Shift Registers**  

**Description**:  
Shift registers store and shift data bits in a sequence. They are classified as:

- **Serial-In Serial-Out (SISO)**
- **Serial-In Parallel-Out (SIPO)**

**Probable Questions**:

- What is the application of a shift register in digital circuits?

---

### **Counters**  

**Description**:

- **Asynchronous Counters**: Count without synchronized clock inputs (also called ripple counters).
- **Synchronous Counters**: All flip-flops are triggered by the same clock signal.

**Probable Questions**:

- Explain the difference between synchronous and asynchronous counters.

---

## 2.4 Microprocessor

### **Internal Architecture and Features**  

**Description**:

- The microprocessor has components like ALU (Arithmetic Logic Unit), control unit, and registers.
- Examples: 8085 microprocessor.

**Probable Questions**:

- Draw the block diagram of the 8085 microprocessor.

---

### **Assembly Language Programming**  

**Description**:

- Assembly language is a low-level programming language that directly interfaces with the microprocessor's hardware.
  
---

## 2.5 Microprocessor System

### **Memory Device Classification and Hierarchy**  

**Description**:

- **Primary Memory**: Includes RAM and ROM.
- **Secondary Memory**: Hard drives, SSDs.
- **Memory Hierarchy**: From fastest (registers) to slowest (secondary storage).

---

### **Interfacing I/O and Memory**  

**Description**:

- **I/O Interface**: Mechanism through which the processor communicates with external devices.
- **Memory Interface**: Mechanism to connect RAM, ROM, and storage devices.

---

### **Programmable Peripheral Interface (PPI)**  

**Description**:  
A PPI allows a microprocessor to interface with peripheral devices, like keyboards and displays.

---

### **Direct Memory Access (DMA)**  

**Description**:  
DMA allows peripherals to directly transfer data to/from memory without the CPU.

---

## 2.6 Interrupt Operations

### **Interrupts**  

**Description**:

- **Interrupt**: A signal that halts the current execution of a program to execute an Interrupt Service Routine (ISR).
- **Interrupt Processing**: The steps taken when an interrupt is raised, which includes saving the program state, executing the ISR, and restoring the state.

---

## **Probable MCQs for Digital Logic and Microprocessor**

### **Understanding-Based MCQs**

**Q1**: In Boolean algebra, the complement of \(A + B\) is:  
A) \(A \cdot B\)  
B) \(\overline{A \cdot B}\)  
C) \(\overline{A} + \overline{B}\)  
D) \(\overline{A} \cdot \overline{B}\)  
**Answer**: D) \(\overline{A} \cdot \overline{B}\)  

---

**Q2**: The Karnaugh Map method is used to:  
A) Solve truth tables  
B) Minimize Boolean expressions  
C) Maximize truth tables  
D) Multiply Boolean expressions  
**Answer**: B) Minimize Boolean expressions  

---

### **Numerical-Based MCQs**

**Q3**: Convert the decimal number 27 to binary:  
A) \(11100_2\)  
B) \(11011_2\)  
C) \(10001_2\)  
D) \(10110_2\)  
**Answer**: B) \(11011_2\)

---

**Q4**: Perform binary addition: \(1011_2 + 1101_2\):  
A) \(11000_2\)  
B) \(10101_2\)  
C) \(10100_2\)  
D)

 \(11100_2\)  
**Answer**: A) \(11000_2\)

---

### **Skills-Based MCQs**

**Q5**: In a 4-to-1 multiplexer, how many select lines are required?  
A) 1  
B) 2  
C) 3  
D) 4  
**Answer**: B) 2  

---

**Q6**: The memory hierarchy from fastest to slowest is:  
A) Cache > Registers > RAM > Secondary Storage  
B) Registers > Cache > RAM > Secondary Storage  
C) RAM > Registers > Cache > Secondary Storage  
D) Secondary Storage > RAM > Cache > Registers  
**Answer**: B) Registers > Cache > RAM > Secondary Storage  

---
