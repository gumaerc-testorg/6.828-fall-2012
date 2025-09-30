---
content_type: page
description: This section provides guidelines, instructions, and resources on Xv6,
  the teaching operating system used for the course.
learning_resource_types: []
ocw_type: CourseSection
title: Study Materials
uid: 84bedfa1-3b28-16d3-9b78-17929251461c
---
## Introduction

Xv6 is a teaching operating system developed in the summer of 2006 for MIT's operating systems course, 6.828: Operating System Engineering. We hope that xv6 will be useful in other courses too. This page collects resources to aid the use of xv6 in other courses, including a commentary on the source code itself.

## History and Background

For many years, MIT had no operating systems course. In the fall of 2002, one was created to teach operating systems engineering. In the course lectures, the class worked through Sixth Edition Unix (aka V6) using John Lions's famous commentary. In the lab assignments, students wrote most of an exokernel operating system, eventually named Jos, for the Intel x86. Exposing students to multiple systems–V6 and Jos–helped develop a sense of the spectrum of operating system designs.

V6 presented pedagogic challenges from the start. Students doubted the relevance of an obsolete 30-year-old operating system written in an obsolete programming language (pre-K&R C) running on obsolete hardware (the PDP-11). Students also struggled to learn the low-level details of two different architectures (the PDP-11 and the Intel x86) at the same time. By the summer of 2006, we had decided to replace V6 with a new operating system, xv6, modeled on V6 but written in ANSI C and running on multiprocessor Intel x86 machines. Xv6's use of the x86 makes it more relevant to students' experience than V6 was and unifies the course around a single architecture. Adding multiprocessor support requires handling concurrency head on with locks and threads (instead of using special-case solutions for uniprocessors such as enabling / disabling interrupts) and helps relevance. Finally, writing a new system allowed us to write cleaner versions of the rougher parts of V6, like the scheduler and file system. 6.828 substituted xv6 for V6 in the fall of 2006.

## Xv6 Sources and Text

The latest xv6 source is available via

git clone git://pdos.csail.mit.edu/xv6/xv6.git

We also distribute the sources as a printed booklet with line numbers that keep everyone together during lectures. The booklet is available in the lecture notes section. To get the version corresponding to this booklet, run

git checkout -b xv6-rev7 xv6-rev7

The xv6 source code is licensed under the traditional {{% resource_link "852e1a40-0268-4c48-b6c5-1ebd9bfda918" "MIT license" %}}; see the LICENSE file in the source distribution. To help students read through xv6 and learn about the main ideas in operating systems we also distribute a textbook / commentary for the latest xv6, available in the lecture notes section. The line numbers in this book refer to the above source booklet.

xv6 compiles using the GNU C compiler, targeted at the x86 using ELF binaries. On BSD and Linux systems, you can use the native compilers; On OS X, which doesn't use ELF binaries, you must use a cross-compiler. Xv6 does boot on real hardware, but typically we run it using the QEMU emulator. Both the GCC cross compiler and QEMU can be found on the 6.828 tools page.

## Xv6 Lecture Material

In 6.828, the lectures in the first half of the course cover the xv6 sources and text. The lectures in the second half consider advanced topics using research papers; for some, xv6 serves as a useful base for making discussions concrete.

## Unix Version 6

6.828's xv6 is inspired by Unix V6 and by:

- Lions, John. _Lions' Commentary on UNIX_. 6th ed. Peer to Peer Communications, 1977. ISBN: 9781573980135.
    - An on-line version of the {{% resource_link "964f4db4-7d52-47ae-ad61-7a0db279f04d" "Lions commentary" %}}, and {{% resource_link "ab7747d3-75bb-4bc1-8e98-9c5581f9ccfb" "the source code" %}}.
    - The v6 source code is also available {{% resource_link "df8d29d7-7fd5-4776-bb09-34ca44723f87" "online" %}} through {{% resource_link "e92eddc8-ed79-4dec-a7dd-5e3617c70f3d" "the PDP Unix Preservation Society" %}}.

The following are useful to read the original code:

- Digital Equipment. _The PDP11 / 40 Processor Handbook_. Digital Equipment Corporation, 1972.