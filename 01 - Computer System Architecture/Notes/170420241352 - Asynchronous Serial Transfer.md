---
date: 2024-04-17T13:52
tags: []
---
#### Start & Stop Bit
A serial asynchronous data transmission technique used in many interactive terminals **employs** ==special bits that are inserted at both ends of the character code== 
with this technique each character consistes of three (3) parts

1. Start bit
2. Character bits
3. Stop bits

the convention is that the transmitter rests at the 1 when no characters are transmitted.
- the $1_{st}$ bit called the **Start bit**  is always a 0,
	- and is used to indicate beginning of a character.
- the last bit called the **Stop bit** is always a 1,

a transmitted character can be detected by the reciever from knowledge of transmission rules:
1. when the character is not being send the line is kept in one state(high state).
2. the initiation of the character transmission is detected from the start bit which is always 0.
3. the character bits always follow the start bit.
4. after the last bit of the character is transmitted a stop bit is detected when the line returns to the one state for atleast one bit time

>[!example] 
>![[170420241352 - Asynchronous Serial Transfer 2024-04-17 14.02.38.excalidraw]]
>as an example asynchronous serial transmission is shown,
>- each transmitted character consists of a start bit, 8 information bits & 2 stop bits.
>- the terminal has a keyboard and a printer.
