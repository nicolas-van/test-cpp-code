# Hello World C++ Project

This is a simple C++ project that demonstrates the basic structure of a C++ application using CMake for building.

## Project Structure

```
hello-world-cpp
├── src
│   └── main.cpp
├── CMakeLists.txt
└── README.md
```

## Requirements

- CMake (version 3.10 or higher)
- A C++ compiler (e.g., g++, clang++)

## Building the Project

1. Clone the repository or download the project files.
2. Open a terminal and navigate to the project directory.
3. Create a build directory:

   ```
   mkdir build
   cd build
   ```

4. Run CMake to configure the project:

   ```
   cmake ..
   ```

5. Compile the project:

   ```
   make
   ```

## Running the Application

After building the project, you can run the application with the following command:

```
./hello-world-cpp
```

You should see the output:

```
Hello, World!
```

## License

This project is licensed under the MIT License.