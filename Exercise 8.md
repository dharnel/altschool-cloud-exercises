# altschool-cloud-exercises Exercise 8 - Crontab

The task was to create a bash script to run at every hour, saving system memory(RAM) usage to a specified file and at midnight it sends the content of the file to a 
specified email address, then starts over for the new day.

Here is a sample of the bash script I wrote, First we create the file with the touch command, then an if statement to check if the time is midnight, When it is 
midnight, the file is sent to an email address with the mutt command which is used to attach files to an email. At every other hour that is not midnight, the date and
the RAM usage is recorded in the file using the date and free command
![Screenshot (70)](https://user-images.githubusercontent.com/68646090/198154738-3d8da295-e862-4e66-bd0c-f18df66743b0.png)

here is the crontab I wrote to run the script every hour.
![Screenshot (68)](https://user-images.githubusercontent.com/68646090/198154852-2c1bb78f-810e-4532-b360-330a66303eeb.png)

Here is the email I received
![Screenshot (71)](https://user-images.githubusercontent.com/68646090/198155167-414d5704-aec1-4728-8af3-6b91916f472f.png)

