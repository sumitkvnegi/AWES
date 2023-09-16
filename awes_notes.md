magnetic -> storage

binary == machine languauge == low level programming language

5 phases of computer generation :-

### first 1940-56 = vacuum tube

used for calculation, storage, and control purpose.

**ENIAC:** Electronic Numerical Integrator and Computer, built by J. Presper Eckert and John V. Mauchly (18,000 vacuum tubes)

**EDVAC:** Electronic Discrete Variable Automatic Computer was designed by von Neumann. It could store data also as instruction and thus the speed was enhanced.

**UNIVAC:** Universal Automatic Computer was developed in 1952 by Eckert and Mauchly.

| Characteristics                  | Components                                                                             |
| -------------------------------- | -------------------------------------------------------------------------------------- |
| Main electronic component        | Vacuum tube.                                                                           |
| Programming language             | Machine language.                                                                      |
| Main memory                      | [Magnetic tapes](https://www.geeksforgeeks.org/magnetic-tape-memory/) and magnetic drums. |
| Input/output devices             | Paper tape and punched cards.                                                          |
| Speed and size                   | Very slow and very large (often taking up an entire room).                             |
| Examples of the first generation | IBM 650, IBM 701, ENIAC, UNIVAC1, etc.                                                 |

### second 1956-63 = trainsistor

Another feature was the core storage. Transistors were invented in Bell Labs.

Central Processing Unit (CPU), memory, programming language, and input, and output units also came into the force within the second generation.

The programming language was shifted from high level to programming language and made programming comparatively a simple task for programmers. Languages used for programming during this era were FORTRAN (1956), ALGOL (1958), and COBOL (1959).

| Characteristics                   | Components                                                                                                               |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Main electronic component         | Transistor.                                                                                                              |
| Programming language              | Machine language and assembly language.                                                                                  |
| Memory                            | Magnetic core and magnetic tape/disk.                                                                                    |
| Input/output devices              | Magnetic tape and punched cards.                                                                                         |
| Power and size                    | Smaller in size, had low power consumption, and generated less heat (in comparison with the first-generation computers). |
| Examples of the second generation | PDP-8, IBM1400 series, IBM 7090 and 7094, UNIVAC 1107, CDC 3600, etc.                                                    |

### third 1964-71 = ic

Here a variety of transistors were placed on silicon chips, called semiconductors. IC was made from silicon and also called silicon chips.

A single IC has many transistors, registers, and capacitors built on one thin slice of silicon. Programming was now wiped out Higher level languages like BASIC (Beginners All-purpose Symbolic Instruction Code). Minicomputers find their shape during this era.

| Characteristics                  | Components                                                  |
| -------------------------------- | ----------------------------------------------------------- |
| Main electronic component        | Integrated circuits (ICs).                                  |
| Programming language             | High-level language.                                        |
| Memory                           | Large magnetic core, magnetic tape/disk.                    |
| Input/output devices             | Magnetic tape, monitor, keyboard, printer, etc.             |
| Examples of the third generation | IBM 360, IBM 370, PDP-11, NCR 395, B6500, UNIVAC 1108, etc. |

### fourth 1971-present = microprocessor

the large-scale of integration LSI circuits built on one chip called microprocessors. The computers using microchips were called microcomputers. The Intel 4004 chip, developed in 1971, located all the components of the pc from the central processing unit and memory to input/ output controls on one chip and allowed the dimensions to reduce drastically. Technologies like multiprocessing, multiprogramming, time-sharing, operating speed, and virtual memory made it a more user-friendly and customary device. The concept of private computers and computer networks came into being within the fourth generation.

| Characteristics                                                              | Components                                                                                                            |
| ---------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| Main electronic component                                                    | Very-large-scale integration (VLSI) and the microprocessor (VLSI has thousands of transistors on a single microchip). |
| Memory                                                                       | semiconductor memory (such as[RAM, ROM](https://www.geeksforgeeks.org/difference-between-ram-and-rom/), etc.).           |
| [Input/output devices](https://www.geeksforgeeks.org/input-and-output-devices/) | pointing devices, optical scanning, keyboard, monitor, printer, etc.                                                  |
| Examples of the fourth generation                                            | IBM PC, STAR 1000, APPLE II, Apple Macintosh, Alter 8800, etc.                                                        |

### fifth beyond = ai

| Characteristics                 | Components                                                                                                                                                                                                                                                                         |
| ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Main electronic component       | Based on artificial intelligence, uses the Ultra Large-Scale Integration (ULSI) technology and parallel processing method (ULSI has millions of transistors on a single microchip and the Parallel processing method use two or more microprocessors to run tasks simultaneously). |
| Language                        | Understand natural language (human language).                                                                                                                                                                                                                                      |
| Size                            | Portable and small in size.                                                                                                                                                                                                                                                        |
| Input/output device             | Trackpad (or touchpad), touchscreen, pen, speech input (recognize voice/speech), light scanner, printer, keyboard, monitor, mouse, etc.                                                                                                                                            |
| Example of the fifth generation | Desktops, laptops, tablets, smartphones, etc.                                                                                                                                                                                                                                      |

the 8 **Mechanical Calculators** before modern computers were invented.

1. Abacus (ca. 2700 BC)
2. Pascals Calculator (1652)
3. Stepped Reckoner (1694)
4. Arithmometer (1820)
5. Comptometer (1887) and Comptograph (1889)
6. The Difference Engine (1822)
7. Analytical Engine (1834)
8. The Millionaire (1893)

**Digital Computer:** A digital computer can be defined as a programmable machine which reads the binary data passed as instructions, processes this binary data, and displays a calculated digital output. Therefore, Digital computers are those that work on the digital data.

![1694795907801](image/awes_notes/1694795907801.png)

* **Control Unit : **The Control unit coordinates and controls the data flow in and out of CPU and also controls all the operations of ALU, memory registers and also input/output units. It is also responsible for carrying out all the instructions stored in the program. It decodes the fetched instruction, interprets it and sends control signals to input/output devices until the required operation is done properly by ALU and memory.
* **Memory Registers : **A register is a temporary unit of memory in the CPU. These are used to store the data which is directly used by the processor. Registers can be of different sizes(16 bit, 32 bit, 64 bit and so on) and each register inside the CPU has a specific function like storing data, storing an instruction, storing address of a location in memory etc. The user registers can be used by an assembly language programmer for storing operands, intermediate results etc. Accumulator (ACC) is the main register in the ALU and contains one of the operands of an operation to be performed in the ALU.

**Interconnection between Functional Components**

A computer consists of input unit that takes input, a CPU that processes the input and an output unit that produces output. All these devices communicate with each other through a common bus. A bus is a transmission path, made of a set of conducting wires over which data or information in the form of electric signals, is passed from one component to another in a computer. The bus can be of three types – Address bus, Data bus and Control Bus.

![1694796256205](image/awes_notes/1694796256205.png)

The address bus carries the address location of the data or instruction. The data bus carries data from one component to another and the control bus carries the control signals. The system bus is the common communication path that carries signals to/from CPU, main memory and input/output devices. The input/output devices communicate with the system bus through the controller circuit which helps in managing various input/output devices attached to the computer.

[Booting](https://www.geeksforgeeks.org/booting-and-dual-booting-of-operating-system/) may be defined as process of loading the operating system into memory. The booting process starts from the moment when we power on computer and continues till moment, computer is ready for use. In the case of [DOS](https://www.geeksforgeeks.org/dos-full-form/), booting process starts when we start computer and continues till DOS prompt is displayed. The booting process of DOS mainly deals with loading three main system files of DOS into memory. These files are  **IO.SYS** , **MSDOS.SYS** and  **COMMAND.COM** .

In the booting process of DOS, the following steps are performed when we start a computer –

1. Once the computer system is turned on, **BIOS** (Basic Input /Output System) performs a series of activities or functionality test on programs stored in ROM, called on **Power-on Self Test** (POST) that checks to see whether peripherals in system are in perfect order or not.
2. After the **BIOS** is done with pre-boot activities or functionality test, it read bootable sequence from** CMOS** (Common Metal Oxide Semiconductor) and looks for master boot record in first physical sector of the bootable disk as per boot device sequence specified in  **CMOS** . For example, if the boot device sequence is –
   1. Floppy Disk
   2. Hard Disk
   3. CDROM
3. After this, master boot record will be searched first in a floppy disk drive. If not found, then hard disk drive will be searched for master boot record. But if the master boot record is not even present on hard disk, then CDROM drive will be searched. If the system is not able to read master boot record from any of these sources, ROM displays the message “**No Boot device found”** and system is halted. On finding master boot record from a particular bootable disk drive, operating system loader, also called Bootstrap loader is loaded from boot sector of that bootable drive· into memory. A bootstrap loader is a special program that is present in boot sector of bootable drive.
4. Bootstrap loader first loads the** IO.SYS** file. After this, **MSDOS.SYS** file is loaded which is core file of DOS operating system.
5. After this, **MSDOS.SYS** file searches to find Command Interpreter in **CONFIG.SYS** file and when it finds, it loads into memory. If no Command Interpreter specified in the** CONFIG.SYS** file, the** COMMAND.COM** file is loaded as default Command Interpreter of DOS operating system.
6. The last file is to be loaded and executed is the** AUTOEXEC.BAT** file that contains a sequence of DOS commands. After this, the prompt is displayed, and we can see drive letter of bootable drive displayed on the computer system, which indicates that operating system has been successfully on the system from that drive.

**[Types of Booting](https://www.geeksforgeeks.org/difference-between-cold-booting-and-warm-booting/) :**

1. **Cold Booting/Switch Booting –**
   When the user starts computer by pressing power switch on system unit, the operating system is loaded from disk to main memory this type of booting is called** Cold Booting. **This booting takes more time than Hot or Warm Booting.
2. **Hot or Warm Booting –**
   Hot booting is done when computer system comes to no response state/hang state. Computer does not respond to commands supplied by user. There are many reasons for this state, only solution is to reboot computer by using the **Reset button** on cabinet or by pressing a combination of **ALT + CTRL + DEL** keys from keyboard.

The memory of a Computer is any physical device that is capable of storing information whether it is large or small and stores it temporarily or permanently. For example, [Random Access Memory (RAM)](https://www.geeksforgeeks.org/different-types-ram-random-access-memory/), is a type of volatile memory that stores information for a short interval of time, on an integrated circuit used by the Operating System.

Memory can be either volatile or non-volatile. Volatile memory is a type of memory that loses its contents when the computer or hardware device is switched off. RAM is an example of a volatile memory i.e. why if your computer gets rebooted while working on a program, you lose all the unsaved data. Non-volatile memory is a memory that keeps its contents saved even in the case of power loss. [EPROM((Erasable Programmable ROM)](https://www.geeksforgeeks.org/eprom-full-form/) is an example of non-volatile memory.

### Types of Computer Memory

* [Primary Memory](https://www.geeksforgeeks.org/primary-memory/)
* [Secondary Memory](https://www.geeksforgeeks.org/secondary-memory/)
* [Cache Memory](https://www.geeksforgeeks.org/cache-memory/)


#### Primary Memory

Primary Memory is called as main memory of the System. During computer operations, it stores data, programs, and instructions. It is commonly called Semiconductor Memory or Volatile Memory. Primary Memory is faster than Secondary Memory.


## **Characteristics of Main Memory**

* Semiconductor memories.
* Faster than secondary memories.
* A computer cannot run without primary memory.
* It is the working memory of the computer.
* Usually volatile memory.
* Data is lost in case the power is switched off.

#### Secondary Memory

Secondary Memory is used to store a heavy amount of data or information. The data or information stored in Secondary Memory is permanent and secondary memory is slower than primary memory, but secondary memory can’t be directly accessible by the CPU.

#### Cache Memory

Cache Memory is faster memory that helps in fastening the speed of the CPU. Cache Memory is used to store the data that is frequently required by the CPU. Whenever the system gets off, data present in the cache memory gets lost.



## Units of Memory

 A group of eight bits is known as a Byte. 1 Byte can represent numbers between zero (00000000) and 255 (11111111), or 2^8^ = 256 distinct positions.

## **Types of Various Units of Memory**

* Bit
* Nibble
* Byte
* Kilo Byte
* MegaByte
* Giga Byte
* Tera Byte
* Peta Byte
* Exa Byte
* Zetta Byte
* Yotta Byte

A Byte is abbreviated with a big “B” whereas a bit is abbreviated with a small “b”.


| Name      | Equal To          | Size (In Bytes)                           |
| --------- | ----------------- | ----------------------------------------- |
| Bit       | 1 Bit             | 1/8                                       |
| Nibble    | 4 Bits            | 1/2 (rare)                                |
| Byte      | 8 Bits            | 1                                         |
| Kilobyte  | 1024 Bytes        | 1024                                      |
| Megabyte  | 1, 024 Kilobytes  | 1, 048, 576                               |
| Gigabyte  | 1, 024 Megabytes  | 1, 073, 741, 824                          |
| Terrabyte | 1, 024 Gigabytes  | 1, 099, 511, 627, 776                     |
| Petabyte  | 1, 024 Terabytes  | 1, 125, 899, 906, 842, 624                |
| Exabyte   | 1, 024 Petabytes  | 1, 152, 921, 504, 606, 846, 976           |
| Zettabyte | 1, 024 Exabytes   | 1, 180, 591, 620, 717, 411, 303, 424      |
| Yottabyte | 1, 024 Zettabytes | 1, 208, 925, 819, 614, 629, 174, 706, 176 |




****Primary memory ****is a segment of computer memory that can be accessed directly by the processor. In a hierarchy of memory, primary memory has access time less than secondary memory and greater than cache memory. Generally, primary memory has a storage capacity lesser than secondary memory and greater than cache memory.

## Need of primary memory

In order to enhance the efficiency of the system, memory is organized in such a way that access time for the ready process is minimized. The following approach is followed to minimize access time for the ready process.

* All programs, files, and data are stored in secondary storage that is larger and hence has greater access time.
* Secondary memory can not be accessed directly by a CPU or processor.
* In order, to execute any process operating system loads the process in primary memory which is smaller and can be accessed directly by the CPU.
* Since only those processes are loaded in primary memory which is ready to be executed, the CPU can access those processes efficiently and this optimizes the performance of the system.


## Primary Memory Example

Primary Memory examples are [RAM](https://www.geeksforgeeks.org/different-types-ram-random-access-memory/), [ROM](https://www.geeksforgeeks.org/read-only-memory-rom/), [cache](https://www.geeksforgeeks.org/cache-memory-in-computer-organization/), [PROM](https://www.geeksforgeeks.org/prom-full-form/),[ EPROM](https://www.geeksforgeeks.org/eprom-full-form/), registers, etc.

## Classification of Primary Memory

Primary memory can be broadly classified into two parts:

1. ****R****ead-****O****nly ****M****emory (ROM)
2. ****R****andom ****A****ccess ****M****emory (RAM)

![1694858131341](image/awes_notes/1694858131341.png)


## Read-Only Memory

Any data which need not be altered are stored in ROM. ROM includes those programs which run on booting of the system **(known as **a **bootstrap program **that initializes** OS) **along with data like algorithm required by OS. Anything stored in ROM cannot be altered or changed.

### ****Types of ROM:****

ROM can be broadly classified into 4 types based on their behavior:

* ****MROM: ******Masked ROM **is hardwired and pre-programmed ROM. Any content that is once written cannot be altered anyhow.
* ****PROM: ******Programmable ROM **can be modified once by the user. The user buys a blank PROM and writes the desired content but once written content cannot be altered.
* ****EPROM: ******Erasable and Programmable ROM **Content can be changed by erasing the initial content which can be done by exposing EPROM to UV radiation. This exposure to ultra-violet light dissipates the charge on ROM and content can be rewritten on it.
* ****EEPROM: ******Electrically Erasable and Programmable ROM **Content can be changed by erasing the initial content which could be easily erased electrically. However, one byte can be erased at a time instead of deleting in one go. Hence, reprogramming of EEPROM is a slow process.


## Random Access Memory

Any process in the system which needs to be executed is loaded in RAM which is processed by the CPU as per Instructions in the program. Like if we click on applications like Browser, firstly browser code will be loaded by the Operating system into the RAM after which the CPU will execute and open up the Browser.

### ****Types of RAM:****

RAM can be broadly classified into SRAM (Static RAM) and DRAM (Dynamic RAM) based on their behavior:

* [****DRAM****](https://www.geeksforgeeks.org/dram-full-form/)****: ****Dynamic RAM or DRAM needs to periodically refresh in a few milliseconds to retain data. DRAM is made up of capacitors and transistors and electric charge leaks from capacitors and DRAM needs to be charged periodically. DRAM is widely used in home PCs and servers as it is cheaper than SRAM.
* [****SRAM****](https://www.geeksforgeeks.org/sram-full-form/)****:**** Static RAM or SRAM keeps the data as long as power is supplied to the system. SRAM uses Sequential circuits like a flip-flop to store a bit and hence need not be periodically refreshed. SRAM is expensive and hence only used where speed is the utmost priority.


## ****When cache memory comes into existence?****

Data in primary memory can be accessed faster than secondary memory but still, access times of primary memory are generally in a few microseconds, whereas the CPU is capable of performing operations in nanoseconds. Due to the time lag between accessing data and acting on data performance of the system decreases as the CPU is not utilized properly, it may remain idle for some time. In order to minimize this time gap new segment of memory is Introduced known as Cache Memory.
