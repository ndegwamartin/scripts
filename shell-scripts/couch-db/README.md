Usage

0. Make sure the target host is set up with couch db running
1. Place the json documents you want to populate the db inside this folder
2. run *./couch_migrate.sh -d <database name>*

No. 2 above is the simplest form of usage which assumes the migration scripts reside in the same folder as this script. The **database name** is the only **required parameter**. 

You can use the test.json provided to test the script and see if populates your db by running the above command no 2

For more options, run :


*./couch_migrate.sh --help* to get a list of available options


  Specify (Optional) a database name like *./couch_migrate.sh -d <database name>*

  Specify (Optional) a host like  *./couch_migrate.sh -h <hostname>*

  Specify (Optional) a port name like  *./couch_migrate.sh -p <port>*

  Specify (Optional) a source folder like  *./couch_migrate.sh -f <folder path>*

  Specify (Optional) a username like  *./couch_migrate.sh -u <username>*

  Specify (Optional) a password like  *./couch_migrate.sh -pwd <password>*

  Specify (Optional) a protocol e.g. http or https like  *./couch_migrate.sh -proto <protocol>*

  Specify (Optional) a HTTB VERB or method e.g. PUT, POST(default) like \033[33m ./couch_migrate.sh -method <http verb>\033[0m

  Specify (Optional) any multiple arguments like  *./couch_migrate.sh -u <username> -pwd <password> -d <database name>*

For Authentication you can choose to pass the username and password as part of the host 
e.g.  **./couch_migrate.sh -h http://<username>:<password>@<hostname>**

Have a nice day! :)
   
