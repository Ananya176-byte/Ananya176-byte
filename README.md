TASK-2
TASK WAS ABOUT TO Design a 4bit ALU in NI multisim capable of doing the following operations:-
1. Addition:- Add the binary numbers and display the output in 7-segment display.
2.Subtraction:- Subtract the binary numbers and display the output in 7-segment display.
3.Logical operations like AND, OR and XOR.
SO HERE I STARTED DOING THE CKT FOR THE 4 BIT ADDITION AND SUBTRACTION IN ONE SINGLE CKT BY ADDING A NEW INPUT MODE(M)
THEN I STARTED THINKING ABOUT THE OTHER 3 OPERATIONS AND , OR,XOR.
SO FOR 4 BIT WE NEED TO AND THE SAME BIT OF 2 NO.S AND AFTER DOING IT FOR ALL BITS WE NEED TO WRITE THEM ACCORDING TO THE SIGNIFICANCE SAME STEPS ARE FOR OTHER GATES ALSO.
THEN WE NEED TO SHOW THE VALES OF THE RESULT IN A 7 SEGMENT DISPLAY CKT.
SO WE ALSO HAVE TO PUT IN ONE CONTROL BASED CKT WHERE WE DECIDE THE COMBINATIONS ACCORDING TO WHICH THE TASK WILL BE PERFORMED.
SO THE BEST OPTION WILL BE A MULTIPLEXER AND THEN I TOOK 4 (4:1) MUX  AND SAME SELECTLINES TO ALL 4.
IF WE GIVE THE COMBINATION 00- AND, 01-OR,10-XOR,11-ADD (IF MODE=0), SUBTRACT (IF MODE=1).
THEN WE WILL CONNECT THE RESULTS TO THE 7 SEGMENT DISPLAY ACCORDING TO CONVERSION LOGIT OF THE DISPLAY.
 
