# SMA7-ASE_2025-1
CI/CD + static analysis

This is a Repository to provide CI/CD environment (otherwise, CTIP) to SMA team 7.

This environment ...
1. Clones code from development team's repository.
2. Builds project with CMake.
3. Performs unit testing with GTest (GoogleTest).
4. Checks code coverage with gcovr.
5. Runs static analysis (cppCheck + Clang-tidy + FlawFinder + Sonarqube)
6. Makes a github issue.

We need ...
1. Development team's sonarqube token.
2. Development team's public repository address.
