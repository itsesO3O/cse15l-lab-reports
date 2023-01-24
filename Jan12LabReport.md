# Jan12LabReport
To install VS Code (I personally had it preinstalled on the lab computer, but have my own VSC at home), visit the website  [https://code.visualstudio.com/](https://code.visualstudio.com/) and do
as instructed to eventually have VS Code in your computer.

![Image](vscode open.PNG)

Once you have Visual Studio Code, you can use the terminal to connect remotely to where you desire; for us, we connected using gitbash, which you can install at
[https://gitforwindows.org/](https://gitforwindows.org/) . Once done with this, you can create a bash terminal by open the terminal in VSC with Ctrl+` and subsequently make sure to to select Git Bash as a default profile by using Ctrl+Shift+P, searching for "Select Default Profile" and selecting it for use. You type into the open terminal (selecting bash from the drop down after adding a new terminal) the following:

`$ssh cs15lwi23zz@ieng6.ucsd.edu`. 

(For us our account was more specific, removing the zz for another of an apprently random 3-letter permutation).
You put your password in, which may be made difficult by the fact you can't see what inputs are being received visually, and you get the following:

![Image](onceLoggedIn.png)

From here you can perform commands. I tried concatenating the Hello.txt file from within the computer I connected to, got the following alongside an error below it
since I was encouraged to see if I could make an error occur, which for a professional on those was easy.

![Image](concatenationTest.png)

Some other commands are:
- `$cd` Change the working directory.
- `$ls` To list the files in the current directory (or specify from where after the command)
- `$ls -lat` From what my labmates had on the Lab 1 Doc, this shows files in ordered from the most recently modified.

And all that was done in lab is completed, aside from the setup of the page where this is in itself. 

Thanks for reading and good evening.
