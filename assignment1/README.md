## assignment 1
Assignment 1 description

[Repository README link](../README.md)  
[This README link](README.md)  

COde snipped for changing states in the program:
```
 # conditions for changing from START to WAITING and RUN states:
  if program_state == 'START': # or program_state == 'WAITING' or program_state == 'RUN':
    #if input_pin_val == True:
    if input_pin.value() == True: # input pin is high
      set_program_state('WAITING')
    else:
      set_program_state('RUN')
```
Image link example:
![state diagram] (Diagram_JaemoSeong_WEEK3.jpg)

List example
*item1
*item2
*item3

