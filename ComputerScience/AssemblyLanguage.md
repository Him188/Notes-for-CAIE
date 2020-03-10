# AssemblyLanguage

`macro` (`subroutine`): contains a sequence of instructions that can be used more than once in a program
`directives`: an instruction that tells the assembler to do something


## Assemblers

### Two-pass assembler

#### 1st Pass
1. Data items are converted into their binary equivalent
2. Any directives are acted upon
3. Any symbolic address are added to the symbolic address table

#### 2nd Pass
1. Forward references are resolved
2. Any a symbolic address is replaced by an absolute address
