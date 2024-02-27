# Memory Forensic
## 1. Memory Forensic
Unlike traditional forensic analysis that primarily deals with data stored on hard drives (persistent storage), memory forensics targets the information stored in a computer's RAM, which is lost when the computer is powered off or rebooted. This includes, but is not limited to : 
1. Running processes
2. Open files
3. Network connections
4. System and user information   

at the time the memory was captured.

## 2. Basic Knowledge about Computer Science
1. Chip architecture   

|Name|Description|
|-|-|
|North Bridge| The Northbridge typically handles communications ***`among`*** the CPU, in some cases RAM, and PCI Express video cards, and the southbridge. Some northbridges also contain integrated video controllers, also known as a Graphics and Memory Controller Hub (GMCH) in Intel systems. |
|South Bridge| The Southbridge can usually be distinguished from the northbridge by ***`not being directly connected to the CPU`***.|

2. Types of RAM
* SRAM: Static RAM
* DRAM: Dynamic RAM
* VRAM: Vedio RAM
* NVRAM: Non-volatile RAM
* SDRAM: Synchronous DRAM

## 3. Why Memory Forensic?
Traditional Forensic (Computer Forensic) focuses on:   
1. Data Recovery
2. File Analysis
3. Timeline Analysis
4. Artifact Analysis

Memory Forensic focuses on:    
1. Process Analysis
2. Malware Detection
3. Rootkit Detection
4. System State Analysis

## 4. Memory Image Acquisition
1. Method :   
    * Live : While targeted computer is turning on
    * Off : 
        * Hibernation
        * Swap Files
        * Dump Files
    * ***Local*** or ***Remote***

2. Challenges with Memory Forensic
    1. Structure : Hard to tell the inside structure of a part of memory.
    2. Volatility : No data will be stored after changing.

## 5. Usefull tools for Memory Forensic
1. Free: Belkasoft RAM Capturer, WinPMEM, DumpIT, `Volatility`

2. Commercial: FTK Imager, F-Response

## 6. Practical Case - Using Volatility
STEPS:  

1. Find image info (OS version)
2. Find suspecious network connections
3. Use Malware detection option to check related process

## 7. Useful Link
[case-001-memory-analysis](https://dfirmadness.com/case-001-memory-analysis/)

