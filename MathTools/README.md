## Alfred workflow: Math tools

##### Description:

A set of *useful* and *convenient* math tools.

##### Download:

Go [here](https://github.com/Emrys365/alfred_workflows/blob/master/MathTools/MathTools.alfredworkflow) and download it directly.

> NOTE: As of MacOS Monterey 12.3, the builtin Python2 has been removed. You may need to manually install it and change the language interpreter in the Script Filter to an installed Python path.

#### 1) Simplify fractions

##### Examples:

![image-20181122010814523](demo_1.png)

+ `frac .11`  ==>  `.11 = 11 / 100`
+ `frac 4/6`  ==>  `4/6 = 2 / 3`
+ `frac -1.4/2.2`  ==>  `-1.4/2.2 = -7 / 11`

#### 2) Greatest common divisor

##### Examples:

![image-20181122010425254](demo_2.png)

#### 3) Least common multiple

##### Examples:

![image-20181122010713899](demo_3.png)

#### 4) Simplify surds

##### Examples:

![image-20181122014249233](demo_4.png)

- `sqrt .0144`  ==>  `√(.0144) = 3/25 = 0.12`
- `sqrt 3 8/81`  ==>  `³√(8/81) = (2/3) ³√(1/3) = 0.462240849567`

##### Note:
>  Negative numbers are not supported.

#### 5) Log functions

##### Examples:

![image-20181122014906647](demo_5.png)

- `log 5`  ==>  `log₁₀(5) = 0.698970004336`
- `log2 1.0001`  ==>  `log₂(1.0001) = 0.000144262291095`
- `ln e`  ==>  `ln(e) = 1.0`

##### Note: 

> *e=2.718281828...* can be used only in some simple cases, and in most cases it is used as the *scientific notation*.

#### 6) Prime factorization

##### Examples:

![image-20181122015801882](demo_6.png)

+ `factor 100`  ==>  `factor(100) = [1, 2, 2, 5, 5]`
+ `factor 31`  ==>  `factor(31) = [1, 31]`

##### Note:

> The maximum value of input integer is limited in case of memory overflow.

#### 7) Permutations and Combinations

##### Examples:

![image-20181122020127840](demo_7.png)

+ `C( 4 2`  ==>  `C(4, 2) = 6 `
+ `c( 1000 3`  ==>  `C(1000, 3) = 166167000 `
+ `P( 4 2`  ==>  `P(4, 2) = 12`
+ `p( 1000 3`  ==>  `P(1000, 3) = 997002000 `

##### Note: 

> The maximum value of *m* is limited for both permutations and combinations.

#### 8) Base conversion

##### Examples:

![image-20181122020127840](demo_8.png)

+ `num 10`  ==>  `base₂ = 0b1010`; `base₈ = 012`; `base₁₆ = 0xa`
+ `num 0b101` ==> `base₈ = 05`; `base₁₀ = 5`; `base₁₆ = 0x5`
+ `num 077` ==> `base₂ = 0b111111`; `base₁₀ = 63`; `base₁₆ = 0x3f`
+ `num 0o77` ==> `base₂ = 0b111111`; `base₈ = 077`; `base₁₀ = 63`; `base₁₆ = 0x3f`
+ `num 0x24` ==> `base₂ = 0b100100`; `base₈ = 044`; `base₁₀ = 36`

#### 9) Bitwise Calculation

##### Examples:

![image-20181122020127840](demo_9.png)

##### supported operations:

+ `>>` : left shift
+ `<<` : right shift
+ `|` : bitwise OR
+ `&` : bitwise AND
+ `^` : bitwise XOR
+ `~` : bitwise NOT
+ `+` : add
+ `-` : subtract
+ `*` : mulitply
+ `//` : floor divide

#### 10) Time conversion

##### Examples:

![image-20240127202348](demo_10.png)

+ `time 3600`  ==>
  + `seconds(3600) = 3600.0`
  + `minutes(3600) = 60.0`
  + `hours(3600) = 1.0`
  + `days(3600) = 0.041666666666666664`
  + `%day-%H:%M:%S(3600) = 1:00:00`
+ `time 600:10`  ==>
  + `seconds(600:10) = 36010.0`
  + `minutes(600:10) = 600.1666666666666`
  + `hours(600:10) = 10.002777777777778`
  + `days(600:10) = 0.4167824074074074`
  + `%day-%H:%M:%S(600:10) = 10:00:10`
+ `time 1:59:32`  ==>
  + `seconds(1:59:32) = 7172.0`
  + `minutes(1:59:32) = 119.53333333333333`
  + `hours(1:59:32) = 1.9922222222222221`
  + `days(1:59:32) = 0.08300925925925925`
  + `%day-%H:%M:%S(1:59:32) = 1:59:32`
+ `time 5-13:44:32`  ==>
  + `seconds(5-13:44:32) = 481472.0`
  + `minutes(5-13:44:32) = 8024.533333333334`
  + `hours(5-13:44:32) = 133.7422222222222`
  + `days(5-13:44:32) = 5.572592592592593`
  + `%day-%H:%M:%S(5-13:44:32) = 5-13:44:32`
