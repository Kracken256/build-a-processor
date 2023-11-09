# build-a-processor
A project where I will build a 64-bit multi-core processor an ALU, PORT IO, synced memory/data bus, and more!

## Progress and Goals
- ✅ Build gated latch
- ✅ Build 1/8/64 bit register
- ✅ Register control and addressing logic
- ✅ Build 8 bit ALU for AND, OR, XOR, and NOR operations
- ✅ Build 1/8/64 bit full adder
- 🔜 Expand ALU to 64 bit
- 🔜 Add ADD,SUB,MUL,DIV,SHIFT,ROTATE, and more operations to ALU
- 🔜 Program counter
- 🔜 Instruction register
- 🔜 Instruction decoder
- 🔜 Internal SRAM addressable memory
- 🔜 Opcode => microcode translation table
- 🔜 Write microcode for all instructions
- 🔜 Conditional branching
- 🔜 Control wires, RESET, HLT, ENABLE, etc.
- 🔜 Chip debug interface to dump internal SRAM
- 🔜 Multi-core IO syncronization and external peripheral IO
- 🔜 Interrupts


## Would be nice
These are things that would be nice to have but probably won't be implemented.
- 🔜 Memory segmentation
- 🔜 Low level control of internal operations
- 🔜 Microcode updates
- 🔜 Any kinds of luxury hardware acceleration: AES-NI, SIMD, COMPRESSION, VIDEO, etc.
- 🔜 Floating point operations

#### Note on this GitHub repo
Because this project is using GUI design files, commit messages won't be very useful. Most commits will just be 'Updates' on the same few files. Once this project gets more complex, I will start using a changelog file.