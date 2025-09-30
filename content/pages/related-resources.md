---
content_type: page
description: This section provides a list of useful references for those interested
  in learning more about the topics covered in the course.
draft: false
learning_resource_types: []
ocw_type: CourseSection
title: Related Resources
uid: 05febe3c-96b3-a001-d66e-1498c63ab27e
---
The resources provided below are useful references for those interested in learning more about the topics covered in the course.

## UNIX®

- Ritchie, Dennis M., and Ken L.Thompson. "{{% resource_link "e9ea4149-eb67-4049-b328-2be6a4b7eaac" "The UNIX® Time-Sharing System" %}}." *Bell System Technical Journal* 57, no. 6 part 2 (1974): 1905–30. You read this paper in 6.033.
- Ritchie, Dennis M. "{{% resource_link "3bbc6529-cfcc-4b44-9248-c55462b00d9c" "The Evolution of the Unix® Time-sharing System" %}}." 1984.
- Kernighan, Brian, and Dennis Ritchie. *The C Programming Language*. 2nd ed. Prentice Hall, 1988. ISBN: 9780131103627.

## x86 Emulation

- {{% resource_link "3050faf3-66af-43f8-8b03-396a232ac582" "QEMU" %}}—A fast and popular x86 platform and CPU emulator.
    - {{% resource_link "82eb298e-dc72-4646-860f-42458b730cbd" "User Manual" %}}
- {{% resource_link "88e47565-638a-478e-a826-ba9ce70720d3" "Bochs" %}}—A more mature, but quirkier and much slower x86 emulator. Bochs is generally a more faithful emulator of real hardware than QEMU.
    - {{% resource_link "ec2a1758-5570-4611-96a8-3f33e23d761e" "User Manual" %}}
    - {{% resource_link "004e78a5-b00f-4f36-a73c-6edf72700cf2" "Debugger Reference" %}}

## x86 Assembly Language

- {{% resource_link "686572c6-2398-4e86-a0c4-de5b60a00dd6" "*PC Assembly Language*" %}}, Paul A. Carter, July 2006.
- {{% resource_link "d61c5692-80bb-45f9-aff6-3534e3439df0" "*Intel® 80386 Programmer's Reference Manual*" %}}, 1987 (HTML®).    
    Much shorter than the full current Intel® Architecture manuals below, but describes all processor features used in 6.828.
- {{% resource_link "fac2a964-497c-42dd-b0dc-631b66e92726" "*IA-32 Intel® Architecture Software Developer's Manuals*" %}}, Intel®, 2007. Download the following manuals:
    - Volume I: Basic Architecture
    - Volume 2A: Instruction Set Reference, A–M
    - Volume 2B: Instruction Set Reference, N–Z
    - Volume 3: System Programming Guide
- Multiprocessor References:
    - {{% resource_link "8e587dd8-9354-4a30-a73b-3ced49555134" "MP specification" %}}
    - {{% resource_link "59d2d54d-3d4f-437c-8280-1f21d60ec2a2" "IO APIC" %}}
- {{% resource_link "5f35ae0f-e14f-4ffd-b004-5a91c4628c40" "AMD64 Architecture Programmer's Manual" %}}.    
    Covers both the "classic" 32-bit x86 architecture and the new 64-bit extensions supported by the latest AMD and Intel® processors.
- Writing Inline Assembly Language with GCC:
    - {{% resource_link "105e939a-8fb4-4bf8-b154-d1ecd2d4f49e" "Brennan's Guide to Inline Assembly" %}}, Brennan "Mr. Wacko" Underwood
    - {{% resource_link "b213eca6-bd3b-4bff-b7fa-8f8758595b21" "Inline assembly for x86 in Linux®" %}}, Bharata B. Rao, IBM®
    - {{% resource_link "be78ffe6-7bb0-4e7f-b320-2e4e37a78ab9" "GCC-Inline-Assembly-HOWTO" %}}, Sandeep. S
- Loading x86 Executables in the ELF Format:
    - Tool Interface Standard (TIS) Executable and Linking Format (ELF).    
        The definitive standard for the ELF format.

## PC Hardware Programming

- General PC Architecture Information:
    - {{% resource_link "67aa7fea-8763-411a-be0c-2260dfa3eaf1" "Phil Storrs PC Hardware book" %}}, Phil Storrs, December 1998.
    - {{% resource_link "838dff9a-9407-4a63-9438-437293276cf6" "Bochs technical hardware specifications directory" %}}.
- General BIOS and PC Bootstrap:
    - {{% resource_link "b790b5ed-9c9a-4785-a247-e098ea1b27f3" "BIOS Central" %}}
    - {{% resource_link "5822beae-5390-4308-904f-e637b6f09ad6" "BIOS Services and Software Interrupts" %}}, Roger Morgan, 1997.
    - {{% resource_link "3aac17e5-a011-46a4-8ac8-cf8ce466eb5b" "\"El Torito\" Bootable CD-ROM Format Specification" %}}, Phoenix / IBM®, January 1995.
