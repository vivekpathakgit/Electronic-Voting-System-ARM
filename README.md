# Electronic Voting System ARM
## Description: 
This is a voting system for 2 candidates A and B. User can cast vote to A & B via switches 1 & 2 respectively. After each vote, user needs to clear the switches and then can caste vote again. Via switch 3, the user can halt voting and display result. Result will be displayed as A wins!! or B wins!! or Draw! . 

## Interface: 
![image](https://github.com/vivekpathakgit/ElectronicVotingSystemARM/assets/93838914/48cf928d-f680-406e-8945-5d3d53173aa9)
The result will be displayed in JTAG UART and the input of votes and halt command will be operated through Switches.

![image](https://github.com/vivekpathakgit/ElectronicVotingSystemARM/assets/93838914/73b4edf5-ed15-49e0-a883-9be0670c17ec)
An Invalid Input! message will be displayed if the user enters a command beyond the commands in use from the switches. 

## Constrain: 
![image](https://github.com/vivekpathakgit/ElectronicVotingSystemARM/assets/93838914/659b8cdf-fbd0-4804-81c5-90452f22c929)
Nothing will be displayed in JTAG UART at begining of the program, if switches are not clear. User if required to first clear the switches, once done then there is no error in the program.  
