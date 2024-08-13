# Procedure



## Circuit Diagram and Simulation of a Finite State Machine
Here we have design a state machine for a simple combinational lock where the passcode is 4 bit binary number 1001. The state diagram is as follows.


    
<center>
<img src="./images/E9p2.png" style="width:50%">

</center>


The corresponding circuit diagram and simulation has been shown below with the help of D Flip Flop and 4 bit AND gate.


- The D Flip Flop is designed as below:
    - Design Latch circuit and make a component say ‘Latch’.
    <center>
    <img src="./images/Pim1.png" style="width:50%">

    </center>
    - Using the latch, design a D-FF and make a component as shown below.
    <center>
    <img src="./images/Pim2.png" style="width:50%">

    </center>
- 4 input AND gate is designed as below.
<center>
<img src="./images/Pim3.png" style="width:50%">

</center> 

## Circuit and Simulation of the combinational lock is as below


***186: Input, 192: Output***

### State 1: Data: 1111 State: Locked

    
<center>
<img src="./images/E9p3.png" style="width:50%">

</center>


### State 2: Data: 0111 State: Locked
<center>
<img src="./images/E9p4.png" style="width:50%">

</center>

### State 3: Data: 0011 State: Locked
<center>
<img src="./images/E9p5.png" style="width:50%">

</center>

### State 4: Data: 1001 State: Un-Locked
<center>
<img src="./images/E9p6.png" style="width:50%">

</center>

### Step 5: Data: 0100 State: Locked

<center>
<img src="./images/E9p7.png" style="width:50%">

</center>


# Manual
- Refer the simulator manual on how to design the circuit
    - Manual --> [Click Here](./simulation/coavlNew.pdf)

<center>
<embed src="./simulation/coavlNew.pdf" type="application/pdf">
</center>

