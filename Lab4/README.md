# CPE 322-A Lab 4: Django and Flask

## Assignment Overview 
The instructions for the assignment were as follows:
* Study the GitHub repository Lesson 4 labs
* Install Django and Django REST framework
* Start Django project "stevens," run server, and view app
* Start Django REST project "mycpu," run server, and view app
* Install Flask if no module named 'flask'
* Run Flask server via hello_world.py and view app

## Using Raspberry Pi 
* For this lab, there are instructions to complete it using a raspberry pi on the IOT repo
1. To install Django and Django REST framework on raspberry pi
~~~
$ pip3 -V
$ pip3 list
$ sudo pip3 install -U setuptools
$ sudo pip3 install -U django
$ sudo pip3 install -U djangorestframework
$ sudo pip3 install -U django-filter
$ sudo pip3 install -U markdown
$ sudo pip3 install -U requests
~~~
2. Install MariaDB server and client on Raspberry Pi
~~~
$ sudo apt update
$ sudo apt install mariadb-server mariadb-client
$ sudo apt install python3-mysqldb
$ sudo pip3 install -U mysqlclient
$ sudo mysql_secure_installation
Enter current password for root (enter for none): 
Change the root password? [Y/n] 
New password: PASSWORD
Re-enter new password: PASSWORD
Remove anonymous users? [Y/n] 
Disallow root login remotely? [Y/n] 
Remove test database and access to it? [Y/n] 
Reload privilege tables now? [Y/n]
~~~
3. Start Django project STEVENS
4. Start Django REST project MYCPU
* possible problem: requests.exceptions.InvalidURL: Failed to parse: http://127.0.0.1:8000/dt/1/
* Solution: sudo pip3 install -U urllib3
5. Run Flask server and open a browser via VNC Viewer and go to http://127.0.0.1:5000/
~~~
$ cd ~/iot/lesson4
python3 hello_world.py
~~~

## Results

## References
* [IOT Repo](https://github.com/kevinwlu/iot)

## Stevens Institute of Technology, Computer Engineering, class of 2024
![Stevens Logo](https://web.stevens.edu/news/newspoints/brand-logos/2020/Circular/Stevens-Circular-Logo-2020_RED.png)
