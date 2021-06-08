# RealMode-x86-asm-QEMU-Debugger
A debugger for assembly x86 code runing in Real Mode (tested inside QEMU)

## How to use
1. install dependencies --> pip install -r requirements.txt
2. copy the .gdbinit file to your OS root folder --> cp .gdbinit ~/.gdbinit <-- (CAREFUL! if you already have a .gdbinit file it will be lost if no backup is made)
3. write your x86 asm code on the kernel.asm file
4. run the QEMU with --> make
5. run the debugger with --> python3 main.py
6. press ENTER, Spacebar or click the 'Step' button at the bottom of the screen to step to the next instruction.
7. have fun :)

![output](https://user-images.githubusercontent.com/43099047/121246981-18a48d00-c878-11eb-85c8-8b710645c8fb.gif)
