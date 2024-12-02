# An introduction to C programming

## Content
* C History
* Writing a small C progam, understand the basic workflow
* The very basics on GDB
* A word on a Programming Style Guide
* Assignments, Keywords, Identifiers, Variables
* Control flow
* Functions
* Preprocessor
* Pointers
* Arrays 
* Structures
* Working with files and standard I/O

## Level
beginner

This short course is intended for students and researchers in need of
knowing the very basics of the C programming language.
Familiarity and previous experience with any high level programming
language will be very helpful, as well as a basic knowledge of linux.

## Objectives
This course aims to train the basic concepts of the C-programming language. The different topics are shown in the table below. 
Small examples will be used to experiment with these different topics.

## Setup
During the sessions, a WSL environment (Windows Subsystem for Linux - Ubuntu) with gcc compiler will be used to run and demonstrate the C programs. Very basic Linux commands will be used. 

It can be useful to have an environment available to test small C example programs, either during the session or afterwards to test the different features.
More info on setting up a C-environment: [C environment setup](https://github.com/franklbvp/c_intro/blob/main/docs/cProgramming_installation_environment-windows-2024.pdf)


## Material related to the course

* [hands-on examples](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-examples.zip)

## Slides, Video and More

|Slides |  Extra |
|------------ | -------------------- | 
| [Introduction](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-00-Introduction.pdf)  |     |
| [Some history](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-00-SomeHistory.pdf)  |    |
| [Basic workflow](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-T-BasicWorkflow.pdf)   |   |
| [Programming style](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-T-ProgrammingStyle.pdf)  |    |
| [Debugging basics GDB](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-T-DebugC.pdf)  |  [GDB Quick Start](https://github.com/franklbvp/c_intro/blob/main/docs/gdbQuickGuide.pdf)  |
| [Variables, arithmetic](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-BBB-Variables-coreDataTypes.pdf)  |    |
| [Expressions](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-BBB-Expressions.pdf)  |   |
| [Control flow: conditionals](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-BBB-ControlFlow_Conditionals.pdf)  |   |
| [Control flow: loops](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-BBB-ControlFlow_Loops.pdf)  |    |
| [Funtions](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-BBB-Functions.pdf)  |    |
| [Scoping basics](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-S-Scope_basics.pdf)  |   |
| [Preprocessor](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-S-Preprocessor.pdf)  |    |
| [Pointers](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-S-Pointer_basics.pdf)  |    |
| [Arrays](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-S-Arrays_basics.pdf)  |    |
| [Strings](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-S-Strings_basics.pdf)  |    |
| [Structures](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-S-Structures_basics.pdf)  |    |
| [Dynamic memory](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-S-MemoryManagement.pdf)  |    |
| [Structures: more](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-S-Structures_more.pdf)  |    |
| [One more thing](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-S-OneMoreThing.pdf)  |    |
| [IO](https://github.com/franklbvp/c_intro/blob/main/docs/Ccourse-IO.pdf)  |    |


| PowerPoint Narrative (2021) | 
| -----------------------|
| [Some history](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-00-SomeHistory/1_2e8n2z3u) |   
| [Basic workflow](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-T-BasicWorkflow/1_pwj4imbo) |   
| [Programming style](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-T-ProgrammingStyle/1_38l82nh4)  |   
| [Debugging basics GDB](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-T-DebugC/1_zqes4f7e)  | 
| [Variables, arithmetic](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-BBB-Variables_arthmetic/1_pyk8r2eb)  |   
| [Expressions](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-BBB-Expressions/1_wj3eccz8)  |   
| [Control flow: conditionals](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-BBB-ControlFlow_Conditionals/1_rhedhfsq)  |   
| [Control flow: loops](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-BBB-ControlFlow_Loops/1_rsci04za)  |   
| [Funtions](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-BBB-Functions/1_v1gcjynk)  |   
| [Scoping basics](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-S-Scope_basics/1_0wp58qsy) | 
| [Preprocessor](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-S-Preprocessor/1_k219ecc4) |   
| [Pointers](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-S-Pointer_basics/1_koqey0e6) | 
| [Arrays](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-S-Arrays_basics/1_1zh4ykft)  |   
| [Strings](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-S-Strings_basics/1_044vbccn)  |   
| [Structures](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-S-Structures_basics/1_ly002x9s)  |   
| [Dynamic memory](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-S-MemoryManagement/1_5mvhmrim) | 
| [Structures: more](https://kuleuven.mediaspace.kaltura.com/media/Ccourse-S-Structures_more/1_8e3u3xhb)    |
| [IO](https://kuleuven.mediaspace.kaltura.com/media/c_programming_IO-collabrecording/1_kp5cn3hw)  |   
 



## Check also
* [James Aspnes Notes on Data Structures and Programming Techniques](http://www.cs.yale.edu/homes/aspnes/classes/223/notes.html)
* [Joel Sommers' The Book of C](https://jsommers.github.io/cbook/index.html)
