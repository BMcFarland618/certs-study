# Week 1
## [3.1 Explain Basic Cable  Types and Their Connectors, Features and Purposes](#31---explain-basic-cable-types-and-their-connectors-features-and-purposes "Chapters 9, 10, 16")
### **Chapter 9**  
- Expansion cards and built-in adapters
    - An Expansion card or adapter card is a printed circuit board installed into an expansion slot in the motherboard to add functionality
    - Common adapter cards are display cards, NICs = network interface cards, video capture cards, sound cards, and cards that add ports like eSATA
    - Most modern motherboards have a lot of these expansion card functions built in.
- Expansion cards = Adapters
- Adapters
    - Display Adapter - controls the output to the display device
        - High performance display adapters often require heat sinks or cooling fans

    - Sound cards - converts digital information into analog sounds
        - This is called digital-to-analog converter or (DAC)
        - Sound cards also do the opposite or Analog-to-digital converter (ADC)
        - Sound card connectors usually consist of 3 or more audio ports all 3.5mm mini jacks. 

    - Capture cards- converts data from an external video source to video files stored on local storage or cloud-based storage space.
        - Takes some burden off the processing side of the PC for converting incoming data
        - Modern capture cards us HDMI.

    - External port adapters and interfaces
        - Connector = plug at the end of a cable (Male)
        - Port = socket where the cable attaches (Female)
        - Ports are also connectors
- USBs
- USB - Universal Serial Bus interface is an external bus that connects to the PCs PCI bus.
    - USB 1.0 and 1.1 - Low-speed versions transmit data up to 1.5MBps (megabits per second)
    - Full-speed 1.1 standard up to 12 Mbps
    - One way at a time transmission - Half-duplex communication

    - Hi-speed USB 2.0 
        - Transmit speeds up to 480Mbps = 60 MBps (Megabytes per second) in half duplex
        - USB Hubs and peripherals are downward compatible.

    - Superspeed USB 3.0
        - Up to 5Gbps (625 MBps)
        - Supports full-duplex communication - communicate in both directions at once

    - USB 3.1
        - Theoretical max speed of 10Gbps (1.25 GBps)
        - Uses USB-C connector
        - USB-C provides both data and power to a device. Faster data transfer and faster charging

    - USB 4.0
        - Uses USB-C connectors and cables
        - Up to 40Gbps speeds

    - Power to USB Devices
        - USB 2.0 500 milliamps of power
        - USB 3.0 900 milliamps of power
        - USB 3.1 up to 100 watts of power

    - USB Ports, Connectors and Cables
        - USB - A
        - USB - C
            - Cable length
            - USB 1.0 = 3 meters
            - USB 2.0 = 4 meters
            - USB 3.0 depends on quality of cable
            - USB 3.1 Gen 1 = 2 meters
            - USB 3.1 Gen 2 - 1 meter
            - USB 4 = 2 meters lower bandwidth
                - .8 meters higher bandwidth
    - Thunderbolt
        - High speed interface primarily in Apple until recent PCs
        - Thunderbolt 4 is a standardization of Thunderbolt 3
        - Can carry display port data as well as PCI express and USB 3.1 data
        - Thunderbolt 1 = 10Gbps throughput in both directions
        - Thunderbolt 2 = 20Gbps
        - Thunderbolt 3 and 4 = 40Gbps
        - Daisy-chain high speed devices without using a hub or switch
        - Can use a Thunderbolt chassis too. Hold PCIe cards
        - Thunderbolt uses Lightning connector/port
    - DB-9 Serial port
        - Legacy serial = 9-pin D-sub connector referred to as RS-232
        - D-sub connector is connector that has either pins or holes with a D-shaped ring around it. Sub is short for subminiature. VGA monitor connectors use this.
    - Communication adapters
        - Communication devices that connect a pc to a network - either LAN or internet
        - Most are built-in in modern PCs
    - Network adapters
        - (NIC) 
        - Connects a PC to a type of network, such as wired ethernet or. wireless Wi-Fi or cellular network.
        - In the workplace, a PC is connected to a LAN, which may be connected to a larger private network and also the internet.
        - At home, devices can connect to a LAN to share internet connection via digital subscriber. Line (DSL) or cable modem connection.
        - Most common connector for ethernet is RJ-45 = Registered Jack. Number designates size not number of wires. RJ-45 connectors have 8 wires.
    - Modem adapters
        - Modem- combined functions of modulator/demodulator. Allowing computers to communicate with one another over telephone lines. Modem can be internal or an adapter. Card in the expansion bus. 
        - Analog modem uses telephone wall jack
        - DSL and cable networks use modem as a misnomer due to all the signals being digital.
        - RJ-11 port is used to attach a phone cable to the wall-mounted phone jack
        - RJ-11 is slightly smaller than an RJ-45 with 2 or 4 wires

    - Cables 
        - SATA, IDE, SCSI, and eSATA



