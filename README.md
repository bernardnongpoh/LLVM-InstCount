# An LLVM Pass that count the number of Instruction Dynamically 
I just started learning LLVM Compiler infrastructure, as I am working and doing research in program analysis, the first thing that came into my mind is how to do program analysis using LLVM. So basically I am looking at the following two things:- 
- Static Analysis: analysis at compile time example like constant folding, loop unrooling etc. I am not a big fan of this analysis maybe I lack the theory in it hopefully I might find it interesting later. 
- Dynamic Analysis: I have been working with `Pintool` for quite a long time, by building fault injection using Pintool. The first thing I did with pintool is to count the number of instruction executed dynamically. So I am looking for the same functionality here aswell. So I look at different implementation available at github let look at few of them. 

 1. I find this [bbCount by Kelman if name is correct](https://gist.github.com/bploeckelman/3614316) interesting and borrow some of the implementation from there. I also look at [Assignment from UCSD](https://ucsd-pl.github.io/cse231/wi17/part1.html#section2) the hint look great to me. 


An LLVM Pass that count the number of Instruction at Runtime 
