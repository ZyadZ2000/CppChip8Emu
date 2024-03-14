# Chip8 Emulator

This is a chip8 emulator written in C++.

This project works on Ubuntu with cmake and libsdl2-dev installed.

To compile:

```
    cd cmake-build-debug
    cmake ..
    make
```

To run:
    ```
        cd cmake-build-debug
        ./Chip8_Emulator ../roms/PONG
    ```

To get some help run:
    ```
        cd cmake-build-debug
        ./Chip8_Emulator -help
    ```
Use the -t flag to print the program counter, register values and opcode executed each cycle.

Use the -s flag to execute one instruction at a time waiting for you to press enter after each cycle

Here's a screenshot:

<img src="https://github.com/ZyadZ2000/CppChip8Emu/assets/85132955/28798ee8-7dc9-49c7-aad1-9789662c0fae" style="width:50%;" />

The key mapping is as follows - 

| Chip 8 Key | Keyboard Key |
| :--------: | :----------: |
| `1`        | `1`          |
| `2`        | `2`          |
| `3`        | `3`          |
| `4`        | `Q`          |
| `5`        | `W`          |
| `6`        | `E`          |
| `7`        | `A`          |
| `8`        | `S`          |
| `9`        | `D`          |
| `0`        | `X`          |
| `A`        | `Z`          |
| `B`        | `C`          |
| `C`        | `4`          |
| `D`        | `R`          |
| `E`        | `F`          |
| `F`        | `V`          |
