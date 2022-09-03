### Alt school africa Exercise 4

This exercise was to install PHP version 7.4 on our local linux machine using the ppa:ondrej/php package repo and to also learn how to use the add-apt-repository command.
The exercise was relatively straightforward and I did not have any difficulty in attempting it.

The first step was to run the sudo apt-get update command and then the sudo apt -y install software-properties-common. Check the image below.
! [Screenshot1] (images/screenshot(56).png) 
! [screenshot2] (images/screenshot(57).png)

Then I ran the sudo add-apt-repository ppa:ondrej/php command
! [screenshot3] (images/screenshot(58).png)

Then I ran the sudo apt -y install php7.4

The content of /etc/apt/sources.list and the php -v command
! [screenshot4] (images/screenshot(59).png)   
