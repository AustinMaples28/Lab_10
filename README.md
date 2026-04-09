Sequential Circuits: Latches
In this lab, you’ve learned about edge sensitive circuits and explored some of the power therein.

Rubric
Item	Description	Value
Summary Answers	Your writings about what you learned in this lab.	25%
Question 1	Your answers to the question	25%
Question 2	Your answers to the question	25%
Question 3	Your answers to the question	25%
Names
Austin Maples
Madison Hickey
Summary 
In this lab, we explored the difference between level sensitive and edge sensitive sequential circuits.  This lab demonstrated how clocked, edge sensitive memory is the fundamental building block that makes reliable, complex digital systems like counters and computers possible.
Lab Questions
What is difference between edge and level sensitive circuits?
A level sensitive circuit continuously updates its output whenever the enable signal is held high, meaning the output follows the input in real time while enabled. 
Why is it important to declare initial state?
When an FPGA is first programmed, all internal memory elements power on in an unknown, unpredictable state that could be anything. Without an initial begin block setting default values, a circuit like a counter could start counting from a random garbage number rather than zero. 
What do edge sensitive circuits let us build?
Edge sensitive circuits enable the construction of stable feedback-based systems that are impossible with level sensitive logic, the most basic example being a counter. 
