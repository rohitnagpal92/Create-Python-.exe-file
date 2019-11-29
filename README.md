# Create-Python-exe.-file
We can create python executable (.exe) file that can be run on any system even if the user doesn't using the python software. Creating the python .exe file provides the easy way to execute the required program. Like all other .exe files, user just need to double-click on the file and the program in-built in .exe file gets execute automatically. This comes very handy in case automating the entire process or job scheduling etc.

Below are the steps mentioned to create python .exe file using the python script (already created):
1. Open "Command Prompt"
2. Change the location of current drive to where the python script is placed. To change the location type: cd <locatoion of python script> 
3. Now type: pip install pyinstaller
4. Once the installation of step3 is done, as the last step type: pyinstaller -F <name of python file>

