---
date: 2024-04-01T11:49
tags: []
---
*A bus organization for cpu registers is shown.*
![[010420241149 - General Registers Organization in CPU 2024-05-19 12.34.08.excalidraw]]

- The output of each register is connected to *2* multiplexers to form two buses **A** & **B**
- The selection lines in each multiplexer selects one register
	- for the input data for the particular bus 
- The **A** & **B** buses form the inputs to a common ALU
- The operations selected in the ALU determines the arithmitic or logic operation that is to be performed. 
- The result of the micro operation is available for output data and also goes into the inputs of all registers.
- The register that receives information from the output bus is selected by a decoder. 
	- The decoder activates one of the register load input .thus, providing a transfer path b.w. the data in the output bus and the input of selected destination register.

- The control unit that operates the CPU bus system directs the information flow through the regsiters and ALU by selecting the various components in the system
- For example, to perform the operation R1 <- R2 + R3
- The control must provide binary selection variables of the following selector inputs:
	1. MUX A selector (SELA): to place the content of R2 into bus A.
	2. MUX B selector (SELA): to place the content of R3 into bus B.
	3. ALU operation selector (OPR): to provide the arithmetic addition A + B,
	4. Decoder destination selector (SELD): to transfer the content of the output bus into R1.
- The four control selection varibales are generated in the control unit and must be available at the beginning of a clock cycle.