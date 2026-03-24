# abacus-for-study

This repository is designed for studying and testing some classes from the ABACUS software. It provides a platform for learning the implementation details and functionality of ABACUS components.

## About ABACUS
ABACUS (Atomic-orbital Based Ab-initio Computation at UStc) is an open-source package based on density functional theory (DFT). The package utilizes both plane wave and numerical atomic basis sets with the usage of pseudopotentials to describe the interactions between nuclear ions and valence electrons.

## Main Repository
The main ABACUS repository is available at: [https://github.com/deepmodeling/abacus-develop](https://github.com/deepmodeling/abacus-develop)

## Compilation Methods

### CMake Compilation
In the `source/source_base/` directory, CMake is used for compilation. This method allows you to compile all code together.

### Individual Compilation
For each functionality, you can also compile separately by:
1. Entering the corresponding `test` directory
2. Running the `compile.sh` script to compile
3. Modifying the `main.cpp` file in each test directory to practice using the classes

<img width="600.75" height="358.875" alt="abacus_for_study_logo" src="https://github.com/user-attachments/assets/4dae819c-674b-4654-8e83-18bcdc6e2a63" />
