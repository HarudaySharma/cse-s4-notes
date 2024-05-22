###### *design of hardwired control unit*
![[Timing and Control 2024-05-19 12.43.33.excalidraw]]

>[!note] **explanation**
>- Firstly, CPU will read the instructions from memory. All these instructions are stored in the instruction register. The size of the instruction register is 16 bits (0 to 15). 
>- The first 12 bits of the instruction register (0 to 11) specify the address of the operand, the next 3 bits (12 to 14) specify the opcode, and the last bit (15th bit) specify the indirect bit. 
>- Opcode specifies the operations to be performed. As the opcode size is 3 bits, we can perform 2³(=8) operations. 
>- We have to decode these bits using a decoder to perform all these operations. 
>- Since opcode is of 3 bits, those 3 bits are passed as input to a decoder, and hence we use a 3X8 decoder and get 8 outputs. 
>- All these outputs, along with the address and the indirect bit, are passed to control unit gates. 
>- Say if we get our input as 001 and let’s say that it contains the ADD operation, the output D1 from the decoder will become active and control logic gates will perform that. 
>- Next, we have a Sequence Counter of size 4 bits. Since the size is 4 bits, we will have 2⁴(=15) timing signals ranging from 0 to 15. 
>- 4 bits sequence counter will be decoded using a decoder. Since the size of SC is 4 bits, a 4X16 decoder is used, and all the outputs of the decoder (from T0 to T15) are given as input to control logic gates. 
>- Sequence Counter accepts 3 control inputs, namely, increment(INR), clear(CLR), and clock. 
>- Whenever the clock bus and increment control unit is enabled, we can only perform some operation on the sequence counter. 
>- Enabling clear input makes the counter start from the beginning.
