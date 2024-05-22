#### Serial in Serial Out (SISO)
#### Serial in Parallel Out (SIPO)
#### Parallel in Parallel  Out (PIPO)
#### Parallel in Serial Out (PISO)

| Register | Loading | Reading | Total    |
| :--------: | :-------: | :-------: | :--------: |
| **SISO**     | $n$     | $n - 1$ | $2n - 1$ |
| **SIPO**     | $n$     | $0$     | $n$      |
| **PISO**     | $1$     | $n - 1$ | $n$      |
| **PIPO**     | $1$     | $0$     | $1$      |