- VGA Display - kern / console.c
    - {{% resource_link "54f16423-0251-4865-88f0-7e42c058de1c" "VESA BIOS Extension (VBE) 3.0 (PDF)" %}}, {{% resource_link "b99244ea-2d86-48ba-bfb9-68c773465185" "Video Electronics Standards Association" %}}, September 1998.
    - {{% resource_link "19a08926-cb9f-4e35-9e1a-88358c1a29e7" "VGADOC" %}}, Finn Thøgersen, 2000.
    - {{% resource_link "4918d6e8-bd11-4102-8608-90b02f97d093" "Free VGA Project" %}}, J. D. Neal, 1998.
- Keyboard and Mouse - kern / console.c
    - {{% resource_link "12fd2b02-7a49-4afe-96be-b4a135c9fa44" "Adam Chapweske's Resources" %}}
- 8253/8254 Programmable Interval Timer (PIT) - inc / timerreg.h
    - {{% resource_link "b4000de2-a877-4f93-a7b1-cccf0448b852" "82C54 CHMOS Programmable Interval Timer" %}}, Intel®, October 1994.
    - Data Solutions 8253/8254 Tutorial, Data Solutions.
- 8259/8259A Programmable Interrupt Controller (PIC) - kern / picirq.\*
    - {{% resource_link "838dff9a-9407-4a63-9438-437293276cf6" "8259A Programmable Interrupt Controller" %}}, Intel®, December 1988.
- Real-Time Clock (RTC) - kern / kclock.\*
    - {{% resource_link "67aa7fea-8763-411a-be0c-2260dfa3eaf1" "Phil Storrs PC Hardware book" %}}, Phil Storrs, December 1998. In particular:
        - {{% resource_link "ce9aeb18-0a2e-46a5-89fb-01e70bf7d114" "Understanding the CMOS" %}}
        - {{% resource_link "6472bc6f-eb4b-4fe4-baac-90a04157b090" "A list of what is in the CMOS" %}}
    - CMOS Memory Map, Padgett Peterson, May 1996. ({{% resource_link "b04c4865-f1e6-4be8-a07a-6258263f3929" "TXT" %}})
    - {{% resource_link "dcebbb7b-0f99-4aca-9344-732e837ad7c9" "M48T86 PC Real-Time Clock" %}}, ST Microelectronics, April 2004.
- 16550 UART Serial Port - kern / console.c
    - PC16550D Universal Asynchronous Receiver / Transmitter with FIFOs, National Semiconductor, 1995.
    - {{% resource_link "f033e54b-a7b2-4a1d-b732-dfea6b207cfb" "Technical Data on 16550" %}}, Byterunner Technologies.
    - {{% resource_link "f6554ce5-5871-40fb-81c2-044c67fd0133" "Interfacing the Serial / RS232 Port" %}}, Craig Peacock, August 2001.
- IEEE 1284 Parallel Port - kern / console.c
    - {{% resource_link "5c6ad9a3-e7f0-417a-99ed-eee315be66b3" "Parallel Port Central" %}}, Jan Axelson.
    - {{% resource_link "b5620b6b-8f79-465e-915b-c06782f7dc0d" "IEEE 1284 - Updating the PC Parallel Port" %}}, National Instruments.
    - {{% resource_link "ffb2e2e3-49ba-434e-b1ee-906d34aa83d3" "Interfacing the Standard Parallel Port" %}}, Craig Peacock, August 2001.
- IDE Hard Drive Controller - fs / ide.c
    - AT Attachment with Packet Interface - 6 (working draft), ANSI, December 2001.
    - Programming Interface for Bus Master IDE Controller, Brad Hosler, Intel®, May 1994.
    - {{% resource_link "714bd64c-f6d5-43c6-8b71-120deded7ef2" "The Guide to ATA / ATAPI documentation" %}}, Constantine Sapuntzakis, January 2002.
- Sound Cards (not supported in 6.828 kernel, but you're welcome to do it as a challenge problem!)
    - Signal Processing using Sound Cards
    - {{% resource_link "5243bb4d-8e73-4575-b54a-1426e7308d93" "Sound Blaster Series Hardware Programming Guide (PDF)" %}}, Creative Technology, 1996.
    - 8237A High Performance Programmable DMA Controller, Intel®, September 1993.
    - {{% resource_link "7c1c2823-af84-4103-ae43-b653ebee2b9f" "Sound Blaster 16 Programming Document" %}}, Ethan Brodsky, June 1997.
- E100 Network Interface Card
    - Intel 8255x 10 / 100 Mbps Ethernet Controller Family Open Source Software Developer Manual
    - 82559ER Fast Ethernet PCI Controller Datasheet
- E1000 Network Interface Card
    - PCI / PCI-X Family of Gigabit Ethernet Controllers Software Developer's Manual