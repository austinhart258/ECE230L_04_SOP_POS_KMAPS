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

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
- Because the actual shape of the map is a donut like shape rather than the 2d usage which is the map

### Why are the names Sum of Products and Products of Sums?
- I am pretty sure its just a name to give the boolean algebra a name and make it more like regular arithmetic

### Open the test.v file – how are we able to check that the signals match using XOR?
- Because of the behavior of XOR which in this case if both inputs match it sets the led = 1 and if they dont match then it sets them to 0 if they are identical using a XOR check basically if led1 or led2 deviate from led0 it throws the fail.

