# 🍉 Melon-Language
![ml-banner](https://user-images.githubusercontent.com/69463173/158062823-ea321f58-0fdc-44f0-a3c2-143848e7f8f0.png)

![citrullus-banner](https://user-images.githubusercontent.com/69463173/158047253-6a384476-cfdf-42b4-8f02-5e00ab1d4405.png)

![Capture](https://user-images.githubusercontent.com/69463173/158023102-2538ad2a-c541-49e4-b448-c6b4b1d7bfd0.PNG)

[![downloads](https://img.shields.io/github/downloads/pradosh-arduino/Melon-Language/total?style=flat-square)](https://github.com/pradosh-arduino/Melon-Language/releases)
[![discord](https://img.shields.io/discord/902455221039530004?style=flat-square)](https://discord.gg/ChP4RMgcKG)
[![issues](https://img.shields.io/github/issues/pradosh-arduino/Melon-Language?style=flat-square)](https://github.com/pradosh-arduino/Melon-Language/issues)
[![license](https://img.shields.io/badge/License-MIT-orange?style=flat-square)](https://github.com/pradosh-arduino/Melon-Language/blob/main/LICENSE)
![pkg-size](https://img.shields.io/github/repo-size/pradosh-arduino/Citrullus-Packages?label=Citrullus%20Packages%20Size&style=flat-square)
![uptime](https://img.shields.io/uptimerobot/ratio/m790982313-6e394aca6d9e2adb44b814f0?style=flat-square)
![isUp](https://img.shields.io/uptimerobot/status/m790982313-6e394aca6d9e2adb44b814f0?style=flat-square)

**NOTE:** It's Recommmended to use VSCode terminal or Windows Terminal

*no pull request are accepted*

# Syntax
## Console
<details>
  <summary>Click to expand console commands</summary>
  
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
|run |  runs the script |
|run-text |  executes the addresses in text format |
|write |  writes a custom value into address |
|jump |  jumps to a certain position |
|copy |  copy the address to a specific place |
|if |  check if the address is <your_value> or not |
|calc |  do math |
|var |  save a variable |
|write-var |  write a saved variable to a address that is selected by cursor position |
|read-var |  Read The variables |
|var-def| Prints the lists of vars that is defined |
|import | You can import build in librarys |
|load-pkg | loads a package |
|gen-pkg | generates a package with main.mlf |
|fetch-pkg | downloads a pkg from [Citrullus Server](https://cdn.jsdelivr.net/gh/pradosh-arduino/Citrullus-Packages/) |
| time | showns time it even has like `time.month` to show current month or `time.day` or `time.week` etc|
|quit/exit |  closes melon |
  
### Heap
 | Commands | Info |
 |----------|------|
 |~malloc~ |  ~dynamic memory allocation, used with `import <next_line> heap`~ |
 |~free~ | ~returns back the values to the memory~ |
  
 **going to get removed**
 
### Graphics
 | Commands | Info |
 |----------|------|
 | println | prints a text then goes to a new line |
 | printf | prints a text |
 | colour | changes console colour |
 | set-cursor-pos | sets cursor pos |
  
</details>
 
## Script
  <details>
    <summary>Click to expand scripting commands</summary>
    
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
| importf | Import other .mlf to your main.mlf |
| importl | imports any built-in library |
|quit |  quit the console with a error code|

### Graphics
 | Commands | Info |
 |----------|------|
 | println | prints a text then goes to a new line |
 | printf | prints a text |
 
</details>
  
# 📦 Package System
Now melon has it's own package system called as Citrullus, you can create your own packages too with Citrullus API.

# 👨‍💻 Setup
After Getting .zip file if you run `Melon Language.exe` it will not run you need arguments here is the list:
  | Argument | Syntax | Is Needed |
  |----------|--------|----------|
  |--output-format | --output-format <your format> | Yes |
  |--output-name | --output-name <your name> | Yes |
  |--output-path | --output-path <your path> | Yes |
  |--program-path | --program-path <your main.mlf path> | Yes |
  |--logging | --logging <true/false> | No |
  |--splash-text | --splash-text <true/false> | No|
  |--updates | --updates <true/false> | No |
  |--clear-logs | --clear-logs <true/false> | No |
  
  If you want definition for the Arguments always use `Melon_Language --help` or if you want to check version use `Melon_Language --version`
  
  You can use `#this#` to get the current directory (only for output path and program path) eg. `--output-path #this#`
  
# Hardware
  ## windows requirements:
  
  |Software Needed |
  |----------------|
  | C# Runtime Library |
    
  | Hardware | Amount |
  |----------|--------|
  |CPU | any |
  | GPU | any |
  | RAM | >50 MB |
  | Storage | any |

  ## linux requirements:
  
  |Software Needed |
  |----------------|
  | C# Runtime Library |
  
  | Hardware | Amount |
  |----------|--------|
  |CPU | any |
  | GPU | any |
  | RAM | >50 MB |
  | Storage | any |
  
  ## Supported OS:
  
  | OS name | Version | Arch |
  |---------|---------| -----|
  | Windows | > 10 | x86_64 |
  | Linux | any | x86_64 |
  
 # 💖 Feedback
 [![Feedback](https://img.shields.io/badge/Feedback-Github-green?style=flat-square)](https://gist.github.com/pradosh-arduino/4bf93fbf971f583c4d946282dac60e32)
 
