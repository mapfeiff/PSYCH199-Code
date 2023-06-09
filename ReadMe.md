# This is a repository consisting of all code made for my PSYCH 199 - Independent Project Course
Course Taken: Spring 2023
Advisor: Professor Ramesh Srinivasan, Department of Cognitive Sciences, University of California, Irvine

**Recommended to create a Python virtual environemnt to run all code on locally installed libraries**

## Libraries needed to run all code:
> Pytorch (2.0.0) w/ CUDA 11.7
>
> Numpy

## Steps on making your own Python virtual environment:
1. Open a new terminal
2. Ensure the terminal is at the correct directory which you would like to store your Python virtual environment
3. Enter the command: python -m venv NameOfVirtualEnvHere
4. Activate the environment by running the file: ./NameOfVirtualEnvHere/Scripts/Activate.bat
5. Close the current terminal and start a new one
6. You should now be in the Python virtual environment
7. If you do not see the (PythonVirtualEnvironment) tag printed to the left of the current directory within the terminal, then manual select the ./PythonVirtualEnvironment/Scripts/python.exe file as your interpreter (in VScode, the option should be on the bottom right)
8. Close the current terminal and start a new one
9. You should now be in the Python virtual environment
10. If an error about running scripts occurs, ensure permissions are given by running PowerShell as Administrator and entering: Set-ExecutionPolicy RemoteSigned
11. Close the current terminal and start a new one
12. You should now be in the Python virtual environment
13. You should now be able to install any libraries, having them stored locally in the created repository
14. For additional help, see: https://docs.python.org/3/library/venv.html