Hobox
====

Virtualbox-based development environments with ease. 

Inspired by [Vagrant](http://vagrantup.com/)



Requirement
----

* Mac OS X 10.7+
* Python 2.6+
* Virtualbox 4.1+
* (Optional) OpenSSH SSH client 5.6+


Usage
----

    mkdir squeeze
    cd squeeze
    wget http://files.riobard.com/hobox/squeeze.hobox
    hobox init squeeze      # will take about 20 seconds
    hobox up squeeze        # bring up the instance
    hobox ssh squeeze       # ssh into the instance
    hobox down squeeze      # bring down the instance 
    hobox del squeeze       # delete the instance



Todo
----

* Specification of the .hobox container layout
* Specification of the config file format
