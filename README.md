# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Name Carson Rasmussen & Jonibek Utaev (Group 55)

## Lab Summary
In this lab it was a bit more hands on as we had to code our top file, uncomment our constraints,
write our circuit a and b code. Overall, we learned how to assemble our own Verilog modules, how constraint file maps
inputs and outputs to pins on the FGPA

## Lab Questions

### 1 - Explain the role of the Top Level file.
It connects the circuits together, a and b, to each other and to the switches.

### 2 - Explain the function of the Constraints file.
The purpose of the constraints file is how the synthesizer maps to the hardware so it knows how to wire things up.

### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?

Yes the selection of our Minterm and Maxterm where correct for each circuit. Our SOP (~C & ~D) | (A & B) | (B & ~D)
and our POS (D) & (~A) was the most simplified version. This is what I would've chosen.
