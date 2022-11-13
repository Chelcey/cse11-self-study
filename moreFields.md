# <span style="color:purple"> **(MORE) FIELDS**</span>

## What is the main point of (More) Fields?
> <span style="color:blue"> not sure right now</span>

### Reading
- [x] 1.1 Programs, Fields
- [ ] 1.2 Java as a Calculator
- [ ] 1.3 Syntax
- [ ] 2.1 Using Fields
- [ ] 2.2 Beyond ints
- [ ] 2.3 Java Checks Types

### Videos
- [ ] Intro to Runnning Programs
- [ ] Syntax Errors
- [ ] Arithmetic
- [ ] Field Access

---

# <span style="color:magenta"> 1.1 Programs, Fields</span>

## To write, tests, and run programs in a language called Java: 
> <span style="color:blue"> We will put a bunch of text into file with the extension `.java`</span>

---
## Given this program:
  ```
  class FirstExample
  {
    int theNumberFive = 5; 
    }
 ```
 
 ---
 
 ## Output:
 
 ```
 Tester Prima v.2.3
-----------------------------------
Tests defined in the class: FirstExample:
---------------------------
FirstExample:
---------------
new FirstExample:1(
 this.theNumberFive = 5)
---------------
No test methods found.
```

### Dissecting the program:
- <span stye="color:red"> FirstExample</span> <span style="color:green"> is the Test defined in the class</span>
- <span stye="color:red"> *The first line*</span> <span style="color:dark green"> is telling us the name of the tool we are using</span>
- <span stye="color:red"> *This output*</span> <span style="color:dark green"> is saying that an **object** was created and it **class** was `FirstExample`</span>
- <span stye="color:red"> *The number after the `:`*</span> <span style="color:dark green"> is a unique identifier for this objecgt which we call its **reference**(no special meaning, jusgt unique to this object)</span>
- <span stye="color:red"> **Reference**</span> <span style="color:dark green"> has a single **field** which we can refer with `this.theNumberFive`, whose value is `5`</span>

| Vocabulary | Description|
| ----------- | ----------- |
| **object** | new FirstExample:1(this.theNumberFive = 5)|
| **reference** | :1 |
| **field value** | 5 |
| **field name** | theNumberFive |
| **class name** | FirstExample |

---

# <span style="color:magenta"> 1.2 Java as a Calculator</span>

## Given this program:
  ```
  class Operators {
  int theAnswer = 5 + (2 * 45);
}
 ```
 
 ---
 
 ## Output:
 
 ```
Tester Prima v.2.3
-----------------------------------
Tests defined in the class: Operators:
---------------------------
Operators:
---------------
new Operators:1(
 this.theAnswer = 95)
---------------
No test methods found.
```

### Dissecting the program:
- <span stye="color:red"> **To calculate the value 95 for field `theAnswer`**</span> <span style="color:dark green"> this code used multiplication (with the `*` operator) and addition (with the `+` operator)</span>
- <span style="color:dark orange">Java correctly processes the order of operations according to the multiplication-before-addition rule. </span>
- <span style="color:dark orange"> Only the resulting value is stored in the field and shown in the output, not the whole program or calculation.</span>
- <span style="color:dark orange"> We can insert parentheses around the part we want to evaluate first </span>

- <span stye="color:red"> *The first line*</span> <span style="color:dark green"> is telling us the name of the tool we are using</span>

> <span style="color:blue"> limit is value that f(x) approaches as input approaches some value</span>
> <span style="color:blue"> The limit of f(x), as x approaches a, is equal to L.</span>
> <span style="color:blue"> means: As x gets closer to a, f(x) gets closer to L.</span>

## Given this program [Operators]
```
class Operators {
  int theAnswer = (5 + 2) * 45;
  int anotherAnswer1 = (5 + 2) - 3 * 9;
  int anotherAnswer2 = ((5+2) -3) * 9;
}
```
---

## Output
```
Tester Prima v.2.3
-----------------------------------
Tests defined in the class: Operators:
---------------------------
Operators:
---------------
new Operators:1(
 this.theAnswer = 315
 this.anotherAnswer1 = -20
 this.anotherAnswer2 = 36)
---------------
No test methods found.
```

### Dissecting the program:
- <span style="color:dark orange"> The programs would still perform the caclulation and output the results just fine even if we picked other field names like `x` or `someReallyLongFieldName` </span>

---
## Not Quite Math Program

```
class NotQuiteMath {
  int theAnswer2 = (5 + 4) / 2;
}
```
---
## Output

```
Tester Prima v.2.3
-----------------------------------
Tests defined in the class: NotQuiteMath:
---------------------------
NotQuiteMath:
---------------
new NotQuiteMath:1(
 this.theAnswer2 = 4)
---------------
No test methods found.
```
---

### Dissecting the program:
- <span style="color:orange"> When dividing `int` values, Java simply *removes* decimal part so that the answer is always an integer. It simply truncates any decimal portion of the number entirely (even if it would be 0.9999) </span>

---

## Negative Results Program 1
```
class NegativeResults {
    int negativeResult = 1 + (-3);
}
```
---
## Output
```
Tester Prima v.2.3
-----------------------------------
Tests defined in the class: NegativeResults:
---------------------------
NegativeResults:
---------------
new NegativeResults:1(
 this.negativeResult = -2)
---------------
No test methods found.
```
---

## Negative Results Program 2
```
class NegativeResults {
    int negativeResult1 = 5/(-3);
    int negativeResult2 = 6/(-3);
}
```
---
## Output
```
Tester Prima v.2.3
-----------------------------------
Tests defined in the class: NegativeResults:
---------------------------
NegativeResults:
---------------
new NegativeResults:1(
 this.negativeResult1 = -1
 this.negativeResult2 = -2)
---------------
No test methods found.
```
---
### Dissecting the program:
- <span style="color:orange red"> Java will simply remove the fractional part for negative `int`s as well </span>


## Why do we need to use (More) Fields for?
> <span style="color:blue"> used to classify algorithms according to run time or space requirements</span>


### [Back to Contents:](https://chelcey.github.io/cse11-self-study/)
