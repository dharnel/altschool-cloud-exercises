# altschool-cloud-exercises
### Exercise 3

This exercise was to create 3 groups - admin, support & Engineering and to add the admin group to the sudoers
Then we were to create user in each of the groups
and lastly we were to generate SSH keys for the user in the admin group

The first two tasks were relatively easy as I just used the useradd and the groupadd command to create them.
I created the users first then I used the usermod command to add them to the various groups.

The main challenge I had was generating the SSH keys for the user in the admin group.
I tried doing it while logged into the user and I had permissions issues. I could not generate the SSH keys.
I solved this by changing the ownership of the user directory to the user and I had permisson to create the folder were the keys would be stored.

The contents of the /etc/passwd
![Screenshot (50)](https://user-images.githubusercontent.com/68646090/188664208-5e2b0866-78db-46a2-b59f-da135bc40cf7.png)

The contents of the /etc/group
![Screenshot (51)](https://user-images.githubusercontent.com/68646090/188664438-64407822-ffa8-4c7b-a44d-3496a851c098.png)

The contents of the /etc/sudoers
![Screenshot (52)](https://user-images.githubusercontent.com/68646090/188664542-c3729d35-7f9f-4c14-90c8-96f242f94e24.png)

