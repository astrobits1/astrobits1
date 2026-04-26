### Hi, I like building and learning about low-level systems

I build things primarily to understand them, most of my projects are not meant 
to be useful or widely used, just explorations of systems from the ground up.

I do not use code generators or assistants and prefer to handcraft all 
aspects for the same reasons.

### Here are some of my projects

- <b>MegaGB</b>: A Gameboy/Gameboy color emulator in C, with C++ frontend in SDL2 and minimal ImGui debug logging.
  - <i>Areas explored:</i> Cycle accurate emulation of the Sharp SM83 (Z80 like) Processor. Pixel FIFO simulation for the PPU.
    Interleaving DMA, Timers and scheduling. Targetting high accuracy and commercial ROMs. Building a disassembler and debug
    tools.
<hr>
    
- <b>MegaScript</b>: A high level embeddable bytecode interpreted scripting language in C, with experimental self hosted standard
   lib support (JSON Parsing, HTTP/S) and DLL interfacing.
  
  - <i>Areas explored:</i> Recursive descent parsing in C, bytecode emission and virtual machine state handling. Anonymous functions,
    OOP, Garbage collection, closures, VM-level support for coroutine and stack preservation and more.
<hr>

### What I'm currently working on

- <b>MegaGBA</b>: A Gameboy Advance emulator in C, with C++ frontend in SDL2.
  
  - <i>Areas explored:</i> Emulating the ARM7TDMI core. Implementing a multilayer 2d graphics pipeline, with priority layering,
    alpha blending and SFX. Adding runtime debugging tools and memory inspectors.
<hr>

- <b>TesseractOS</b>: A 64 bit kernel in C and ASM with the goal of building a tinkerer's hobby OS with niche features and design ideas.
  (very initial stage)

  - <i>Areas explored:</i> Building a 32 bit boot kernel for bootstrapping, minimal ELF loading, setting up GDT, IDT and a basic VGA driver.
    
