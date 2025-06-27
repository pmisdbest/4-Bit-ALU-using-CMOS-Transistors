# 4-Bit-ALU-using-CMOS-Transistors

# CMOS ALU Hardware Implementation

A complete 4-bit Arithmetic Logic Unit (ALU) designed and implemented using CMOS transistor technology at the circuit level. This project demonstrates the design of fundamental digital logic components and their integration into a functional ALU capable of performing arithmetic and logical operations.

## Features

- **4-bit ALU** with complete arithmetic and logical operations
- **CMOS transistor-level implementation** for all components
- **8 distinct operations** including:
  - Addition (000)
  - Subtraction (001) 
  - Bitwise AND (010)
  - Bitwise OR (011)
  - Bitwise NOT (100)
  - Bitwise XOR (101)
  - Increment 1 bit (110)
  - Left Shift 1 bit (111)
- **Modular design** with individual component implementations
- **Full adder/subtractor circuits** with carry propagation
- **Control unit** for operation selection

## Architecture Overview

The ALU consists of several key components:

### Core Components
- **Control Unit**: 4-bit operation 8:1 Multiplexer for selecting ALU functions
- **Arithmetic Unit**: 4 Bit Full Adders and Subtractors for mathematical operations
- **Logic Unit**: Bitwise operation circuits (AND, OR, NOT, XOR)
- **Shift Unit**: 1-bit incrementer and shift operations

### Circuit Hierarchy

## Implementation Details

### Technology Specifications
- **Technology**: CMOS (Complementary Metal-Oxide-Semiconductor)
- **Design Level**: Transistor-level implementation
- **Data Width**: 4-bit input/output
- **Control Signals**: 3-bit operation select lines

### CMOS Design Principles
- Pull-up networks using PMOS transistors
- Pull-down networks using NMOS transistors
- Complementary logic for power efficiency
- Minimum transistor sizing for optimal performance

## Circuit Diagrams

The repository includes detailed circuit diagrams for:

1. **Control Unit** - Operation selection and decoding logic
2. **Bitwise Operations** - AND, OR, NOT, XOR implementations
3. **1-bit Incrementer** - Single bit increment functionality
4. **4-bit Full Subtractor** - Complete subtraction with borrow propagation
5. **Individual Logic Gates** - Basic CMOS gate implementations

## Operation Codes

| Opcode | Operation | Description |
|--------|-----------|-------------|
| 000 | Addition | A + B |
| 001 | Subtraction | A - B |
| 010 | AND | A & B |
| 011 | OR | A \| B |
| 100 | NOT | ~A |
| 101 | XOR | A ^ B |
| 110 | Increment | A + 1 |
| 111 | Left Shift | A << 1 |

## File Structure


## Design Methodology

1. **Bottom-up Approach**: Started with basic CMOS logic gates
2. **Modular Design**: Each operation implemented as separate module
3. **Hierarchical Integration**: Combined modules into complete ALU
4. **CMOS Optimization**: Minimized transistor count and power consumption

## Key Design Features

- **Low Power Consumption**: CMOS technology ensures minimal static power
- **Scalable Architecture**: Design can be extended to larger bit widths
- **Complete Functionality**: Supports both arithmetic and logical operations
- **Educational Value**: Demonstrates transistor-level digital design principles


## Tools Used

- Circuit design and simulation using LTSpice
- CMOS transistor models
- Logic simulation tools

## Testing and Verification

The ALU has been tested for:
- Correct arithmetic operations (addition, subtraction)
- Proper logical operations (AND, OR, NOT, XOR)
- Shift and increment functionality

## Applications

This ALU design serves as:
- Educational reference for CMOS digital design
- Foundation for microprocessor design courses
- Building block for larger arithmetic units
- Demonstration of transistor-level implementation

## Future Enhancements

Potential improvements include:
- Extension to 8-bit or 16-bit operations
- Addition of multiplication and division
- Implementation of floating-point operations
- Power optimization techniques
- Layout design for fabrication

## Contributing

Contributions are welcome! Please feel free to:
- Report issues or bugs
- Suggest improvements
- Add new operations or features
- Optimize existing designs

## License

This project is open source and available under the Apache 2.0 license.

## Author

Pratham Maan
- GitHub: @pmisdbest
- Email: prathammaan7@gmail.com

## Acknowledgments

- Thanks to the digital design community for CMOS design principles
- Reference materials from computer architecture textbooks
- Open source EDA tools for circuit simulation

---

*This project demonstrates the fundamental principles of digital logic design using CMOS technology, providing a complete working ALU implementation from transistor level to functional operation.*
