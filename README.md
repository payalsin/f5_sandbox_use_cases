# F5 Ansible 101 F5 Workshop

Welcome to this Ansible 101 training.

This training will take you through the basic knowledge and exercises to
gain understanding how F5 BIG-IP can leverage Ansible to facilitate
automated application services.

Being a '101', this training will only cover:

-  Exploring some Ansible basics.
-  Gathering BIG-IP facts.
-  Creating BIG-IP objects like nodes, pool, virtual server and iRules.
-  Disable pool member, delete configuration and error handling.
-  Introduction of using AS3 with Ansible.

After taking this course a student should be able to create simple
playbooks for deploying application services on BIG-IP and be able to
use AS3 with Ansible and push configurations through a playbook on the
BIG-IP.

**Note:** 
If you have any questions or issues, [Click here to open an issue](https://github.com/f5devcentral/FAS-ansible-workshop-101/issues)

**Pre-requisites**

To get the most out of this training, the student should already have some basic knowledge about the use of Ansible and BIG-IP. When you are
completely new to Ansible it is recommended to start with the 2 hour [Ansible Quick Start](https://linuxacademy.com/cp/modules/view/id/288) training from Linux Academy.

**Lab Environment**

This Ansible 101 training comes with a pre-configured lab environment. Please go **[here](https://github.com/f5devcentral/FAS-provisioner)** to
provision your lab environment.

This content is a multi-purpose toolkit for effectively demonstrating Ansible's capabilities on F5 BIG-IP by providing workshop training in
various forms -- instructor-led, hands-on or self-paced.

Following topics will be covered

## Section 1 - Ansible F5 Basic Exercises

-  Exercise 1.0 - Exploring the lab environment
-  Exercise 1.1 - Using Ansible to gather data from F5 BIG-IP 
-  Exercise 1.2 - Adding nodes to F5 BIG-IP
-  Exercise 1.3 - Adding a load balancing pool
-  Exercise 1.4 - Adding members to a pool
-  Exercise 1.5 - Adding a virtual server
-  Exercise 1.6 - Adding and attaching an iRule to a virtual server
-  Exercise 1.7 - Save the running configuration 
-  Exercise 1.8 - Virtual server facts 

## Section 2 - Ansible F5 Operational/Advanced Exercises

-  Exercise 2.0 - Disabling a pool member 
-  Exercise 2.1 - Deleting F5 BIG-IP Configuration
-  Exercise 2.2 - Error Handling 

## Section 3 - Ansible F5 AS3 Exercises

-  Exercise 3.0 - Intro to AS3
-  Exercise 3.1 - Operational Change with AS3 
-  Exercise 3.2 - Deleting a Web Application 
-  Exercise 3.3 - Deploying WAF through AS3
