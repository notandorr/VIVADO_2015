# VIVADO_2015
Labs done in the course **Embedded Logic Design** using Vivado 2015 ver

**LAB 1**

Design a 4:2 Priority encoder on Basys 3

**LAB 2**

Implement a 4-bit adder/subtractor (adds/subtracts two 4-bit inputs)
using the full-adders designed

**LAB 3**

Design and implement a counter on basys3. The counter should continuously count from 0 to 31. The output of the counter can be displayed on the LEDs of basys3 at a rate of 1,2,4 or 8 seconds. The rate is decided by the user(use switched for this task). The counter should be able to clear itself whenever the clear button is pressed.

**LAB 4**
 
 Design a counter that counts from 0 to 255. Display the count on the seven segment display.
o Using a switch select as Up/Down counter. or
o Using a switch, to add pause functionality. (Counter pauses counting)

**LAB 5**

Design a 6 bit up_counter and Display its out count on SSD (Seven Segment Display) using both Internal and External SSD. Display 2 LSB bit on External SSD and 4 MSB bit on Internal SSD

**LAB 6**

Take input from two brams, do the sum and store the bcd output in the FIFO (​using built-in fifo​). One bram coe file will consist of your name letters and other file will contain numbers from 0-9. eg - Take 0 for a, 1 for b .... and so on.
Read the sum value from fifo one by one using push button. Display the output on the on-board ssd.

**LAB 7**

Design and code an FSM to detect an overlapping and non-overlapping sequence of '10101' as either mealy/moore.
a. A switch should be taken as control input to detect overlapping/non-overlapping sequence.

**LAB GCD**

• Write separate Verilog code for the control path.
• Write separate Verilog code for datapath 
• Write top file (name it as gcd_top) 
• Give the input via switches and display the results on 7-segment in BCD format 
• Use 25 MHz clock for gcd and 190Hz clock for led-to-bcd. 

