---
date: 2024-05-13T12:39
tags: []
---
![[110420241508 - Handshaking 2024-04-16 11.35.36.excalidraw]]
the sequence of events listed shows the 4 possible states that the system can be at any given time.
1. the source unit initiates the transfer by placing the data on the bus and enabling its data valid signal.
2. the data accepted signal is activated by the destinaition unit after it accepts data from the bus
3. the source unit then disables its data valid signal, which invalidates the data on the bus
4. the destination unit then disables its data accepted signal and the system goes into its initial state. 
5. the source does not send the next data item until after the destination unit shows its readiness to accept new data by disabling its data accepted signal.