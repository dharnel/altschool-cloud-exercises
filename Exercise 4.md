### Alt school africa cloud Exercise 4

This exercise was to install PHP version 7.4 on our local linux machine using the ppa:ondrej/php package repo and to also learn how to use the add-apt-repository command.
The exercise was relatively straightforward and I did not have any difficulty in attempting it.

The first step was to run the sudo apt-get update command and then the sudo apt -y install software-properties-common. Check the image below.
![Screenshot (56)](https://user-images.githubusercontent.com/68646090/188276294-9530ca58-121c-4979-b5df-83f51fd04423.png)
 
![Screenshot (57)](https://user-images.githubusercontent.com/68646090/188276365-52653623-a01e-4246-9116-c7f6cc4a5d2d.png)


Then I ran the sudo add-apt-repository ppa:ondrej/php command
![Screenshot (58)](https://user-images.githubusercontent.com/68646090/188276381-6892093b-3fdb-488b-bf45-1f853b7ea565.png)


Then I ran the sudo apt -y install php7.4

The content of /etc/apt/sources.list and the php -v command
![Screenshot (59)](https://user-images.githubusercontent.com/68646090/188276395-012010d6-6f01-4e68-999e-3aa746455598.png)

![Screenshot (60)](https://user-images.githubusercontent.com/68646090/188276919-ce8f2ccc-363a-43ce-89c5-6b1f3046d6ab.png)

