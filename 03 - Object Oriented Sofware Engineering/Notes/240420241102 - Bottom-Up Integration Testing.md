---
date: 2024-04-24T11:02
tags: []
---
In bottom up integration testing, module at the **lowest level are developed first** and other **modules which go towards the 'main' program** are **integrated** and **tested one at a time**.
 - Bottom up integration also ***uses test drivers*** to drive and pass appropriate data to the lower level modules. 
	 - As and when code for other module gets ready, these drivers are replaced with the actual module.
 - In this approach, **lower level modules are tested extensively** thus **make sure** that **highest used module is tested properly**. 
