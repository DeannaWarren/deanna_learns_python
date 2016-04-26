# Building Skills In Python - Language Basics

## Background and History

### History
- "a relatively simple programming language that includes a rich set of supporting libraries ... keeps the language simple and reliable, while providing specialized feature sets as separate extensions"
-  "is implemented in C, and relies on the extensive, well understood, portable C libraries"
-  "created in 1991"

### Features of Python 
- Object Oriented Language 
- dynamic not statically compiled language 
- "full access to OS services"
- shell scripting language

### Comparisons -- The Java Yardstick
- Simple and Familiar 
    - "  It relies on a few core data structures and statements "
- Object Oriented
    - single and multiple inheritence
- Secure
    - precompiled modules can be distributed to prevent alterations
    - builtin import function can be supplemented
    - no " buffer overflow " problem
    - dynamic: features like exec or eval can introduce problems, but are easy to identify
- Interperted
    - simpler edit-execute cycle vs compiled language's edit-compile-link-execute
    - interperter can be run interactively ??
    - interperter can, again, be extended with modules
- Dynamic
- Portable
    - rests on a portable C source
    - "OS inconsistency makes it imposible to provide perfect portability"
- Robust
    - "errors are raised as exceptions"
    - " mistakes lead to simple, easy-to-interpret error messages"
- Multithreaded
    - ((... it is definitely time to learn more about multithreaded stuff ))
- Garbage Collection
    - "The Python run-time environment handles garbage collection of all Python objects. Reference counters are used to assure that no live objects are removed. When objects go out of scope, they are eligible for garbage collection"
-  Exceptions
    - try statment to handle exceptions
    - exceptions raised in a uniform way
- High Performance 
    - "The Python interpreter is quite fast. However, where necessary, a class or module that is a bottleneck can be rewritten in C or C++, creating an extension to the runtime environment that improves performance."

## Getting Started
### Command Line Interaction
- Starting and Stopping CL Python
    - terminal instructions
    - type python to begin
    - type Control-D to end
- each statement is evaluated when entered
- a long statement can be broken into multiple lines using an escape character(\\)

### The IDLE Dev Environment
- come back to this later (using a cloud IDE now)

### Script Mode
- print #comma seperated values and strings here
- running a script
    - Explicit Command Line Execution
        - python example1.py 
    - Implicitly from the Command Line
        - more complicated
    - Manually from within the IDLE
        - explore this more when exploring IDLE

### Getting Help
- submit help() in the REPL for interactive utility
- submit help(object) for specific help

### Syntax Formalities
- Following is QUOTED
    - Simple statements must be complete on a single Logical Line....  we’ll look at compound statements, which have indented suites of statements, and which span multiple Logical Lines. The rest of these rules will define how Logical Lines are built from Physical Lines through a few Line Joining rules.
    - Physical Lines are defined by the platform; they’ll end in standard n or the Windows ASCII CR LF sequence ( \r\n ).
    - Comments start with the # character outside a quoted string; comments end at the end of the physical line. These are not part of a statement; they may occur on a line by themselves or at the end of a statement.
    - Coding-Scheme Comments. Special comments that are by VIM or EMACS can be included in the first or second line of a Python file. 
    - Explicit Line Joining. A \ at the end of a physical line joins it to the next physical line to make a logical line. This escapes the usual meaning of the line end sequence. The two or three-character sequences ( \n or \r\n ) are treated as a single space.
    - Implicit Line Joining. Expressions with ()‘s, []‘s or {}‘s can be split into multiple physical lines.
    - Blank Lines. When entering statements interactively, an extra blank line is treated as the end of an indented block in a compound statement. Otherwise, blank lines have no signficance.
    - Indentation. The embedded suite of statements in a compound statement must be indented by a consistent number of spaces or tabs. When entering statements interactively or in an editor that knows Python syntax (like IDLE), the indentation will happen automatically; you will outdent by typing a single backspace. When using another text editor, you will be most successful if you configure your editor to use four spaces in place of a tab. This gives your programs a consisent look and makes them portable among a wide variety of editors.
    - Whitespace at the beginning of a line is part of indentation, and is significant. Whitespace elsewhere within a line is not significant. Feel free to space things out so that they read more like English and less like computer-ese.
- END QUOTE

### Excercises 
- " Print Script. Create and run Python file with commands like the following examples: "
    - example1.py
- " Another Simple Print Script. Create and run a Python file with commands like the following examples "
    - example2.py
- "Numeric Types. Compare the results of 22/7 and 22.0/7. Explain the differences in the output."
    - Integer vs Float division a la Ruby

### Style Notes
- considerably flexible
- guidelines taken from PEP8

- Case Sensitive
- makes use of indentation (very important)
- file names => letters, digits, _ 
- file names => ending is .py 