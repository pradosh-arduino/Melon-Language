# Melon-Language
![Melon-Banner](https://user-images.githubusercontent.com/69463173/150173009-32ea2a94-9286-4c27-aeaf-c37dc1d6bdd4.png)

A Simple programming Language made with C#

# Both Compiling and Interpreting
Melon Language Supports both compiling AND interpreting

# Syntax

| command | defenition                                                               |                           syntax |
|---------|--------------------------------------------------------------------------|----------------------------------|
|  >   | move the cursor right by 1                                                  |                              > |
|  <   | move the cursor left by 1                                                   |                              < |
|  +   | add the Address that is selected in cursor                                  |                              + |
|  -   | subtract the Address that is selected in cursor                             |                              - |
|  ;   | print the Array in the screen                                               |                              ; |
|  @   | compile the values into a executable file                                   |                              @ |
|  %   | clears the screen                                                           |                              % |
|  $   | resets all address                                                          |                              $ |
|  &   | loads program into memory or executes some commands                         |                              & |
|  ~   | executes the program in text format                                         |                              ~ |
|  *   | writes a custom value into address                                          |                 * "next line " "your value" |
|  \   | jumps to a certain position                                                 |                 \ "next line " "your value" |
|  /   | copy the address to a specific place                                        |                 / "next line " "your value" |
|  ^   | check if the address is <your value> or not                                 |                 ^ "next line " "your value" |
|  ,   | do math                                                                     |                 , "next line " "your value" |
|  `verticle bar`   | save a variable                                                |            `verticle bar`  "next line " "your var name" "next line " "your var value" |
|  #   | write a saved variable to a address that is selected by cursor position     |                 # "next line " "your var name" |
|  :   | Read The variables                                                          |                 : "next line " "your var name" |
|  !   | quit                                                                        |                              ! |
  

# Setup
After Getting .zip file if you run `Melon_Language.exe` it will not run you need arguments here is the list:
  | Argument | Syntax | IsNeeded |
  |----------|--------|----------|
  |--output-format | --compile-format <your format> | Yes |
  |--output-name | --output-name <your name> | Yes |
  |--output-path | --output-path <your path> | Yes |
  |--program-path | --program-path <your main.mlf path> | Yes |
  
  If you want definition for the Arguments always use `Melon_Language --help` or if you want to check version use `Melon_Language --version`
  
  You can use `#this#` to get the current directory (only for output path and program path) eg. `--output-path #this#`
  
# Hardware
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
  
