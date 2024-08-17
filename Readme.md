For  each `p` defined as the a random seed, a factible seed `s` is found as :
```
s = 2502505 + 100 (p - 1).
```
Formula taken from [Bischoff and Ratcliff, 1995].

In this work, from [Karabulut and Inceo Inceoglu, 2004], the problems: P1A2, P2A2, P3A2, P4A2, P5A2 are chosen to create data. 

```
p = [1,...,100]
```

The line for each box type contains 8 numbers:     

1. Box type i,

2. Number of boxes of type i,

3. 0/1 indicator,

3. Box length ,

5. 0/1 indicator,

6. Box width ,

7. 0/1 indicator,

8. Box height.


NOTE: Before each box dimension the 0/1 indicates whether placement in the vertical orientation is permissible (=1) or not (=0)

Example: 
| Number of instances    | Number of boxes |
| -------- | ------- |
| 100  | 25   |

| Seed for "p" or problem number   | p value  |
| -------- | ------- |
| 1  | 2502505   |

| Container length   | Container width  | Container height  |
| -------- | ------- | ------- |
| 50  | 50   | 50   |

| Number of types of boxes   | 
| -------- |
| 23  |

| Type   | Number of typed boxes  |  X 0/1 indicator  | Length | Y 0/1 indicator  | Width | Z 0/1 indicator  | Height |
| -------- | ------- | -------- | ------- | -------- | ------- | -------- | ------- |
| 1 | 1 | 1 | 50 | 1 | 18 | 1 | 11 |
| 2 | 1 | 1 | 50 | 1 | 18 | 1 | 39 |
| 3 | 1 | 1 | 7 | 1 | 32 | 1 | 33 |
| ... | ... | ... | ... | ... | ... | ... | ... |
|23 | 1 | 1 | 3 | 1 | 2 | 1 | 1|

References:

[Karabulut and Inceo Inceoglu, 2004]
Karabulut, K. and ˙Inceo ˘glu, M. M. (2004). A hybrid genetic algorithm for packing in 3d with deepest
bottom left with fill method. In International Conference on Advances in Information Systems,
pages 441–450. Springer

[Bischoff and Ratcliff, 1995]
Bischoff, E. E. and Ratcliff, M. (1995). Issues in the development of approaches to container
loading. Omega, 23(4):377–390.


