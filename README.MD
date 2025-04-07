## Structured Programming
### Structure Theorm
The structured program theorem, also known as the Böhm–Jacopini theorem, is a fundamental result in programming language theory that states any computable function can be expressed using only three control structures: sequence, selection (if-then-else), and repetition (while or for loops). 

##### Sequence 
- Sequence is the most basic of the construct
- It is simply performing one step after another
- Each step is followed in a specific sequence
- Sequence can be thought of as "do this, then do this, then do this"

#### Selection(Decision)
- Selection is the decision making construct
- It is used to make yes/no or true/false decision logically.
- Selection can be though of as "if somethind is true take this action, otherwise take this action"

#### Repetition (Iteration/ Looping)
- Iteration can from the work "reiterate", which means to repeat
- Iteration is a looping construct
- Iteration is a combination of decision and sequence and can repeat steps
- Iteration can be though of as "while something is true, do this, otherwise stop"

### Program Design Methods
There are six standard methods -
1. Pseudo Code
2. Structured Diagrams (Graphical Design Notation)
3. Structured Flow Chart (Graphical Design Notation)
4. Decision Tables (Tabular Design Notation)
5. Nassi-Shneidermen Chart (Graphical Design Notation)
6. HIPO

## Pseudo Code	
The prefix pseudo means "fake" ; pseudo code, therefore , literally means " fake code" – that is, not the code that is actually entered into the computer. Pseudo code uses human-language statements instead of symbols (such as flowchart symbols) do represent program logic. It is more precise in representing logic than regular idiomatic English but dose not follows a specific programming language's syntax. Pseudo code statements can be composed and edited by hand or by using a typical of the shelf word processing program. Some people would argue further that pseudo code is much closer to actual code than are flowcharts, which makes pseudo code more productive than flow chatting. However, some programmer's don't like to use pseudo code because it is doesn't depict the program logic visually like a flowchart does.

- To describe the algorithm
	- Informal language for program definition
	- Very much like a computer language
	- Consists of a set of action-oriented commands
	- May have different versions
	- A common language for computer programming languages
	- An English-like language
	- Has few grammar rules but there is enough structure
	- Describe the processes carried out by a program
	- Each set of instructions is written from top to bottom, with only one entry and one exit

### Pseudo Code Definition
- The assignment symbol means "takes the value of"
- Sequencing is indicated by indentation
- Keywords allow data input to and output from the program:
    - read-to input data from a backing store
    - write-to output data backing store
    - accept-to input data from a keyboard
    - display-to output data to screen
    - print-to output data to a printer
- There are three looping constructs:

```shell
(i)repeat-until
repeat
	command-sequence:
until (condition);

(ii) while
while (condition)
do
	command-sequence:
endo;

(iii) for
for index from a to b
do
	command-sequence:
endo;
```

- Conditional branching may use the if-then-else construct:
```shell
if  (condition) then
	command-sequence1:
else
	command-sequence2:
endif;

# Multiple branching (or selection) with nested ifs:
if  (condition1) then
	command-sequence1:
elseif (condition2)  then
	command-sequence2:
elseif (condition3) then
   ......................
   .....................
else
	default command sequence;
endif;
```

- Alternative selection ladder- the case structure
```shell
do case of index
	case index (condition1)
	command sequence1;
case index (condition2)
	command sequence2;
case index (condition....)
   	------
	------
case index (condition N)
	command sequence N;
   	otherwise	
	default command sequence;
endcase;
```

` Operators
1. Arithmetic Operator
	- "+" addition
	- "-" subtraction
	- "*" multiplication
	- "/" division

2.	Relational Operator
	-	"=" equal to
	-	">"	greater than
	-	"<"	less than
	-	"<>" not equal to
	-	">=" greater than or equal to
	-	"<=" less than or equal to

3.	Logical operator
	- and, or, not

4. Operator Precedence
	1. (), 
	2. *,/
	3. +, -


#### Simple Sequence
##### Example
```shell
begin
    Walk to door
    Open door
    Move through door
end
```

#### Simple Selection
##### Example
```shell
if (inside room) then
 	Pull door
else
	Push door
endif
```

#### Simple Repetition
##### Example
```shell
while nails is sticking out 
	hit nail
endwhile
```

### A systematic Approach to Defining a Problem
Defining the problem is the first step towards a problem solution. A systematic approach to problem definition, leads to a good understanding of the problem. Here is a tried and tested method for defining (or specifying) any given problem:
- Divide the problem into three (3) separate components:
	1. input or source data provided
	2. output or end result required
	3. processing-a list of what actions are to be performed
