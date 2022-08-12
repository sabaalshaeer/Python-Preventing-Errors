# Python-Preventing-Errors
Open a version of the WordCount project that contains errors.
In PyCharm, select File→Close Project.
This closes the project you were working on, but leaves PyCharm running. You are returned to the Welcome to PyCharm window.
Select Open, and beneath the C:\094021Data\Setting Up Python and Developing a Simple Application directory, select the Errors directory, as shown.
Select OK.
Confirm that the Python 3.9 interpreter will be used with this project.
In the Project pane, if wordcount.py is not showing beneath the Errors folder, select the triangle next to Errors to expand that folder.
Double-click wordcount.py to open the file for editing.
Attempt to run the program, and verify that Python produces a syntax error in the console.
Within the wordcount.py code window, right-click and select Run 'wordcount'.
A syntax error is reported.
In the Run window, close the wordcount tab.
Debug the program.
Verify that PyCharm has detected several syntax errors in the code, denoted by red highlighting.
At the right of your source code, observe the error count.
PyCharm has found numerous errors in the code.
Along the right edge, examine the markers showing lines that contain errors.
Point at the error marker at the end of line 12, and wait a moment.
Two possible errors have been identified in line 12.
Correct the missing closing quote.
Place your insertion point at the end of line 12, before the last closing parenthesis.
Type a double quote character.
Verify that line 12 is no longer marked as an error.
Fix the remaining syntax errors.
In line 14, point at the underlined word println.
Python's print statement is just print. There is no println statement in the language.
Fix the error by removing the letters l and n from println.
In line 18, point at the underlined word useroutput.
You didn't define useroutput, but you did define a user_output variable (notice the underscore). Mistakes like these are often the result of typos or forgetting the exact name of a variable. If the name isn't exact, Python won't be able to execute it.
Add the underscore to fix the print statement in line 18.
Test your program to make sure it runs properly.
Run the program.
Enter Testing input at the first prompt.
When you're asked to strip common words, enter Y
Observe that the resulting print line isn't repeating your Y answer, but says Testing input.
In your source code, examine the print statement in line 14.
Correct the error.
In wordcount.py, correct the logic error in the code.
Rerun the program and test that it works as intended.
Clean up the workspace.
Select File→Close Project.
Close the Welcome to PyCharm window.
