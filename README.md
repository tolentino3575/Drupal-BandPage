
#Band Page

#### By: Erik Tolentino

## Description

This is a website built with Drupal. It contains basic content types such as articles and basic pages.

## Prerequisites

You will need the following things properly installed on your computer:<br>
• [Drupal](https://www.drupal.org/project/drupal)<br>
• [MAMP] (https://www.mamp.info/en/)

##Log-In
• Database Name: 'project' (file will be 'project.sql.zip')<br>
• PhpMyAdmin user: '<em>BandManager</em>' password: '<em>password</em>'<br>
• Site Maintenance Account: '<em>BandManager</em>' password: '<em>password</em>'<br>

## Setup/Installation Requirements

1. Open Terminal and clone this repository: https://github.com/tolentino3575/Drupal-BandPage.git
2. In your browser navigate to ```http://localhost:8888/phpmyadmin```. Select the Import tab and in the project directory go to ```sites > db-backups > databasename.sql.zip``` and click GO at the bottom of your screen
3. Also in phpmyadmin, recreate the user you created initially in the database (the username and password can be found in the settings.php file)
4. Open MAMP, select ```Preferences```, select ```Web Server``` tab, direct the ```Document Root``` to the top level of your project folder
5. Navigate the browser to ```http://localhost:8888``` 

## Known Bugs

N/A

## Support and Contact Details

If you have any issues, questions, ideas, or concerns contact us through GitHub. If you would like to make a contribution to the code, feel free to do so and notify me by e-mail.

## Technologies Used

• Drupal<br>
• phpMyAdmin<br>
• PHP<br>
• GIT<br>
• HTML<br>
