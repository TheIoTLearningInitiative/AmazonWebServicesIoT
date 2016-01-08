# Lesson 10 - Using the Amazon CLI

In our previous sessions (Lesson 3 to 9) we use the graphical interface to create and configure the IoT devices to report to the AWS infrastructure.
In this lesson we will install the AWS CLI (Client Line Interface to configure our IoT device on the AWS infrastructure)

First we need to install the AWS CLI folow this tutorial to install the software: 

* http://docs.aws.amazon.com/cli/latest/userguide/installing.html
 
After you complete the installation, just test it:

    $ aws help

You must see something like this:

![](51.jpg)

Execute the command aws configure to set up our credentials

![](52.jpg)

The credentials was created on the lesson 1.
The default amazon region must be selected from this table:

![](53.jpg)

**Note:** In the example, I'm using US West (Oregon) us-west-2



---


The next step is grant to our CLI user the AWS IoT access.


 