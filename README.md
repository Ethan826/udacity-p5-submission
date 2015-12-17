# Instructions to Udacity reviewer

## The IP address and SSH port so your server can be accessed by the reviewer.

52.33.71.162:2200

## The complete URL to your hosted web application.

http://ec2-52-33-71-162.us-west-2.compute.amazonaws.com/

## A summary of software you installed and configuration changes made.

I installed the following packages:

* postgresql 
* apache2 
* git
* libapache2-mod-wsgi-py3 
* postgresql-server-dev-all
* python3-dev 
* python3-pip 
* python3-psycopg2
* virtualenv
* glances (for the performance-monitoring assignment)
* fail2ban (for the banning attackers assignment)

I also wrote a cron script saved at `/home/grader/cronJob.sh` and run by `crontab`.

## A list of any third-party resources you made use of to complete this project.

I consulted numerous StackOverflow answers, the Udacity comment board, Ubuntu, Apache, and Flask documentation, Google, etc. 

I adapted significant chunks of code from [here](https://goo.gl/r9yH4T) and [here](http://goo.gl/UJFhQO). 
