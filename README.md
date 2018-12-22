# setup-python

## Purpose
Write down the process of setting up the programming environment of Python with VSCode.

## Steps	
1. Install the Git version control software on your Windows 10.   
  Git would help you **_clone_**(download) the code source directly from Github.  
	Use the command **_git clone giturl_**.  
  ![git](/pictures/readme/git.png)    
	
	
2. Install the python software. Check python installation using **_cmd-pyhton_**.  
	Test python function in cmd. Use command **_python .py-file-name_** to run python file.  
	![cmd-python](/pictures/readme/cmd-python.png)    
	
3. Install the Visual Studio Code. Install the **extension-Python**.  
	![extension-pyhton](/pictures/readme/extension-python.png)    
	
4. Download the Python **launch.json** file.   
  This setting file sets the Python debugging environment.   
  Also set up the environment with the python software you installed.  
	![launch-json](/pictures/readme/launch-json.png)   
	
5. Display Timeout waiting for debugger connection always.   
  ![timeout-error](/pictures/readme/timeout-error.png)     
	  * Possible reasons:   
	  [Visual Studio Code Python Timeout waiting for debugger connection](https://stackoverflow.com/questions/52462599/visual-studio-code-python-timeout-waiting-for-debugger-connection)  
    ![possible-solution](/pictures/readme/possible-solution.png)    
    * Solution:   
		Skip the debugging processes. So it won't bother so much.   
		Right click Run Python File in Terminal.    
		In terminal, result is displayed there.    
    ![run-in-terminal](/pictures/readme/run-in-terminal.png)   

## Reference
1. [How to Set Up Python in Visual Studio Code on Windows 10](https://www.youtube.com/watch?v=dNFgRUD2w68)
2. [Python debug configurations in Visual Studio Code](https://code.visualstudio.com/docs/python/debugging)
3. [Python For Beginners](https://www.python.org/about/gettingstarted/)
4. [How to run git clone command on windows](https://developer.ibm.com/answers/questions/8770/how-to-run-git-clone-command-on-windows/)
5. [Getting Started with Python in VS Code](https://code.visualstudio.com/docs/python/python-tutorial)
