Names: Anthony Ducharme & Irma Smajlovic (Team 28) 
# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

Summarize your learnings from the lab here.

We learned how to make K-Maps using 4 variables. We learned how to create optimized POS and SOP equations from those K-Maps. Finally we learned how to implement them with Verilog on the Basys-3 board.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?

Because K-Maps can wrap cylidrically so there is only one variable changing across edges. K-Maps are a 2d visual of a 3d model.

### Why are the names Sum of Products and Products of Sums?

It's called SOP because we use AND gates to get all the products that result in 1 and then we sum them using OR gates. As for POS it's because we use OR gates to get all the sums that result in 0 and then we multiply them using AND gates.

### Open the test.v file – how are we able to check that the signals match using XOR?

An XOR gate returns 1 if the inputs are different and a 0 if the inputs are the same. In the code we say that if XOR returns 1 the if statement is executed because 1 does not equal 0, and if the XOR returns a 0 the if statement doesnt execute because 0 equals 0.
