# **Robot Framework Guidelines**
https://www.mono-project.com/community/contributing/coding-guidelines/#file-headers  
Style Guidelines  
Indentation  
Performance and Readability  
Where to put spaces  
Where to put braces  
Multiline Parameters  
Use whitespace for clarity  
File headers  
Multiline comments  
Casing  
Line length and alignment  
Initializing Instances  
Baroque Coding  
Warnings  
Conditional compilation  
Missing Implementation Bits  
NotImplementedException  
Use Simple Identifiers  
Examples  
Source Code Control  
Summary Description  
Best Practices  
Documentation  
Check all arguments  
Be careful about freeing memory  
[Focus on code readability](#head1234)

## **Some of the coding standards are given below:**

1. Limited use of globals:
These rules tell about which types of data that can be declared global and the data that can’t be.


2. Standard headers for different modules:
For better understanding and maintenance of the code, the header of different modules should follow some standard format and information. The header format must contain below things that is being used in various companies:
Name of the module
Date of module creation
Author of the module
Modification history
Synopsis of the module about what the module does
Different functions supported in the module along with their input output parameters
Global variables accessed or modified by the module


3. Naming conventions for local variables, global variables, constants and functions:
Some of the naming conventions are given below:
Meaningful and understandable variables name helps anyone to understand the reason of using it.
Local variables should be named using camel case lettering starting with small letter (e.g. localData) whereas Global variables names should start with a capital letter (e.g. GlobalData). Constant names should be formed using capital letters only (e.g. CONSDATA).
It is better to avoid the use of digits in variable names.
The names of the function should be written in camel case starting with small letters.
The name of the function must describe the reason of using the function clearly and briefly.


4. Indentation:
Proper indentation is very important to increase the readability of the code. For making the code readable, programmers should use White spaces properly. Some of the spacing conventions are given below:
There must be a space after giving a comma between two function arguments.
Each nested block should be properly indented and spaced.
Proper Indentation should be there at the beginning and at the end of each block in the program.
All braces should start from a new line and the code following the end of braces also start from a new line.


5. Error return values and exception handling conventions:
All functions that encountering an error condition should either return a 0 or 1 for simplifying the debugging.
On the other hand, Coding guidelines give some general suggestions regarding the coding style that to be followed for the betterment of understandability and readability of the code. Some of the coding guidelines are given below :



6. Avoid using a coding style that is too difficult to understand:
Code should be easily understandable. The complex code makes maintenance and debugging difficult and expensive.


7. Avoid using an identifier for multiple purposes:
Each variable should be given a descriptive and meaningful name indicating the reason behind using it. This is not possible if an identifier is used for multiple purposes and thus it can lead to confusion to the reader. Moreover, it leads to more difficulty during future enhancements.


8. Code should be well documented:
The code should be properly commented for understanding easily. Comments regarding the statements increase the understandability of the code.


9. Length of functions should not be very large:
Lengthy functions are very difficult to understand. That’s why functions should be small enough to carry out small work and lengthy functions should be broken into small ones for completing small tasks.


10. Try not to use GOTO statement:
GOTO statement makes the program unstructured, thus it reduces the understandability of the program and also debugging becomes difficult.


## **Advantages of Coding Guidelines:**

Coding guidelines increase the efficiency of the software and reduces the development time.
Coding guidelines help in detecting errors in the early phases, so it helps to reduce the extra cost incurred by the software project.
If coding guidelines are maintained properly, then the software code increases readability and understandability thus it reduces the complexity of the code.
It reduces the hidden cost for developing the software.


## <a name="head1234"></a> **Focus on code readability**  
Readable code is easy to follow, optimizes space and time. Here are a few ways to achieve that:

- Write as few lines as possible.
- Use appropriate naming conventions.
- Segment blocks of code in the same section into paragraphs.
- Use indentation to marks the beginning and end of control structures. Clearly specify the code between them.
- Don’t use lengthy functions. Ideally, a single function should carry out a single task.
- Use the DRY (Don’t Repeat Yourself) principle. Automate repetitive tasks whenever necessary. The same piece of code should not be repeated in  the script.
- Avoid Deep Nesting. Too many nesting levels make code harder to read and follow.
- Capitalize SQL special words and function names to distinguish them from table and column names.
- Avoid long lines. It is easier for humans to read blocks of lines that are horizontally short and vertically long.- 