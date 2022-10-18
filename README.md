<p align="center">
  <img
    src="https://user-images.githubusercontent.com/69463173/189360260-98ad7317-ea47-45d9-b547-f527678dcfd4.png"
  >
  <h2 align="center">😉 Simple, 💾 Low Level, 👨‍💻 PPL</h2>
  <h4 align="center">Melon is a simple, low level, procedural programming language (PPL). made for low level control with a interpreter and a compiler<h4>
</p>
  
<p align="center">
  <a href="https://github.com/pradosh-arduino/Melon-Language/releases"><img src="https://img.shields.io/github/downloads/pradosh-arduino/Melon-Language/total?style=flat-square" alt="downloads"></a>
<a href="https://discord.gg/G2zKcAYrxS"><img src="https://img.shields.io/discord/902455221039530004?style=flat-square" alt="discord"></a>
<img src="https://betteruptime.com/status-badges/v1/monitor/ha7i.svg">
<img src="https://img.shields.io/github/last-commit/pradosh-arduino/Melon-Language?style=flat-square" alt="commit">
<img src="https://img.shields.io/github/directory-file-count/pradosh-arduino/Citrullus-Packages?color=%23e85634&label=Citrullus%20Packages&style=flat-square" alt="totat_pkg">
<a href="https://www.reddit.com/r/Melon_Language"><img src="https://img.shields.io/badge/Reddit-r%2FMelon__Language-red?style=flat-square&logo=reddit"></a>
  
#
  
**Melon extensions for vscode**
  
