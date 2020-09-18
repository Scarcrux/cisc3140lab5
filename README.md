# cisc3140lab5
Terminal Log Files

For Task 1, I had to select a column from a CSV file using terminal in MacOS. I googled all the necessary commands. First, I used curl to download a zip archive containing a CSV file to a Lab 5 directory that I had already created. Then I used unzip to extract the contents of the zip file. I navigated in terminal to the subdirectory created by unzipping the archive. Then I used the head command to read the first 10 lines of a CSV file that I selected. Then I read the total number of lines in the CSV. Then I selected the 3rd column in the CSV which contained movie ratings. I used cat to select the column and output it to a text file. Then I use the sort command to reverse sort the text file numerically line-by-line. Finally, I used head again to show what the selected and sorted column looks like in the text file.

Working with data sets and parsing data and command-line interfaces are all common so this task helped to familiarize those concepts at a basic level.

For Task 2, I had to create a shell script version of task 1. Shell scripts can be great for saving time for repeated tasks because you can throw a bunch of command in a script and even automate them by schedule if you want to.

I created a basic, static bash script using the nano text editor. First, I navigated to a fresh directory in terminal. Then I opened nano to edit the bash script. I copied and pasted the commands from Task 1 into the bash script. Saved the file and exited nano, then ran the script. The script ran all of the terminal commands with a single command to execute the bash script.

For Task 3, I had to do something creative in terminal. The objective was to gain more familiarity with terminal and use it for more purposes. I decided to use ffmpeg to convert an MP4 video into an animated GIF. First, I installed ffmpeg. Then I input "ffmpeg -i cat.mp4 -f gif cat.gif" into terminal to output the video as a GIF named cat.gif. This task seemed easier than expected.
