# HelloWorld

A minimal C17 Hello World program.

## Build and run

With GCC installed and available on `PATH`, run these commands from the repository
root in PowerShell:

```powershell
gcc -std=c17 -Wall -Wextra -Wpedantic -O2 -o helloworld.exe main.c
.\helloworld.exe
```

The program prints `Hello, World!`.

## Install GCC on Windows

If `gcc` is not available, install MSYS2, open its **UCRT64** terminal, and
install the compiler:

```powershell
winget install --id MSYS2.MSYS2 --exact
```

```sh
pacman -S --needed mingw-w64-ucrt-x86_64-gcc
```

Add `C:\msys64\ucrt64\bin` to `PATH` if the installer used the default location,
then open a new terminal.
