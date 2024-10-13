# bash_project

The purpose of this project of mine, is to allow for users to check the permissions of a file that they input into the program. The program is also meant for them to change permissions for said file if they would like to as well.

The main syntax used for the program is functions, such as the first prompt that will display when running the script. This simply displays, by using the **echo** command, the different usages of the script and the help option that will also show how to use the script.

When users type in -p before the filename, it will simply show what the current permission settings are for the file. Now in hindsight, it would have been helpful to include what each permission is and what it does, but I didn't think of that until after completing the script and that is something I would have definitely added so users can get a general idea of what they are looking at when they are given the permissions to the file.

The -f function before the filename, allows for the users to change permissions for the specific file that they have chosen. Once again it would have been nice for the user to display the different permission settings and how they work, but I was more or so focused on getting the main function complete and did not think about it until writing the README.md

A lot of writing this script came from looking back at our previous assignment, the bash args assignment, but this time the function was for checking and changing permissions which I really enjoyed doing for this project. It may seem like a simple program that isn't too complicated, but to me it meant a lot since I can confidentially say I am not very skilled when it come to programming this kind of stuff or in general. I did consult to some videos and website for assistance as well, especially when it came to writing the functions. Overall it was a good learning experience and I really enjoyed attempting and working on this project.

This project did take longer than expected, about an hour and a half mainly because it took me a long time to troubleshoot an error that was happening. Before using -f for the function, I was using -ep, which was not working because it turns out it was more focused on just reading the -p option and was executing the -p function, rather than executing the -ep function that it was supposed to. Not sure why it works like that and I'm sad it took so long for me to figure that out, but after changing the letter to something else, it worked out fine.
