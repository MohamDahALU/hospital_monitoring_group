## heart_rate_monitor.sh
For this script, you just need to run it by entering "./heart_rate_monitor.sh" in the terminal. Then it will prompt you to enter the monitor name. Let's say the user entered "Monitor_2", the script will then run a subscript in the background that logs heart rate information indefinetly in a file called "heart_rate_log.txt", and it will print the process ID in the terminal. You can use the PID that was printed on the "kill" command to terminate it.

## archive_log.sh
This script archives the "heart_rate_log.txt" by appending the date information to the end of the file name. This will lead to the "heart_rate_monitor.sh" script to create a new logging file, and the archived file will be separated.

## backup_archives.sh
This script creates a directory called "archived_logs_group30", and moves each archived log file to it. Then it backs up that directory to a sandbox using the scp command.

## Experience
We are a team of 6. Unfortunately 1 of our members is currently in out of kigali. In order to complete the project, we met at campus on Tuesday by 12 pm while the member out of kigali 
joined virtually. We designated tasks based of each persons' strength. Doing this allowed us to complete the task in about 4 hrs. The entire experience alllowed each individual to shine andhelped us understand the benefit of designation and teamwork.  
