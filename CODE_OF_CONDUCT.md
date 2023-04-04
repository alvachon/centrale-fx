# CODE OF CONDUCT

## Coding Convention

### Denomination

s_ = structure \
t_ = typedef \
u_ = union \
e_ = enum \
g_ = global name

* When declaring a struct, union or enum with a typedef, all indentation rules apply.
* You must align the typedef's name with the struct/union/enum's name.
* You must indent all structures' names on the same column for their scope.
* You cannot declare a structure in a .cc file (Do it in the .h file)

### ASCII only (for now)

Variable = lowercase, digits, _, snake case (this_is_snake_case), English, mnemonic \
Function = lowercase, digits, _, snake case (this_is_snake_case), English, mnemonic \
Files = lowercase, digits, _, mnemonic \
Directories = lowercase, digits, _, mnemonic \
Macros, Types, Other... = snake case (this_is_snake_case), English, mnemonic

- - - -

Global Variable : const AND static obliged, declaration and initialization same line. \
Static Variable : declaration and initialization same line. \
Constant : declaration and initialization same line.
- - -

### Formating

^^^^ = indent code w/ 4-space tabulations \
25 = lines by function, not counting curly bracket {} \
80 = columns wide \
NEWLINE = Separate each function, empty (no tab, no space)

You may add a new line after an instruction or control structure, but you’ll have
to add an indentation with brackets or assignment operator. 

Operators must be atthe beginning of a line.

Comment or Instruction = right above the function, one per line, \
END OF LINE = no space, no tab \
SPACE = no double, even in operator \
cc keyword = must have 1 space unless types(int, char, float, etc) and sizeof \
Variable = same column as the scope, 1 per line \
Pointers = *before the name's variable, not after the type. \
Declaration = Must be declared at the start of the function \
Assignement = multiple autorized \
CONTROL STRUCT (if, while. . .) = (), unless they contain a single line or condition.

- - - 

### Functions

4 parameters max \
5 variable declaration max per function \
no arguments = (void) \
Parameters in function's must be named \
Empty line each function \
Return function need to be in ())function must have 1 tab (^) between type and its name

- - - 

### Comments

 Comments can be inside functions' bodies.  \
 Comments must be on their own line \
 Your comments must be in English. And they must be useful. \
 A comment cannot justify a "bastard" function.

- - - 

### Varia
 Cannot include a .cc file \
 No more than 5 function in a .cc file