### **Chapter 10**  
- 
### **Chapter 16**   
- 
---
## [3.2 Given a Scenario Install the Appropriate RAM](#32---given-a-scenario-install-the-appropriate-ram "Chapters 9, 11")
### **Chapter 9**  
- Memory
- RAM - Random access memory. Data and programs are accessible in any (random) order.
    - Most RAM is volatile or dynamic RAM. Once the computer is off, no more power is sent to RAM and contents are lost
- Capacity - from bits to bytes
    - Binary digit - bit (light switch on or off) On = 1 Off = 0
    - A group of bits is a byte. Bytes usually are a number divisible by 8.
- Speed - Hertz to gigahertz
    - Hertz - number of electrical cycles or vibrations per second
1 hertz is 1 cycle per second
- RAM and ROM
    - RAM stores the results of each component that the processor completes in order to go to the next task
    - RAM also stores instructions for current running applications

    - ROM is read only. Processor can read the instructions but not store.
- RAM chips and Modules
    - Memory error checking
    - Error Correcting Code - (ECC)
    - Parity - every 8-bit byte comes with a 9th bit (the Parity bit), which determines the presence of errors in the data.
    - 2 types of parity - odd and even
        - Odd Parity- the total number of 1s in the byte are odd
        - Even Parity - the total number of 1s in the byte are even
- Parity memory modules only are used on systems with parity.
- Non-parity systems cannot use parity memory modules. Most modern motherboards do not use parity, but some systems use parity like Server Raids.
- SRAM very fast, very expensive
    - Usually used for caches.
- DRAM is slower and needs more power than SRAM, but is more affordable
    - Is the main memory in a computer
    - Modern DRAM is synchronized with the system clock also know as synchronous DRAM or SDRAM. SDRAM now runs in multiples of the system clock
- Types of DDR SDRAM
    - Dual/Triple and Quad Channel Architecture
        - Dual - system alternates between reading 2 physical separate memory modules
        - Triple - alternates between 3 
        - Quad - alternates between 4
- Multichannel is a function of the motherboard not the RAM itself
    - In multichannel motherboards, memory slots need to be identical. The motherboard treats these sets of slots as if they were a single slot.
    - DDR1 SDRAM processed data by accessing. The memory module twice per clock cycle.
        - Uses 184 pin DIMM socket
        - 2.5 V
        - Code = PC66,  PC100, PC133
    - DDR2 SDRAM faster clock rates starting at 400MHZ. Less power. 
        - Speed increases by clock-doubling the I/O circuits on the chips and adding buffers
        - Uses 240-pin DIMM socket
        - 1.8 V
        - Code = PC2-3200, PC2-8500
    - DDR3 SDRAM
        - Far less power than predecessors
        - Twice the bandwidth
        - 240 pin DIMM socket with a different key notch
        - Dual-channel architecture sold in pairs
        - Memory controller chips (MCC) that support triple channel are available sold in sets of three
        - Code = PC3-3500 etc.
        - Low voltage version is known as DDR3L. Uses 1.35V
        - Useful in darkeners and server farms
    - DDR4 SDRAM
        - Faster, higher density and lower voltage
        - DDR changes how the channels are accessed, using a point-to-point architecture whereby each channel connects to a single module.
        - 288-pin DIMMs Socket
        - Up to 64 GB capacity
        - Uses 1.2 V
    - DDR5 SDRAM
        - Doubles bandwidth of DDR4
        - Up to 512 GB capacity
        - Uses 1.1V 
        - 288-pin DIMM socket but not compatible with DDR4 slots.
        - Usually enclosed in plastic shell with heat sinks

    - Use what is compatible and use identical modules

