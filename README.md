# reports_app
Create mysql table from csv file, Create mysql table from large csv file, Import big csv file to mysql using php, Simple lightweight php framework, future proof php framework., flexible php framework, No OOPs Framework, Fast php framework

PreRequisites
------------------------------------------
works with >= PHP5, PHP7
mysql 5.x
Linux Preferable
Can install on windows too

Installation
------------------------------------------
Linux
go to server root folder 
cd /var/www/html
git clone https://github.com/jtkboss/reports_app.git
cd reports_app
msyql -u USERNAME -p -e "CREATE DATABASE reports_app"
msyql -u USERNAME -p reports_app < migrate_reports_app.sql
nano config.php - add username and password for your mysql server
open the url in your browser localhost/reports_app
username - best@worst.com
password - 12345678
Rock & Roll

Features
------------------------------------------
csv to mysql table conversion
works with heavey csv files as well
can create new users form create user tab
can use the framework to develop a new application as well
more flexible and fast unlike heavy frameworks which consume time and performance to do a simple task

Create uploaded csv file to mysql table
------------------------------------------
you can upload the file once you login
to import the file you need to run the following commnad
go to project folder - cd /var/www/html/reports_app/backend
php csv_to_table.php
you can add the same in to CRON in LINUX to automate the import 

Once imported email will be triggered to uploaded person

Please Add a Star to my Repo and Email me for any enhancements or new features
