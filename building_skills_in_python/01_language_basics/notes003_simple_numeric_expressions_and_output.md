## Simple Numeric Expressions and Output

### output
- Python 3.0 will replace the irregular print statement with a built-in print()
- ( Side Note ) print function can be imported if desired using "from \_future\_ import print\_function"
- "The print statement takes a list of values and, well, prints them. Speaking strictly, it does two things:"
    - "it converts the objects to strings ..."
    - "puts the characters of those strings on standard output."
- usage as such: 
    - print "string here", variable_here, 102
- a trailing , will combine muliple statements into a single line output
- Redirecting Output
    - how do we send output to system's standard error file?
        - "import sys"
        - redirect using "chevron print" syntax
        - "print >> file, <expression, ...>"
        - "Two common files are sys.stdout and sys.stderr."