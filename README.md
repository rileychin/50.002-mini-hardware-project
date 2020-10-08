# 50.002-mini-hardware-project
LUC code for Alchitry Labs for Manual &amp; FSM testing of full adder using FPGA 


TO RUN: 
1) Create a new project in Alchitry Lab
2) Import files from src & constraints into your Alchitry Lab project
3) Build au_top.luc and flash into FPGA to run. 

Manual testing: 
Uncomment lines 14-16, 55-64 in au_top.luc, lines 92-94 in constraints.acf
Comment lines 19-21, 68-81 in au_top.luc, lines 97-99 in constraints.acf

FSM testing: 
Uncomment lines 19-21, 68-81 in au_top.luc, lines 97-99 in constraints.acf
Comment lines 14-16, 55-64 in au_top.luc, lines 92-94 in constraints.acf
