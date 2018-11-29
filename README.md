# alfred_workflows

### 1. Math tools

##### Description:

A set of *useful* and *convenient* math tools.

##### Download:

Go [here](https://github.com/Emrys365/alfred_workflows/blob/master/MathTools/MathTools.alfredworkflow) and download it directly.

#### 1) Simplify fractions

##### Examples:

![image-20181122010814523](MathTools/demo_1.png)

+ `frac .11`  ==>  `.11 = 11 / 100`
+ `frac 4/6`  ==>  `4/6 = 2 / 3`
+ `frac -1.4/2.2`  ==>  `-1.4/2.2 = -7 / 11`

#### 2) Greatest common divisor

##### Examples:

![image-20181122010425254](MathTools/demo_2.png)

#### 3) Least common multiple

##### Examples:

![image-20181122010713899](MathTools/demo_3.png)

#### 4) Simplify surds

##### Examples:

![image-20181122014249233](MathTools/demo_4.png)

- `sqrt .0144`  ==>  `√(.0144) = 3/25 = 0.12`
- `sqrt 4 8/81`  ==>  `³√(8/81) = (2/3) ³√(1/3)`

##### Note:
>  Negative numbers are not supported.

#### 5) Log functions

##### Examples:

![image-20181122014906647](MathTools/demo_5.png)

- `log 5`  ==>  `log₁₀(5) = 0.698970004336`
- `log2 1.0001`  ==>  `log₂(1.0001) = 0.000144262291095`
- `ln e`  ==>  `ln(e) = 1.0`

##### Note: 

> *e=2.718281828...* can be used only in some simple cases, and in most cases it is used as the *scientific notation*.

#### 6) Prime factorization

##### Examples:

![image-20181122015801882](MathTools/demo_6.png)

+ `factor 100`  ==>  `factor(100) = [1, 2, 2, 5, 5]`
+ `factor 31`  ==>  `factor(31) = [1, 31]`

##### Note:

> The maximum value of input integer is limited in case of memory overflow.

#### 7) Permutations and Combinations

##### Examples:

![image-20181122020127840](MathTools/demo_7.png)

+ `C( 4 2`  ==>  `C(4, 2) = 6 `
+ `c( 1000 3`  ==>  `C(1000, 3) = 166167000 `
+ `P( 4 2`  ==>  `P(4, 2) = 12`
+ `p( 1000 3`  ==>  `P(1000, 3) = 997002000 `

##### Note: 

> The maximum value of *m* is limited for both permutations and combinations.

---

### 2. cd

##### Description:

This workflow could help you:
 - open the given path/file in Finder
 - (cmd) reveal the given path/file in Finder
 - (ctrl) open the given path/file in iTerm

It can remember at most MAX_LENGTH history records that you searched before and you can access them again conveniently.

> MAX_LENGTH is a variable that limits the maximum number of records to remember, and you could modify it as you like in the right panel.

##### Download:

Go [here](https://github.com/Emrys365/alfred_workflows/blob/master/cdTool/cd.alfredworkflow) and download it directly.

##### Examples:

+ `cd` + nothing : It will list all the history records.

+ `cd` + `path/file name` : It will open the `path` in Finder or open the `file` directly.

![demo_1](cdTool/demo_1.png)

+ ` cd` + `any string` : It will list all history records that are possibly relevant to the input.

![demo_2](cdTool/demo_2.png)

+ `cd` + `path/file name` & press `command` while selecting an item in the list : 

  It will reveal the `path`/`file` in Finder.

  ![demo_3](cdTool/demo_3.png)

+ `cd` + `path/file name` & press `ctrl` while selecting an item in the list : 

  It will open the `path`/`path of file` in iTerm.

  Note : Please make sure you have installed `iTerm` before you try this !

  ![demo_4](cdTool/demo_4.png)

---

### 3. To be continued

