# Code Review Rubric

This document lays out common criteria used to review student code (in order of importance).

| Criterion | Excellent | Good | Adequate | Developing |
|---|---|---|---|---|
| **Correctness** | No errors, program always works correctly and meets the specification(s). | Minor details of the program specification are violated, program functions incorrectly for some inputs. | Significant details of the specification are violated, program often exhibits incorrect behavior. | Program only functions correctly in very limited cases or not at all. |
| **Readability** | No errors, code is clean, understandable, and well-organized. | Minor issues with consistent indentation, use of whitespace, variable naming, or general organization. | At least one major issue with indentation, whitespace, variable names, or organization. | Major problems with at three or four of the readability subcategories. |
| **Code Efficiency** | No errors, code uses the best approach in every case. | N/A | Code uses poorly-chosen approaches in at least one place. | Many things in the code could have been accomplished in an easier, faster, or otherwise better fashion. |
| **Assignment Specifications** | No errors | N/A | Minor details of the assignment specification are violated, such as files named incorrectly or extra instructions slightly misunderstood. | Significant details of the specification are violated, such as extra instructions ignored or entirely misunderstood. |

### Correctness

This is the most important criterion. A program must meet its specifications and function correctly. This means that it behaves as desired, producing the correct output, for a variety of inputs.

### Readability
Code needs to be readable to both you and a knowledgeable third party. This involves:

* Using indentation consistently (e.g., every method's body is indented to the same level)
* Adding whitespace (blank lines, spaces) where appropriate to help separate distinct parts of the code (e.g., space after commas in lists, blank lines between methods or between blocks of related lines within methods, etc.)
* Giving variables meaningful names. Variables named `A`, `B`, and `C` or `foo`, `bar`, and `baz` give the reader no information whatsoever about their purpose or what information they may hold. Names like `principal`, `maximum`, and `counter` are much more useful. Loop variables are a common exception to this idea, and loop variables named `i`, `j`, etc. are okay.
* The code should be well organized. Methods should be defined in one section of the program, code should be organized into methods so that blocks of code that need to be reused are contained within methods to enable that, and methods should have meaningful names.

Please refer to the following style guides for an idea of what 'Excellent' readability might look like:

- [Google HTML/CSS style guide](https://google.github.io/styleguide/htmlcssguide.html)
- [Airbnb JavaScript style guide](https://github.com/airbnb/javascript)

### Code Efficiency
There are often many ways to write a program that meets a particular specification, and several of them are often poor choices. They may be poor choices because they take many more lines of code (and thus your effort and time) than needed, or they may take much more of the computer's time to execute than needed. For example, a certain section of code can be executed ten times by copying and pasting it ten times in a row or by putting it in a simple for loop. The latter is far superior and greatly preferred, not only because it makes it faster to both write the code and read it later, but because it makes it easier for you to change and maintain.

### Assignment Specifications

Assignments will usually contain specifications and/or requirements outside of the programming problems themselves. For example, the way you name your files to submit them to the course website will be specified in the assignment. Other instructions may be included as well, so please read the assignments carefully.