[![e](https://img.shields.io/visual-studio-marketplace/v/Pradosh-S.melon-language?color=green&label=Melon%20Language&style=flat-square&logo=visual-studio-code&logoColor=blue)](https://marketplace.visualstudio.com/items?itemName=Pradosh-S.melon-language)
[![e](https://img.shields.io/visual-studio-marketplace/v/Pradosh-S.melon-code-snippets?color=green&label=Melon%20Code%20Snippets&logo=visual-studio-code&logoColor=blue&style=flat-square)](https://marketplace.visualstudio.com/items?itemName=Pradosh-S.melon-code-snippets)
  
use these to have a better environment while coding in Melon
  
## Console
<details>
  <summary>Click to expand console commands</summary>

|     Commands    |                                                    Info                                                    |           Syntax           |
|-----------------|------------------------------------------------------------------------------------------------------------|----------------------------|
| >               |  move the cursor right by 1                                                                                |  >                         |
| <               |    move the cursor left by 1                                                                               |  <                         |
| +               |  add the Address that is selected in cursor                                                                |  +                         |
| -               |    subtract the Address that is selected in cursor                                                         | -                          |
| ;               |    print the Array in the screen                                                                           | ;                          |
| compile         |   compile the arrays/addresses into a executable file                                                      | compile                    |
| compile-script  |   compile the melon language file to melon language executable                                             | compile-script |
| clear           |   clears the screen                                                                                        | clear                      |
| reset           |   resets all address                                                                                       | reset                      |
| run             |   runs the script                                                                                          | run                        |
| cta             |   prints the addresses in text format                                                                      | cta                        |
| write           |   writes a custom value into address                                                                       |  write \n <value>          |
| copy            |   copy the address to the cursor position                                                                  |  copy \n <value>           |
| if              |   (UNFINISHED) check if the address is <your_value> or not                                                 |                            |
| calc            |   do math                                                                                                  |  calc \n <value>           |
| var             |   save a variable                                                                                          |  var \n <var_name>|
| change-var      |   change variable value                                                                                    |  change-var \n <var_name>|
| delete-var      |   Remove a variable                                                                                        |  delete-var \n <val_name>  |
| delete-all-vars |  Remove All variables                                                                                      |  delete-all-vars           |
| lock-var        |  lock a variable                                                                                           | lock-var \n <name_>           |
| importl         |  Import build in libraries                                                                                 |  importl \n <library_name> |
| load-pkg        |  loads a package                                                                                           |  load-pkg \n <name_>        |
| gen-pkg         |  generates a package with main.mlf                                                                         |  gen-pkg                   |
| fetch-pkg       |  downloads a pkg from [Citrullus Server](https://cdn.jsdelivr.net/gh/pradosh-arduino/Citrullus-Packages/)  |  fetch-pkg \n <name_>       |
|  time           |  shows time it even has like `time.month` to show current month or `time.day` or `time.week` etc           |  time                      |
| quit/exit       |   closes melon                                                                                             |  quit (OR) exit            |
 
### Graphics
 | Commands | Info | Syntax |
 |----------|------|----|
 | println | prints a text then goes to a new line | `println \n "<text>"`
 | printf | prints a text | `printf \n "<text>"`
 | colour | changes console colour | `colour \n <fg>,<bg>`
 | set-cursor-pos | sets cursor pos | `set-cursor-pos \n <x>,<y>`
  
</details>
 
## Script
  <details>
    <summary>Click to expand scripting commands</summary>
    
| Commands | Info | Syntax|
|----------|------|--|
|function| creates a new function | function <name> \n end for calling: <name>~()|
|> | move the cursor right by 1 |>|
|< |   move the cursor left by 1 |<
|+ | add the Address that is selected in cursor |+
|- |   subtract the Address that is selected in cursor |-
|; |   print the Array in the screen |;
|clear |  clears the screen |clear
|reset |  resets all address |reset
|write |  writes a custom value into address |
|jump |  jumps to a line number |
|copy |  copy the address to a specific place |
|if |  check if the address is <your_value> or not |
|calc |  do math |
|write-var |  write a saved variable to a address that is selected by cursor position |
|convert| text to address array |
| goto | goto start to loop infinitly or goto end to end the script much like return in C# |
| sleep | A thread based timer (Milliseconds) |
| importf | Import other .mlf to your main.mlf |
| importl | imports any built-in library |
|for| for loops | for i=1; i-10; i=+1 \n fo-end |
|quit |  quit the console with a error code|

### Graphics
 | Commands | Info |
 |----------|------|
 | println | prints a text then goes to a new line |
 | printf | prints a text |
 
</details>
<h1 align="center">⏳ <strong>Melon's Compiler</strong></h1>
  Melon's compiler is known as neogenic-x or melonnx, which is fast
  
<h1 align="center">📦 <strong>Package System</strong></h1>
  Now melon has it's own package system called as Citrullus API, you can create your own packages too.

<h1 align="center">💻 <strong>Setup</strong></h1>
    
Arguments:
  
|    Arguments    |                                 Comments                                 |
|-----------------|--------------------------------------------------------------------------|
| --output-path   |   The output path of the compiled binary                                 |
| --output-format | The format of the compiled binary, currently supported are bin, hex, mle |
| --output-name   |   The name of the compiled output                                        |
| --program-path  |  the path for your main.mlf                                              |
| --logging       |    Enable Logging                                                        |
| --splash-text   |    Enable splash text                                                    |
| --updates       |    Enable Update check                                                   |
| --clear-logs    |    Clears logs when typing `quit` or `exit`                              |
| --run           |    Runs a script without opening Melon                                   |
| --compile       |    Compiles a script without opening Melon                               |
| --new-project   |    Created a new project for melon                                       |
| --help          |    Display this help screen.                                             |
| --version       |    Display version information.                                          |
  
  You can use `#this#` to get the current directory (only for output path, program path and new project) eg. `--output-path #this#`
  
  <h1 align="center">💽 <strong>Hardware</strong></h1>
  
|   OS    | Version | Hardware Requirements | Architecture |
|------------|--|------------------|--------------|
| 🚪 Windows | 7 to 11|Above 30 MB Memory | x86 x64 ARM  |
| 🐧 Linux   | Any Distribution |Above 30 MB Memory | ❌ x64 ARM  |
| 🍎 OSX     | 10.12 or above |Above 30 MB Memory | ❌ x64 ❌  |
