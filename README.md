# C++ Windows Audio Player

A lightweight C++ console application that utilizes the Windows API to play audio files synchronously.

## Features
* Uses native Windows Multimedia (`winmm.lib`) capabilities.
* Plays uncompressed `.wav` audio tracks directly through the console.
* Displays status updates in the terminal when playback begins and ends.

##  Requirements
* **Operating System**: Windows (Uses platform-specific `<Windows.h>` headers)
* **Compiler**: MinGW/GCC or Visual Studio (MSVC)

## How to Run (VS Code)

1. Clone this repository to your local machine.
2. Place an uncompressed audio file named `megalovania.wav` into the project root directory.
3. Open your terminal and compile the program using:
   ```bash
   g++ RUNNER.cpp -o RUNNER.exe -lwinmm
   ```
4. Run the executable:
   ```bash
   .\RUNNER.exe
   ```

> **Note**: If you run into directory location issues, update the file path in `RUNNER.cpp` to use the absolute path of your `.wav` file.
