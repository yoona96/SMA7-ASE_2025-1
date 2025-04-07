# SMA7-ASE_2025-1
CI/CD + static analysis

This is a Repository to provide CI/CD environment (otherwise, CTIP) to SMA team 7.

This environment ...
1. Gets code from development team's repository.
2. Builds project with CMake.
3. Performs unit testing.
4. Checks coverage of unit test (GTest) with gcovr.
5. Runs static analysis (cppCheck + Clang-tidy + Sonarqube)
6. Makes a github issue.

We need ...
1. Development team's sonarqube token.
2. Development team's repository dispatched.

Development team needs ...
1. Public development github repository.
2. .yml file in .github/workflows folder to trigger dispatch.
3. V&V team's PAT (personal access token) as secret key.