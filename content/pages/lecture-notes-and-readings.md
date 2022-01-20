---
content_type: page
title: Lecture Notes and Readings
uid: 918acd06-aca5-1088-ed18-7978df900929
---

Some of the readings require the [xv6 code (PDF)]({{< baseurl >}}/resources/mit6_828f12_xv6-sourc-rev7), as well as the [xv6 book (PDF - 1.3MB)]({{< baseurl >}}/resources/mit6_828f12_xv6-book-rev7), which are provided courtesy of Frans Kaashoek, Robert Morris, and Russ Cox and are used here with permission.

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
LEC #
{{< thclose >}}
{{< thopen >}}
LECTURE TOPICS AND NOTES
{{< thclose >}}
{{< thopen >}}
READINGS AND HANDOUTS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
1
{{< tdclose >}}
{{< tdopen >}}
[Operating Systems (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec1_notes)
{{< tdclose >}}
{{< tdopen >}}
"Chapter 0: Operating System Interfaces" of xv6 book
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
2
{{< tdclose >}}
{{< tdopen >}}
[PC Hardware and x86 Programming (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec2_notes)
{{< tdclose >}}
{{< tdopen >}}
"Appendix A: PC Hardware" and "Appendix B: The Boot Loader" of xv6 book, and the related xv6 source files
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
3
{{< tdclose >}}
{{< tdopen >}}
[Overview of Major Internals, System Call Interface (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec3_notes)
{{< tdclose >}}
{{< tdopen >}}
"Chapter 1: The first process" and the related xv6 source files
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
4
{{< tdclose >}}
{{< tdopen >}}
[Virtual Memory (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec4_notes)
{{< tdclose >}}
{{< tdopen >}}


"Chapter 2: Page Tables"

[Page Table Translation and Registers (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec4_handout)


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
5
{{< tdclose >}}
{{< tdopen >}}
[Interrupts, Exceptions (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec5_notes)
{{< tdclose >}}
{{< tdopen >}}


"Chapter 3: Traps, interrupts, and drivers" and the related xv6 source files

[IDT (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec5_handout)


{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
6
{{< tdclose >}}
{{< tdopen >}}
[Multiprocessors and Locking (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec6_notes)
{{< tdclose >}}
{{< tdopen >}}
"Chapter 4: Locking" with spinlock.c and skim mp.c
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
7
{{< tdclose >}}
{{< tdopen >}}
[Processes and Switching (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec7_notes)
{{< tdclose >}}
{{< tdopen >}}
"Chapter 5: Scheduling" up to "Sleep and wakeup" with proc.c, setjmp.S, and sys\_fork (in sysproc.c)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
8
{{< tdclose >}}
{{< tdopen >}}
[Sleep & Wakeup (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec8_notes)
{{< tdclose >}}
{{< tdopen >}}
Read remainder of "Chapter 5: Scheduling"; read remainder of proc.c and sys\_wait, sys\_exit, sys\_kill
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
9
{{< tdclose >}}
{{< tdopen >}}
[File Systems (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec9_notes)
{{< tdclose >}}
{{< tdopen >}}
"Chapter 6: File system" and bio.c, fs.c, sysfile.c, file.c, except for the logging sections
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
10
{{< tdclose >}}
{{< tdopen >}}
[Crash Recovery (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec10_notes)
{{< tdclose >}}
{{< tdopen >}}
Read log.c and the logging sections of "Chapter 6: File system"
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
11
{{< tdclose >}}
{{< tdopen >}}
[File System Performance and Fast Crash Recovery (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec11_notes)
{{< tdclose >}}
{{< tdopen >}}
Tweedie, Stephen C. "[Journaling the Linux ext2fs Filesystem](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.307.9137)." \[Paper Presented at LinuxExpo 1998\].
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
12
{{< tdclose >}}
{{< tdopen >}}
Project Introduction and Discussion
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
13
{{< tdclose >}}
{{< tdopen >}}
[OS Organization (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec13_notes)
{{< tdclose >}}
{{< tdopen >}}
Engler, Dawson R., M. Frans Kaashoek, and James O'Toole Jr. "[Exokernel: An Operating System Architecture for Application-Level Resource Management](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.52.2893)."
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
14
{{< tdclose >}}
{{< tdopen >}}
In-class Hacking Session
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
15
{{< tdclose >}}
{{< tdopen >}}
Project Conferences
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
16
{{< tdclose >}}
{{< tdopen >}}
Project Conferences (cont.)
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
17
{{< tdclose >}}
{{< tdopen >}}
[Language / OS Co-design (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec17_notes)
{{< tdclose >}}
{{< tdopen >}}
Hunt, Galen C., and James R. Larus. "[Singularity: Rethinking the Software Stack](http://dx.doi.org/10.1145/1243418.1243424)." _Microsoft Research Redmond_ 41, no. 2 (2007): 37–49.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
Quiz
{{< tdclose >}}
{{< tdopen >}}
Quiz (Open Book and Notes)
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
18
{{< tdclose >}}
{{< tdopen >}}
[Scalable Locks (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec18_notes)
{{< tdclose >}}
{{< tdopen >}}
Boyd-Wickizer, Silas, M. Frans Kaashoek, et al. "[Non-Scalable Locks are Dangerous](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.261.196)."
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
19
{{< tdclose >}}
{{< tdopen >}}
Project Conferences
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
20
{{< tdclose >}}
{{< tdopen >}}
Project Conferences (cont.)
{{< tdclose >}}
{{< tdopen >}}
Boyd-Wickizer, Silas, Austin T. Clements, et al. "[An Analysis of Linux Scalability to Many Cores](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.174.5191)."
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
21
{{< tdclose >}}
{{< tdopen >}}
[Lock-free Coordination (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec21_notes)
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
22
{{< tdclose >}}
{{< tdopen >}}
[Virtual Machines (PDF)]({{< baseurl >}}/resources/mit6_828f12_lec22_notes)
{{< tdclose >}}
{{< tdopen >}}
Adams, Keith, and Ole Agesen. "[A Comparison of Software and Hardware Techniques for x86 Virtualization](http://dx.doi.org/10.1145/1168857.1168860)." _ACM Digital Library_ 34, no. 5 (2006): 2–13.
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
23
{{< tdclose >}}
{{< tdopen >}}
No lecture; work on final projects
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
24
{{< tdclose >}}
{{< tdopen >}}
Demos in class
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
25
{{< tdclose >}}
{{< tdopen >}}
Demos in class (cont.)
{{< tdclose >}}
{{< tdopen >}}
 
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}