# GDB Tool
**GDB commands making debugging easier.**


 - to build any system you should include ` -g ` in your command to add debug info within executable file
 - to show code into terminal  write :   `list `
 - to show code into separate terminal  press: ` ctrl + x + a`
 - to put break point at certain line :` b 10 (10 is line number) `
 - to know the breakpoints into file : ` info breakpoints `
 - to get into certain function :` s @ function entry `
 - to make print formate is quite good: `set print pretty on`


## brief of Breakpoints

   ![gdb1](https://github.com/user-attachments/assets/acd362fa-a626-462c-b84a-cf08255c53b6)

## the following command to enhance performance in gdb:
- `run `: to run full code
- `continue` : to execute code from certain point
- to track every change for variable : `use watch + var name`
- to print value of var every command :` display + var name`
- to overwrite value of var: `set var + var-name =20`
- to know protype of any function:` ptype +function name without round bracket`
- to show disassembly of certain function: `disassemble /s d.hello_world`
- to diable mangling of c++ when it comes to disassemble : `set print asm-demangle on`
- to reverse one step :` rn → reverse next`


![gdb2](https://github.com/user-attachments/assets/3affd5d8-0da8-40aa-af6f-ed8f508f0089)
