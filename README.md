# cs2110-homework-2--alu-solved
**TO GET THIS SOLUTION VISIT:** [CS2110 Homework 2- ALU Solved](https://www.ankitcodinghub.com/product/cs-2110-homework-2-alu-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109424&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2110 Homework 2- ALU Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
Optional Tutorial

Note: This tutorial is optional and to help you get acquainted with CircuitSim before you start this homework. If you’re comfortable with this software, feel free to skip to section 2. CircuitSim is an interactive circuit simulation package. We will be using this program for the next couple of homework assignments. This is a tutorial to help you get acquainted with the software. CircuitSim is a powerful simulation tool designed for educational use. This gives it the advantage of being a little more forgiving than some of the more commercial simulators. However, it still requires some time and effort to be able to use the program efficiently. With this in mind, we present you with the following assignment:

1.1 Part 1 — Read Resources

Read through the following resources

• CircuitSim Wires Documentation https://ra4king.github.io/CircuitSim/docs/wires/

• Tutorial 1: My First Circuit https://ra4king.github.io/CircuitSim/tutorial/tut-1-beginner

1.2 Part 2 — Complete Tutorial 2

Complete Tutorial 2 https://ra4king.github.io/CircuitSim/tutorial/tut-2-xor

Instead of saving your file as xor.sim, save your file as part1.sim. As well, make sure you label your two inputs a and b, and your output as c, as well as rename your subcircuit to xor.

1.3 Part 3 — Complete Tutorial 3

Complete Tutorial 3 https://ra4king.github.io/CircuitSim/tutorial/tut-3-tunnels-splitters Name the subcircuit umbrella, the input in, and the output out. Save your file as part2.sim.

2 Overview

All computer processors have a very important component known as the Arithmetic Logic Unit (ALU). This component allows the computer to do, as the name suggests, arithmetic and logical operations. For this assignment, you’re going to build an ALU of your own, along with creating some of the gates.

For this assignment you will:

1. Create the standard logic gates (NAND, NOR, NOT, AND, OR)

2. Create an 8-input multiplexer and an 8-output decoder

3. Create a 1-bit full adder

4. Create an 8-bit full adder using the 1-bit full adder

5. Use your 8-bit full adder and other components to construct an 8-bit ALU

3 Instructions

For this assignment, you will be using CircuitSim. The version is the exact same as the one used in Homework 1 and is included in the 2110 Docker container. If you are having issues with Docker, it can also be found on canvas under Files -&gt; Tools -&gt; CircuitSim -&gt; CircuitSim.v1.jar.

3.1 Requirements

Use of anything not listed above will result in heavy deductions. Your need to have everything in their correctly named sub-circuit. More information on sub-circuits is given below.

Use tunnels where necessary to make your designs more readable, but do not overdo it! For gates, muxes, adders and decoders you can often get clean circuits just by placing your components well rather than using tunnels everywhere.

3.2 Part 1: 1-Bit Logic Gates

ALLOWED COMPONENTS: Wiring Tab and Circuits Tab

All of the circuits in this file are in the gates.sim file.

For this part of the assignment, you will create a transistor-level implementation of the NAND, NOT, NOR, AND, and OR logic gates.

Remember for this section that you are only allowed to use the components listed in the Wiring section, along with any of the logic gates you are implementing in CircuitSim. For example, once you implement the NOT gate you are free to use that subcircuit in implementing other logic gates. Implementing the gates in the order of the subcircuit tabs can be the easiest option.

As a brief summary of the behavior of each logic gate:

NAND (Inputs: A, B – Output: OUT)

A B A NAND B

0 0 1

0 1 1

1 0 1

1 1 0

NOR (Inputs: A, B – Output: OUT)

A B A NOR B

0 0 1

0 1 0

1 0 0

1 1 0

AND (Inputs: A, B – Output: OUT)

A B A AND B

0 0 0

0 1 0

1 0 0

1 1 1

OR (Inputs: A, B – Output: OUT)

A B A OR B

0 0 0

0 1 1

1 0 1

1 1 1

NOT (Input: IN – Output: OUT)

A NOT A

0 1

1 0

Hint: Start by creating the NAND and NOT gates from transistors. Then use this gate as a subcircuit for implementing the others.

All of the logic gates must be within their named sub-circuits.

3.3 Part 2: Plexers

ALLOWED COMPONENTS: Wiring Tab, Circuits Tab, and Gates Tab

All of the circuits in this file are in the plexers.sim file.

The multiplexer you will be creating has 8 1-bit inputs (labeled appropriately as A, B, C, …, H), a single 3-bit selection input (SEL), and one 1-bit output (OUT). The multiplexer uses the SEL input to choose a specific input line for forwarding to the output.

For example:

SEL = 000 ==&gt; OUT = A

SEL = 001 ==&gt; OUT = B

SEL = 010 ==&gt; OUT = C

SEL = 011 ==&gt; OUT = D

SEL = 100 ==&gt; OUT = E

SEL = 101 ==&gt; OUT = F

SEL = 110 ==&gt; OUT = G

SEL = 111 ==&gt; OUT = H

The decoder you will be creating has a single 3-bit selection input (SEL), and eight 1-bit output (labeled A, B, C, …, H). The decoder uses the SEL input to raise a specific output line, as seen below.

For example:

SEL = 000 ==&gt; A = 1, BCDEFGH = 0

SEL = 001 ==&gt; B = 1, ACDEFGH = 0

SEL = 010 ==&gt; C = 1, ABDEFGH = 0

SEL = 011 ==&gt; D = 1, ABCEFGH = 0

SEL = 100 ==&gt; E = 1, ABCDFGH = 0

SEL = 101 ==&gt; F = 1, ABCDEGH = 0

SEL = 110 ==&gt; G = 1, ABCDEFH = 0

SEL = 111 ==&gt; H = 1, ABCDEFG = 0

3.4 Part 3: Adders &amp; ALUs

ALLOWED COMPONENTS: Wiring Tab, Circuits Tab, and Gates Tab

3.4.1 1-Bit Adder

The full adder has three 1-bit inputs (A, B, and CIN), and two 1-bit outputs (SUM and COUT). The full adder adds A + B + CIN and places the sum in SUM and the carry-out in COUT.

For example:

A = 0, B = 1, CIN = 0 ==&gt; SUM = 1, COUT = 0

A = 1, B = 0, CIN = 1 ==&gt; SUM = 0, COUT = 1

A = 1, B = 1, CIN = 1 ==&gt; SUM = 1, COUT = 1

Hint: Making a truth table of the inputs will help you.

3.4.2 8-Bit Adder

For this part of the assignment, you will daisy-chain 8 of your 1-bit full adders together in order to make an 8-bit full adder.

This circuit should have two 8-bit inputs (A and B) for the numbers you’re adding, and one 1-bit input for CIN. The reason for the CIN has to do with using the adder for purposes other than adding the two inputs.

There should be one 8-bit output for SUM and one 1-bit output for COUT.

3.4.3 8-Bit ALU

ALLOWED COMPONENTS: Wiring Tab, Ciruits Tab, Gates Tab, and Plexer Tab

You will create an 8-bit ALU with the following operations, using the 8-bit full adder you created in for

2.4.2:

000. Addition [A + B]

001. Subtraction [A – B]

010. Maximum(A, B) max(A, B)

011. MultiplyBy15 [A * 15]

100. isMultipleOf4 [A % 4 == 0]

101. isPowerOf2 [A == 2n for some n∈N, including 20 = 1]

110. isEquals [A == B]

111. isOdd [A % 2 == 1]

Notice that MultiplyBy15, isMultipleOf4, isOdd, and isPowerOf2 only operate on the A input. They should NOT rely on B being a particular value.

For this ALU, we will be using a multiplexer. This ALU has two 8-bit inputs for A and B and one 3-bit input for OP, the op-code for the operation in the list above. It has one 8-bit output named OUT.

For the Maximum(A, B) operation, if the two values are equal, return A.

For the MultiplyBy15 operation, although there is potential for overflow, we don’t need to worry about it in this homework.

For isMultipleOf4 operation, return 00000001 if A is a multiple of 4, and 00000000 otherwise.

The provided autograder will check the op-codes according to the order listed above (Addition (000), Subtraction (001), etc.) and thus it is important that the operations are in this exact order.

Hint: For the Maximum(A, B) operation, think about how you can use a multiplexer for this operation. You can also use previous circuits that you’ve created for the ALU.

Hint 2: To check if a number is a power of two, use the expression (a&gt; 0&amp;&amp;((a&amp;(a− 1)) == 0)) which is easy to implement in digital logic. Don’t forget to check for negative numbers with this operation!

3.5 Running the Autograder

To run the autograder, type the following command into your terminal while in the homework 3 directory:

java -jar hw02-tester.jar

Make sure all the tests have been passed. Keep in mind that even if you get full credit from the autograder, we reserve the right to test for more cases.

4 Deliverables

Please upload the following files onto the assignment on Gradescope:

1. gates.sim NOT, NAND, NOR, AND, OR

2. plexers.sim Decoder, MUX

3. alu.sim 1-Bit Adder, 8-Bit Adder, 8-Bit ALU

5 Sub-Circuit Tutorial

As you build circuits that are more and more sophisticated, you will want to build smaller circuits that you can use multiple times within larger circuits. Sub-circuits behave like classes in Object-Oriented languages. Any changes made in the design of a sub-circuit are automatically reflected wherever it is used. The direction of the IO pins in the sub-circuit correspond to their locations on the representation of the sub-circuit.

To create a sub-circuit:

1. Go to the “Circuits” menu and choose “New circuit”

2. Name your circuit by right-clicking on the “New circuit” item and selecting “Rename”

To use a sub-circuit:

1. Click the “Circuits” tab next to the “Misc” tab

2. Select the circuit you wish to use and place it in your design

6 Rules and Regulations

6.1 General Rules

1. Starting with the assembly homeworks, any code you write must be meaningfully commented. You should comment your code in terms of the algorithm you are implementing; we all know what each line of code does.

3. Please read the assignment in its entirety before asking questions.

5. If you find any problems with the assignment it would be greatly appreciated if you reported them to the author (which can be found at the top of the assignment). Announcements will be posted if the assignment changes.

6.2 Submission Conventions

1. All files you submit for assignments in this course should have your name at the top of the file as a comment for any source code file, and somewhere in the file, near the top, for other files unless otherwise noted.

3. Do not submit compiled files, that is .class files for Java code and .o files for C code. Only submit the files we ask for in the assignment.

4. Do not submit links to files. The autograder does not understand it, and we will not manually grade assignments submitted this way as it is easy to change the files after the submission period ends.

6.3 Submission Guidelines

2. You are also responsible for ensuring that what you turned in is what you meant to turn in. After submitting you should be sure to download your submission into a brand new folder and test if it works. No excuses if you submit the wrong files, what you turn in is what we grade. In addition, your assignment must be turned in via Canvas/Gradescope. Under no circumstances whatsoever we will accept any email submission of an assignment. Note: if you were granted an extension you will still turn in the assignment over Canvas/Gradescope.

6.4 Syllabus Excerpt on Academic Misconduct

Academic misconduct is taken very seriously in this class. Quizzes, timed labs and the final examination are individual work.

Homework assignments are collaborative, In addition many if not all homework assignments will be evaluated via demo or code review. During this evaluation, you will be expected to be able to explain every aspect of your submission. Homework assignments will also be examined using computer programs to find evidence of unauthorized collaboration.

You are expressly forbidden to supply a copy of your homework to another student via electronic means. This includes simply e-mailing it to them so they can look at it. If you supply an electronic copy of your homework to another student and they are charged with copying, you will also be charged. This includes storing your code on any site which would allow other parties to obtain your code such as but not limited to public repositories (Github), pastebin, etc. If you would like to use version control, use github.gatech.edu

6.5 Is collaboration allowed?

Figure 1: Collaboration rules, explained colorfully
