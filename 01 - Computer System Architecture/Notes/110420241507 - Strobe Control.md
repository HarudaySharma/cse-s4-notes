---
date: 2024-04-11T15:06
tags: []
---
In this method a stobe pulse is supplied by one of the unit to indicate to the other unit when the data transfer has to occur

![[11042024 2024-04-11 10.08.21.excalidraw]]*source initiated diagram*

- The strobe control method, of asynchronous data tranfer employs a **single control line for each data transfer**,

a source initiated transfer is shown in the ***block diagram***,

- the data bus carries the binary information from source unit to the destination unit.
- the bus has multiple lines to transfer an entire byte or word.
- the strobe is a single line that informs the destination unit when a valid data is available in the bus.

in the ***timing diagram*** shown 

- the source unit first places the data on the data bus. after a brief delay to ensure that the data settle to a steady value, the source activates the strobe pulse.
- the information on the data bus and the strobe signal remain in the active state for a suffficient period of time to allow the destination unit to recieve the data.
- often the destination unit uses the falling edge of the strobe pulse to transfer the contents of the data bus into one of its internal register
- the source removes the data from the bus a brief period after it disables its strobe pulse