# Melon-Language
![Melon-Banner](https://user-images.githubusercontent.com/69463173/150173009-32ea2a94-9286-4c27-aeaf-c37dc1d6bdd4.png)

A Simple programming Language made with C#

here the wiki > https://github.com/pradosh-arduino/Melon-Language/wiki

# What's new?
- Changed All symbols to words
- Changed the sytax of programming
- Added a lot more arguments
- Added lot's of commands
- friendly errors, than the old complex exceptions
- More Control with variables (`var, var-def, delete-var, find-var, write-var`)
- Fixed the bug where you can get out of the limit of array length at that point it will throw a `Index was outside the bounds of the array.` error
- bug minor fixes
- many more!

**v2.4.0:**
 - Added a lot of package control
 - Improved stability issues
 - implemented heap with malloc and free
 - small or minor bug fixes
 - improved stability issues
 - many more!

# Syntax
## Console
| Commands | Info |
|----------|------|
|> | move the cursor right by 1 |
|< |   move the cursor left by 1 |
|+ | add the Address that is selected in cursor |
|- |   subtract the Address that is selected in cursor |
|; |   print the Array in the screen |
|compile |  compile the values into a executable file |
|clear |  clears the screen |
|reset |  resets all address |
|run |  loads program into memory or executes some commands |
|run-text |  executes the program in text format |
|write |  writes a custom value into address |
|jump |  jumps to a certain position |
|copy |  copy the address to a specific place |
|if |  check if the address is <your_value> or not |
|calc |  do math |
|var |  save a variable |
|write-var |  write a saved variable to a address that is selected by cursor position |
|read-var |  Read The variables |
|find-var | Find every variables |
|var-def| Prints the lists of vars that is defined |
|import | You can import build in librarys right now availabe are `heap` |
|malloc |  dynamic memory allocation, used with `import <next_line> heap` |
|free | returns back the values to the memory |
|quit/exit |  quit |            

## Script
| Commands | Info |
|----------|------|
|> | move the cursor right by 1 |
|< |   move the cursor left by 1 |
|+ | add the Address that is selected in cursor |
|- |   subtract the Address that is selected in cursor |
|; |   print the Array in the screen |
|clear |  clears the screen |
|reset |  resets all address |
|run-text |  executes the program in text format |
|write |  writes a custom value into address |
|jump |  jumps to a certain position |
|copy |  copy the address to a specific place |
|if |  check if the address is <your_value> or not |
|calc |  do math |
|var |  save a variable |
|write-var |  write a saved variable to a address that is selected by cursor position |
|read-var |  Read The variables |
|find-var | Find every variables |
| goto | goto start to loop infinitly or goto end to end the script much like return in C# |
| sleep | A thread based timer (Milliseconds) |
| import | Import other .mlf to your main.mlf |
|quit |  quit the console with a error code|

# Package System
Now melon has it's own package system called as Citrullus, you can create your own packages too with Citrullus API.

# Setup
After Getting .zip file if you run `Melon_Language.exe` it will not run you need arguments here is the list:
  | Argument | Syntax | IsNeeded |
  |----------|--------|----------|
  |--output-format | --compile-format <your format> | Yes |
  |--output-name | --output-name <your name> | Yes |
  |--output-path | --output-path <your path> | Yes |
  |--program-path | --program-path <your main.mlf path> | Yes |
  |--logging | --logging <true/false> | No |
  |--splash-text | --splash-text <true/false> | No|
  |--updates | --updates <true/false> | No |
  
  If you want definition for the Arguments always use `Melon_Language --help` or if you want to check version use `Melon_Language --version`
  
  You can use `#this#` to get the current directory (only for output path and program path) eg. `--output-path #this#`
  
# Hardware
  *These requirements are not final*
  
  **windows requirements:**
  
  |Software Needed |
  |----------------|
  | none |
    
  | Hardware | Amount |
  |----------|--------|
  |CPU | any |
  | GPU | any |
  | RAM | >256 MB |
  | Storage | any |

  **linux requirements:**
  
  |Software Needed |
  |----------------|
  | none |
  
  | Hardware | Amount |
  |----------|--------|
  |CPU | any |
  | GPU | any |
  | RAM | >256 MB |
  | Storage | any |
  
  **Supported OS:**
  
  | OS name | Version | Arch |
  |---------|---------| -----|
  | Windows | > 10 | x86_64 |
  | Linux | any | x86_64 |
  
