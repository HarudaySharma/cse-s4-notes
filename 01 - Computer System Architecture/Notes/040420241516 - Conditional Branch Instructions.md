---
date: 2024-04-04T15:16
tags: []
---
| Mnemonic |   Branch Condition    | Tested Condition | Description                                                                                     |
| :------: | :-------------------: | :--------------: | ----------------------------------------------------------------------------------------------- |
|    BZ    |    Branch if zero     |     [Z = 1]      | Branch if the zero flag is set (previous operation resulted in zero)                            |
|   BNZ    |  Branch if not zero   |     [Z = 0]      | Branch if the zero flag is cleared (previous operation did not result in zero)                  |
|    BC    |    Branch if carry    |     [C = 1]      | Branch if the carry flag is set (previous addition resulted in a carry)                         |
|   BNC    |  Branch if no carry   |     [C = 0]      | Branch if the carry flag is cleared (previous addition did not result in a carry)               |
|    BP    |    Branch if plus     |     [S = 0]      | Branch if the sign flag is cleared (previous result is positive)                                |
|    BM    |    Branch if minus    |     [S = 1]      | Branch if the sign flag is set (previous result is negative)                                    |
|    BV    |  Branch if overflow   |     [V = 1]      | Branch if the overflow flag is set (signed addition/subtraction resulted in overflow)           |
|   BNV    | Branch if no overflow |     [V = 0]      | Branch if the overflow flag is cleared (signed addition/subtraction did not result in overflow) |

*Unsigned compare conditions(A - B)*

| Mnemonic |     Branch Condition      | Tested Condition | Description                                                                                             |
| :------: | :-----------------------: | :--------------: | ------------------------------------------------------------------------------------------------------- |
|   BHI    |     Branch if higher      |     [A > B]      | Branch if the unsigned value in register A is greater than the unsigned value in register B             |
|   BHE    | Branch if higher or equal |     [A ≥ B]      | Branch if the unsigned value in register A is greater than or equal to the unsigned value in register B |
|   BLO    |      Branch if lower      |     [A < B]      | Branch if the unsigned value in register A is less than the unsigned value in register B                |
|   BLOE   | Branch if lower or equal  |     [A ≤ B]      | Branch if the unsigned value in register A is less than or equal to the unsigned value in register B    |
|    BE    |      Branch if equal      |     [A = B]      | Branch if the unsigned value in register A is equal to the unsigned value in register B                 |
|   BNE    |    Branch if not equal    |     [A ≠ B]      | Branch if the unsigned value in register A is not equal to the unsigned value in register B             |

*Signed compare conditions*

| Mnemonic |      Branch Condition      | Tested Condition | Description                                                                                         |
| :------: | :------------------------: | :--------------: | --------------------------------------------------------------------------------------------------- |
|   BGT    |   Branch if greater than   |     [A > B]      | Branch if the signed value in register A is greater than the signed value in register B             |
|   BGE    | Branch if greater or equal |     [A ≥ B]      | Branch if the signed value in register A is greater than or equal to the signed value in register B |
|   BLT    |    Branch if less than     |     [A < B]      | Branch if the signed value in register A is less than the signed value in register B                |
|   BLE    |  Branch if less or equal   |     [A ≤ B]      | Branch if the signed value in register A is less than or equal to the signed value in register B    |
