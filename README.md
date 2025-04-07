# booker
booking system
Project Dependencies
This project utilizes the nlohmann JSON library and Google Test framework as Git submodules. Their source code is included in the external directory.

Building and Running the Project
To build and run the project using CMake, follow these steps:
1. Open a terminal and navigate to the 'booker' directory: mkdir build && cd build
2. Generate the build system using CMake: cmake ..
3. Compile the project: make
4. Run the application: ./booker [resource_file] [queries.txt] [results.txt]

Running Unit Tests
To execute the test cases from build folder, run:
./unit_tests/unit_tests

The test cases include Example, input, and output folders, containing requirement files and a generated test file. Embedding these files in the test cases would remove dependencies but make them too large. Alternatively, test cases can generate and clean up their own data for production code.
