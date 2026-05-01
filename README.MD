<h1>SPARlock</h1>
<p>Install:
First, you need to install the Python programming language. It is included by default in most Debian GNU/Linux distributions, such as Ubuntu or Kali Linux. If you do not have the language pre-installed, download it from python.org.
Next, Install the ZIP into your home directory, and unzip it. Then run this command that preinstalls all of the requirements for this project.
<code>pip3 install -r requirements.txt</code>
</p>

<h2>Usage</h2>
If you are using Linux, do <code>python sparlock.py [NAME]</code>
<h3>Windows</h3>
Create a file named <code>sparlock.bat</code> at your home directory (the path C:\Users\[YOURNAMEHERE]\sparlock.bat), and should contain this following script:
<code>
@py.exe %USERPROFILE%\SPARlock\sparlock.py %*
@pause
</code>
<h3>MacOS</h3>
Create a file named <code>sparlock.command</code> at your home directory (/Users/[YOURNAMEHERE]) which contains this code:
<code>
#!/usr/bin/env bash
python3 ~/SPARlock/sparlock.py