### **Chapter 11**  
-
---
## [3.3 Given a Scenario Select and Install Storage Devices](#33---given-a-scenario-select-and-install-storage-devices "Chapters 9, 11")
### **Chapter 9**  
- 
### **Chapter 11**  
- 
---
## [3.4 Given a Scenario Install and Configure Motherboards, Central Processing Units CPUS and Add-on Cards](#34---given-a-scenario-install-and-configure-motherboards-central-processing-units-cpus-and-add-on-cards "Chapters 8, 9, 11")
### **Chapter 8**  
- The Motherboard also known as the mainboard, system board or planar board is made of fiberglass  
- ATX or Advanced Technology eXtended measures 12 inches by 9.6 inches  
    - Micro-ATX, Flex-ATX, and Mini-ATX

|Form Factor | Description |
|-----------|-------------|
|ATX         |12x9.6       |
|Micro-ATX(mATX)|9.6x9.6|
|Flex-ATX|9x7.5|
|Mini-ATX|5.9x5.9|
|ITX|8.5x7.5|
|Mini-ITX(mITX)|6.7x6.7|
|Nano-ITX|4.7x4.7|
|Pico-ITX|3.9x2.8|
|Mobile-ITX|2.9x1.77|

- ITX originally named EPIA, used for low-power CPUs  
- ITX boards are mainly used in embedded systems
- Motherboard Components
    - RAM  Slots hold RAM sticks or memory sticks
    - DIMM = Dual Inline  Memory  Module
    - DDR3, DDR4, DDR5 and SODIMM
        - Dual-channel Architecture needs matched pairs of memory. Also come in triple-channel and quad channel.
- Bus Architecture
    - Bus refers to pathways that power, data, or control signals use to travel from one component to another.
        - There are many types of busses. Memory Bus, Expansion Bus, etc.
        - Expansion Bus architecture are PCI, PCIe, and Mini PCIe.
    - PCI = Peripheral Component Interconnect. Transfers data in parallel over  a 32-bit or 64-bit data bus.
    - PCI  slots  are  3 inches long and are used for almost all expansion boards
    - PCIe = Peripheral Component Interconnect Express. New and improved PCI bus.
    - PCIe is not a true bus that transfers data, but a group of serial channels.
    - PCIe connectors have 3 designations x1, x4, and x16. 1, 4, and 16 channels respectively.
    - PCIe x1 is 1.5 inches long, x4 is about 2 inches long and x16 is about 4 inches long.
    - PCIe 1.0 transfers 250MBps per channel. Max transfer rate for PCIe x16 1.0 is 4GBps. 
    - PCIe 2.0 doubled the rate to 500MBps and PCIe 3.0 to 1GBps. PCIe 4.0 doubles that and PCIe 5.0 doubles PCIe 4.0.
    - Mini PCI has a 32-bit data bus like a regular PCI but is smaller.
        - Mini PCI has 3 types. Type 1 and 2 have 100 pins and Type 3 has 124 Pins.
    - Mini PCIe has replaced most Mini PCI in modern Laptops. Faster throughput with a 64-bit data bus.
    -  M.2 = Modern connector type for solid state expansions and drives.
        - M.2 replaced mSATA for mounting solid state storage.
- Motherboard Power Connectors
    - Main Power is a 24-pin connector. 4-pin connectors deliver extra 12 volt power. 6-pin is auxiliary connector that supplies 3.3v and 5v current
    - Some power supplies will have a 20-pin connector + 4 pins. This is a 20+4.
    - 6 and 8 pin power connectors are available for PCIe power boost. These  are 12v connectors and will have yellow abd black wires.
    - 8 pin power connectors also provide additional 12V power.
- Headers
    - Headers are sets of pins on the motherboard to which you can connect a cable.
        - Common port to have a header is USB.
        - USB headers are different. USB 2.0 has a 9 pin header and USB 3.0 has a 20 pin.
- Firmware and Chipsets
    - Firmware is software instructions. Usually held on Read-Only Memory or Rom chips.
    - Firmware built into the motherboard contols basic functions, capabilities and configurability.
    - Firmware on the motherboard includes the chipset and sysstem BIOS.
