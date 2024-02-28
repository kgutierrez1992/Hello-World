# Hello World

## About

This program is designed to print the text "Hello World" to a terminal screen.

## Requirements

To run this program, you will need the following packages installed:

* A C++ compiler.
* CMake version 3.21 <ins>or higher</ins>.

### Installation

### Windows

1. In a web browser, navigate to [https://wwww.MSYS2.org](https://www.msys2.org/)
2. Download the latest installation of MSYS2.
3. Follow the complete installation instructions listed on the home page.
4. In your MSYS2 session, enter the following command:

    ```bash
    pacman -S mingw-w64-ucrt-x86_64-gcc
    ```

5. Verify that the installation was successful by entering the following command into the command prompt/powershell.

    ```
    gcc --version
    ```

6. In a web browser, navigate to [https://www.cmake.org](https://cmake.org/download/) to download and install the latest CMake binary.

### MacOS

#### Installing the clang compiler

1. Install the xcode CLI developer tools with the following command:

    ```bash
    xcode-select --install
    ```

2. Open a terminal session and verify that clang is installed by entering the following command:

    ```bash
    clang --version
    ```

3. In a web browser, navigate to [https://www.cmake.org](https://cmake.org/download/) to download and install the latest CMake binary.

### Linux Installation

#### Debian-based OS

1. Open a new terminal session and enter the following command:

    ```bash
    sudo apt-get install g++
    ```

2. Verify the installation was successful by entering the following command in your terminal session:

    ```bash
    g++ --version
    ```

3. In a web browser, navigate to [https://www.cmake.org](https://cmake.org/download/) to download and install the latest CMake binary.

#### Red Hat-based OS

1. Open a new terminal session and enter the following command:

    ```bash
    sudo yum install g++
    ```

2. Verify the installation was successful by entering the following command in your terminal session:

    ```bash
    g++ --version
    ```

3. In a web browser, navigate to [https://www.cmake.org](https://cmake.org/download/) to download and install the latest CMake binary.

## Build Instructions

1. In a terminal window, clone this repository to your local machine with:

    ```git
    git clone https://github.com/kgutierrez1992/Hello-World.git
    ```

2. Navigate to the "Hello-World/build" directory.

    ```bash
    cd Hello-World/build
    ```

3. Using CMake, generate the necessary build files with the provided CMakeLists.txt file to the build directory:

    ```bash
    cmake ../src
    ```

4. With the files generated, build the source files into an executable file with the following command:

    ```bash
    cmake --build .
    ```

5. Launch the program with the following command:

    ```bash
    ./hello_world
    ```
