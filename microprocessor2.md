# Engineering License Exam Preparation: Digital Logic and Microprocessor (AExE02)

## **Additional Topics on Pins, Bits, and Sizes**

---

### **Microprocessor Pin Configuration and Sizes**

#### **8085 Microprocessor Pin Description**

The 8085 microprocessor is an 8-bit microprocessor with a 16-bit address bus and a 64KB memory capacity. It has 40 pins, and the key pins include:

- **Address Bus (A0 - A15)**: 16 pins for addressing memory.
- **Data Bus (D0 - D7)**: 8 pins for data transfer.
- **Control and Status Signals**:
  - **ALE (Address Latch Enable)**: Latches the lower address byte.
  - **RD**: Read control signal.
  - **WR**: Write control signal.
  - **INT (Interrupt)**: Interrupt request signal.
  - **RESET IN**: Resets the microprocessor.

#### **Probable Questions**

1. **Q1**: How many address lines are there in the 8085 microprocessor?  
   A) 8  
   B) 12  
   C) 16  
   D) 20  
   **Answer**: C) 16

2. **Q2**: How many data lines are available in the 8085 microprocessor?  
   A) 4  
   B) 8  
   C) 16  
   D) 32  
   **Answer**: B) 8

3. **Q3**: What is the purpose of the ALE (Address Latch Enable) signal in the 8085 microprocessor?  
   A) To control the data transfer.  
   B) To latch the address on the lower address bus.  
   C) To manage the interrupts.  
   D) To reset the processor.  
   **Answer**: B) To latch the address on the lower address bus.

4. **Q4**: What is the memory size that can be addressed by a 16-bit address bus?  
   A) 16KB  
   B) 32KB  
   C) 64KB  
   D) 128KB  
   **Answer**: C) 64KB  
   **Explanation**: A 16-bit address bus can address \(2^{16} = 65,536\) locations, which is equivalent to 64KB.

---

### **Bitwise Operations and Sizes in Digital Circuits**

#### **Bitwise Operations**  

In microprocessors and digital circuits, bitwise operations are performed on individual bits:

- **AND**: Performs logical AND between corresponding bits.
- **OR**: Performs logical OR between corresponding bits.
- **XOR**: Performs exclusive OR between corresponding bits.
- **NOT**: Inverts the bits.

#### **Probable Questions**

5. **Q5**: What is the result of the bitwise AND operation between \(1011_2\) and \(1101_2\)?  
   A) \(1010_2\)  
   B) \(1001_2\)  
   C) \(1111_2\)  
   D) \(1100_2\)  
   **Answer**: B) \(1001_2\)

6. **Q6**: Perform the bitwise OR operation between \(0110_2\) and \(1010_2\).  
   A) \(0010_2\)  
   B) \(1110_2\)  
   C) \(1011_2\)  
   D) \(0111_2\)  
   **Answer**: B) \(1110_2\)

7. **Q7**: What is the result of the XOR operation between \(1110_2\) and \(1011_2\)?  
   A) \(0101_2\)  
   B) \(0110_2\)  
   C) \(1000_2\)  
   D) \(0001_2\)  
   **Answer**: A) \(0101_2\)

---

### **Registers, Bit Size, and Instruction Sets**

#### **Registers in 8085 Microprocessor**  

Registers are small storage units within the CPU:

- **8-bit Registers**: Accumulator (A), B, C, D, E, H, L.
- **16-bit Registers**: Stack Pointer (SP), Program Counter (PC).
- **Instruction Set Size**: 8085 microprocessor has a mix of 1-byte, 2-byte, and 3-byte instructions.

#### **Probable Questions**

8. **Q8**: How many bits are used to store data in the accumulator register of the 8085 microprocessor?  
   A) 4 bits  
   B) 8 bits  
   C) 16 bits  
   D) 32 bits  
   **Answer**: B) 8 bits

9. **Q9**: The size of the Program Counter in the 8085 microprocessor is:  
   A) 4 bits  
   B) 8 bits  
   C) 16 bits  
   D) 32 bits  
   **Answer**: C) 16 bits

10. **Q10**: What is the size of the instruction register in the 8085 microprocessor?  
   A) 4 bits  
   B) 8 bits  
   C) 16 bits  
   D) 32 bits  
   **Answer**: B) 8 bits

---

### **Memory Sizes and Hierarchy in Microprocessor Systems**

#### **Memory Devices and Sizes**

- **RAM** (Random Access Memory): Temporary memory, used for data that needs to be accessed quickly.
- **ROM** (Read-Only Memory): Permanent memory used for storing firmware.
- **Memory Size**: Determined by the number of address lines and data lines.

#### **Probable Questions**

11. **Q11**: If a system has a 20-bit address bus, what is the maximum memory size it can address?  
   A) 1MB  
   B) 2MB  
   C) 4MB  
   D) 8MB  
   **Answer**: C) 1MB  
   **Explanation**: With a 20-bit address bus, the maximum number of addressable locations is \(2^{20} = 1,048,576\) bytes, which equals 1MB.

12. **Q12**: A microprocessor with a 32-bit data bus can transfer how many bytes at a time?  
   A) 1 byte  
   B) 2 bytes  
   C) 4 bytes  
   D) 8 bytes  
   **Answer**: C) 4 bytes  
   **Explanation**: A 32-bit data bus can transfer 4 bytes (since \(32 \, \text{bits} = 4 \, \text{bytes}\)) in a single operation.

---

### **Interfacing and I/O Ports in Microprocessors**

#### **I/O Ports**  

- **Parallel Interface**: Transfers multiple bits simultaneously across multiple wires.
- **Serial Interface**: Transfers data one bit at a time.

#### **Probable Questions**

13. **Q13**: How many pins are used for parallel data transmission in an 8-bit parallel port?  
   A) 1  
   B) 4  
   C) 8  
   D) 16  
   **Answer**: C) 8

14. **Q14**: In a microprocessor, a serial communication interface typically uses how many pins for data transfer?  
   A) 1  
   B) 2  
   C) 4  
   D) 8  
   **Answer**: A) 1

---

### **Interrupts and Interrupt Pins**

#### **Interrupt Pins in 8085**

- **INTR**: Interrupt request.
- **RST7.5, RST6.5, RST5.5**: Vectored interrupt pins.
- **TRAP**: A non-maskable interrupt pin.

#### **Probable Questions**

15. **Q15**: Which interrupt pin in 8085 is non-maskable?  
   A) RST7.5  
   B) RST6.5  
   C) TRAP  
   D) INTR  
   **Answer**: C) TRAP

16. **Q16**: How many hardware interrupts are available in the 8085 microprocessor?  
   A) 1  
   B) 3  
   C) 5  
   D) 8  
   **Answer**: C) 5  
   **Explanation**: The 8085 microprocessor has 5 hardware interrupts: TRAP, RST7.5, RST6.5, RST5.5, and INTR.

---

### **Direct Memory Access (DMA) and Controllers**

#### **DMA**  

DMA allows peripheral devices to directly access the main memory without CPU intervention, improving efficiency in data transfers.

#### **Probable Questions**

17. **Q17**: Direct Memory Access (DMA) reduces CPU involvement in data transfers by:  
   A) Accessing the I/O ports directly  
   B) Allowing the peripheral device to directly transfer data to/from memory  
   C) Increasing the clock frequency  
   D

) Using multiple buses for data transfer  
   **Answer**: B) Allowing the peripheral device to directly transfer data to/from memory

18. **Q18**: How many channels does a typical DMA controller have?  
   A) 1  
   B) 2  
   C) 4  
   D) 8  
   **Answer**: C) 4

---