- CPUs and their sockets
    - GPUs are used to render graphics images GPUs save the CPU for other system-wide functions and improves system performance
    - PC - CPU is a chip that interfaces with or connects to all of the components such ass memory, storage, and I/O through busses
    - A CPU is printed in a single operation onto a silicon wafer. Component parts include the control unit, arithmetic logic unit (ALU), registers, busses, and memory cases
    - The Machine Cycle  4 Basic functions in the machine cycle
        - Fetching an instruction, decoding the instruction, executing the instruction and storing the result
        - The four step cycle employs the control unit, ALU and registers
    - Control Unit
        - The traffic cop of the CPU
        -  Uses electronic signals to direct the CPUs overall operation
        - Control Unit interprets instructions and initiates the action needed to carry them out.
        - It fetches and decodes
    - ALU Arithmetic logic unit
        - Execute the instructions
    - Registers
        - Memory location providing temporary storage for calculations
        - Dedicated registers - specific functions such as maintaining status or system-controlled counting operations
        - General-purpose registers - multi-purpose for mathematical or comparison purposes
        - Store the results in the machine cycle
    - Busses
        - Pathways over which data travels
        - External busses care data to and from the CPU
        - Internal busses move data between the CPUs internal components
    - Cache Memory
        - A pool of extremely. Fast memory that is stored close to the CPU and connected to it by a very fast pathway.
        - L1 (Level 1) cache - closest to the CPU
            - On die cache - it is stamped into the same piece of silicon at the same time as the CPU
        - L2 (Level 2) cache - located either on the motherboard or in the CPU package next to the silicon chip
        - L3 (Level 3) cache - larger, slightly further away from CPU but still on the ceramic chip. On multi-core CPU, all cores share L3 cache.
    - CPU Technologies
        - CPU supports a certain word size. The size of the chunk of data that can enter or exit a CPU in one operation

        - X64 Architecture  64-bit architecture  64-bit or 32-bit windows  More than 4 GB of RAM

        - X86 Architecture  32-bit architecture  32-bit windows and 4GB of RAM
    - Advanced RISC Machine
        - CPUS that can understand a lot of instructions are called Complex Instruction Set Computers (CISCs)
        - CPUs with smaller sets of tasks done extremely quickly are called Reduced Instruction Set Computer (RISC)
        - Advanced RISC Machine (ARM) are most common RISC CPUs. Used in most mobile devices and gaming consoles today.
    - Clock Speed
        - The speed at which a CPU can potentially execute instructions.
        - Clock speed is measured in GHZ
        - CPUs with faster clock speed will often be more expensive
    - Multithreading
        - A thread or thread of execution is a portion of a program that can run separately from other portions of the program.
        -  Multithreading a.k.a. hyper threading and simultaneous multithreading (SMT), is a CPU tech that allows two or more threads to execute at the same time within a single execution core.
    - Multicore
        - A core is a CPU with its own set of control unit, ALU, and registers.
        - Dual core, Quad-core, even 6-core and 128-core Superchip CPUs are available
        - 2 cores on the same chip can communicate and cooperate much faster than two single core processors on a shared motherboard.
        - More cores usually mean faster and more energy efficient.
    - Virtualization support
        - HAV Hardware-assisted virtualization
        - The ability to manage multiple operating systems running at once through virtual machines - enabled through BIOS/UEFI settings.
    - Configuring a Motherboard
        - BIOS and UEFI
        - BIOS is basic firmware on the motherboard. This is called system BIOS
        - BIOS is responsible for power-on self-test (POST)
        - Traditional PC system BIOS is 16-bit program that requires x86 compliant hardware.
    - UEFI - Unified Extensible Firmare Interface
        - A 32-bit or 64-bit BIOS alternative.
        - UEFI supports file systems that enable booting up large drives, supports 32-bit or 64-bit booting not dependent on x86 firmware

### **Chapter 9**  
- 
### **Chapter 11**  
- 
---
## [3.5 Given a Scenario Install or Replace the Appropriate Power Supply](#35---given-a-scenario-install-or-replace-the-appropriate-power-supply "Chapter 10")
### **Chapter   10**  
- 
---
