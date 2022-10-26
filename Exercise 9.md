# altschool-cloud-exercises Exercise 9 - Ansible

The task was to create an Ansible playbook to setup a server with apache. The server should be set to the Africa/Lagos Timezone. Also we were to host an index.php file
with content in it as the main file on the server

Here is the ansible playbook. First task was to install updates, then install apache and php to be able to host and render the page. Then we start the apache service
incase it did not start immediately after installation and we set the timezone to Africa/Lagos. Next we install ngingx web server and copy the index.php file and lastly,
we allow internet connections

![Screenshot (74)](https://user-images.githubusercontent.com/68646090/198156303-202b6fa3-dc42-4c1d-b227-880ddf04487f.png)

Here is the output of systemctl status apache2 after deploying the playbook on my digital ocean instance

![Screenshot (75)](https://user-images.githubusercontent.com/68646090/198156576-7d779b38-111b-4bb8-b1d3-79211b771b3c.png)

and here is a screenshot of the rendered page![Screenshot (72)](https://user-images.githubusercontent.com/68646090/198156726-9fb83ff2-f176-415f-acfa-e3ac5086783b.png)


![Screenshot (72)](https://user-images.githubusercontent.com/68646090/198156748-e9d8bd8c-2aff-4c47-96f9-ee4d1edb9186.png)
