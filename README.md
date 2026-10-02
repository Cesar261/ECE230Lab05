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

## Name Rafael and Cesar

## Lab Summary
This lab focuses on implementing digital logic circuits in Verilog using standard Canonical forms (Maxterms/POS for Circuit A and Minterms/SOP for Circuit B). It then demonstrates hierarchical module design by connecting the output of Circuit A into Circuit B within a top-level module to test on the Basys3 board.

## Lab Questions

### 1 - Explain the role of the Top Level file.
The top level file serves as a central structural manager for the whole system design. it instantiates submodules and defines how the data flows. It also is how we get external inputs and outputs to the board
### 2 - Explain the function of the Constraints file.
This file maps the Verilog ports to the actual physical components on the board
### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?
Yes the selection was right for each circuit if we were trying to minimize logic terms We would've chosen the same thing
