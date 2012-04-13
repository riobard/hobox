Hobox
====

Virtualbox-based development environments with ease. 

Inspired by [Vagrant](http://vagrantup.com/)



Requirement
----

* Mac OS X 10.7
* Python 2.7
* Virtualbox 4
* (Optional) OpenSSH SSH client


Usage
----

    mkdir hobox
    cd hobox
    wget http://files.riobard.com/hobox/squeeze.hobox
    hobox init squeeze      # will take about 20 seconds
    hobox info squeeze      # show information (if available)
    hobox up squeeze        # bring up the instance
    hobox ssh squeeze       # ssh into the instance
    hobox down squeeze      # bring down the instance 
    hobox del squeeze       # delete the instance



Todo
----

* Clean up code
* Specification of the .hobox container layout
* Specification of the config file format
