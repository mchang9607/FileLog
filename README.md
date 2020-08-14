Program designed for personal use.
Prompts information from user about digital purchases, then stores such items into the corresponding table.
#### _Attention_: Uses MySQL and Java database drivers for MySQL (jdbc). Packed in jar file, but also officially downloadable [here](https://dev.mysql.com/downloads/connector/j/).
#### _Attention_: This program connects to databases and uses tables with specific names. For details, see MySQL_setup.txt. To change database names and fields, Editting and recompilation of FileLog.java is required.

* Language: Japanese
* Update plans: provide deleting functionality 
* author: mchang9607 (bernkastel79)
* Special thanks:Kent Chen

#### _Setup instructions:_
1. Install MySQL database, and make sure that the local port is 3306 (which should be by default.)
1. Run the commands in order given in MySQL_setup.txt to setup the specific database.
1. `cd` to where the jar file exists, and run it via the command `java -jar ./FileLog.jar`

The program prompts a username and password of the database everytime at start, which by default should be
 * Username: Jguest
 * Password: java
 
You can customize such settings when setting up the database, i.e. replace the username and password with what you want when entering the commands from MySQL_setup.txt.
