---
date: 2024-05-13T14:38
tags:
---
1. $E = a_b\times(KLOC)^{b_b}$
2. $Time = c_b\times(Effort)^{d_b}$
3. $Person\; required = \frac{E}{D}$

*where*
$E=Effort\;applied\;in\;person\: /\:months$
$D=Development\;time\;in\;months(Schedule)$
$KLOC/KDSI=Estimated\;Lines\;of\;Code(in\;thousands)$
$P=No.\;of\;people\;required$
${a_b,\: b_b,\: c_b,\: d_b}\; are \;coefficients$

The above formula is used for the cost estimation of the basic COCOMO model and also is used in the subsequent models. The constant values a, b, c, and d for the Basic Model for the different categories of the system:

| Software Projects |  a  |  b   |  c  |  d   |
|:-----------------:|:---:|:----:|:---:|:----:|
|      Organic      | 2.4 | 1.05 | 2.5 | 0.38 |
|   Semi-Detached   | 3.0 | 1.12 | 2.5 | 0.35 |
|     Embedded      | 3.6 | 1.20 | 2.5 | 0.32 |

- The effort is measured in Person-Months and as evident from the formula is dependent on Kilo-Lines of code. The development time is measured in months.
- These formulas are used as such in the Basic Model calculations, as not much consideration of different factors such as reliability, and expertise is taken into account, henceforth the estimate is rough.

![[Drawing 2024-05-27 14.43.29.excalidraw]]