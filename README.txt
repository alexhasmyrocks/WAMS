							WAMS Beta 														3.10.7.4:
	`											                                    						  Manual


What is WAMS:

WAMS stands for, Windows Automated, Maker, Script. This means that 
you can use this program to write windows based batch scripts. You could make
windows based viruses, malware, tools, or games. WAMS allows you to make these 
previously mentioned scripts without almost any pre-existing knowledge of programming.
WAMS is currently in Beta. 
WAMS will be fully released by June 2020.


How to Declare Variables/Keys:

Keys and variables are the same thing; Keys and variables are words or phrases that stand for a value such as an
integer, string, or a float. Variables can be declared within the properties tab in the tool bar. The second console,
to the right of the main log, is the variable console. This console tells you the variables you currently have declared
and their values. To access your variables, use -(the name of your variable); this will replace the - and the name of your
variable with the value of your variable.


Background Programs:

What are they?
Background programs are pre-existing batch scripts that run within your program. There are
two methods of running background programs in WAMS, the first way is where you have the
absolute path. This kind of path is when you have the entire path of the file; this kind of path
will allow the file to only work in the specific location described by the path. The second way
to declare a background program is using a relative path. To use a relative path, add -n to the end
of the name of the batch script you are attempting to run as a background program. This allows 
the program to be run from any drive on the computer, as long as the file is the same directory as 
the batch script calling the background program.


What is a Package?

A package is pre-written code. This can be used to accomplish tasks that may not be accomplishable otherwise.
Packages have no file extension. All you have to do to add the package to your program is add the file to the packages
folder. Next restart WAMS. Now check under the packages tab.

How to get Packages:
To get packages you can use the ones soon to be provided on the home site. Or if you cannot find a package on the site 
that satisfies your needs, you can find a batch script, download it, right click on it, and click edit. Copy and paste the code inside of there into a blank file
without an extension. Move this to your packages folder. Now you can access this code from any time and plug it into your current script.


How to Delete Commands With Paths in them:
For the ease of the user, you do not need to enter the command and the path following it. All you need to do to delete a 
command with a path used in it is to type the command as you see it in the command log. If that command appears multiple times within your 
code then you will simply need to delete it using the scale widget provided.


When is it ok to move my script?
You can move your file outside of the outputs folder when ever you are not editing it.
Once your script leaves the output folder WAMS cannot make changes to it.
Do not edit any of the other files in the other folders, as those can lead to an error.
