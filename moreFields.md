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

## Given this program:
  ```
  class FirstExample
  {
    int theNumberFive = 5; 
    }
 ```
 
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
- <span stye="color:red"> **FirstExample**</span> <span style="color:dark green"> is the Test defined in the class</span>
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
  int theAnswer = (5 + 2) * 45;
}
 ```
 
 ## Output:
 
 ```
Tester Prima v.2.3
-----------------------------------
Tests defined in the class: Operators:
---------------------------
Operators:
---------------
new Operators:1(
 this.theAnswer = 315)
---------------
No test methods found.
```


> <span style="color:blue"> limit is value that f(x) approaches as input approaches some value</span>
> <span style="color:blue"> The limit of f(x), as x approaches a, is equal to L.</span>
> <span style="color:blue"> means: As x gets closer to a, f(x) gets closer to L.</span>

## Why do we need to use Big O for?
> <span style="color:blue"> used to classify algorithms according to run time or space requirements</span>

## Why do we need to classify algorithms according to run time or space requirements?
> <span style="color:blue"> Knowing how the algorithm works efficiently can add value to the way we do programming</span>
> <span style="color:blue"> Can make the program behave in required optimal conditions</span>

## What does optimal conditions means? 
> <span style="color:blue"> best level or state that it could achieve</span>

https://www.freecodecamp.org/news/all-you-need-to-know-about-big-o-notation-to-crack-your-next-coding-interview-9d575e7eec4/

### [Back to Contents:](https://chelcey.github.io/cse11-self-study/)
