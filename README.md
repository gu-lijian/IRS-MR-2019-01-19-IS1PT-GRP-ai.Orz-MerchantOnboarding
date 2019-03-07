# mr_groupproject
machine reasoning group project

---
## SECTION 5 : USER GUIDE

`<Github File Link>` : <https://github.com/gu-lijian/mr_groupproject/blob/master/User_Guide.pdf>

### [ 1 ] To prepare the Virtual Machine Environment:

> download pre-built virtual machine from http://bit.ly/iss-vm

> start iss-vm

> open terminal in iss-vm

> start the Tool KIE 7.12 on desktop

> wait until KIE server successfully started up

### [ 2 ] To run the back-end JBPM project on KIE server:

> **Go to URL using web browser** http://localhost:8080/jbpm-console

> Login using username/password: wbadmin/wbadmin

> import project using git import from URL:https://github.com/gu-lijian/mr_groupproject.git

> Deploy the MerchantOnborading Project, and make sure it is running with version 1.0.0

### [ 3 ] To run the front-end Python Project:

> make sure django framework is available (pip install django)

> make a new directory, and start a command prompt at this directory

> clone project from git clone URL:https://github.com/gu-lijian/mr_groupproject_web.git

> use cd command to go to /mr_groupproject_web/merchantapp

> run command: $ python manage.py runserver

> **Go to URL using web browser** http://127.0.0.1:8000/