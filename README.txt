$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$


This is the easiet way to make the server just download this :

https://drive.google.com/file/d/1ouRLpvh-Lb9mdrEH6veiZWIuVYJqcTWW/view



$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

WHERE TO PLACE FXSERVER FOLDER?

PLACE FXSERVER ON YOUR DESKTOP


$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

HOW TO INSTALL artifact FOLDER :

STEP 1 - DOWNLOAD LATEST OPTIONAL BUILD

https://runtime.fivem.net/artifacts/fivem/build_server_windows/master/

STEP 3 - MAKE SURE artifact folder is empty and EXTRACT ZIP TO artifact FOLDER.


$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

HOW TO INSTALL cfx-server-data FOLDER:


STEP 1 - 2 OpeN GIT type this

cd Desktop
cd FXServer
git clone https://github.com/citizenfx/cfx-server-data.git

STEP 2 - CLOSE GIT

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

HOW TO CHANGE server.cfg?

Open the server.cfg provided and go through it to the end and do the things that are hashed out.
And then place it in your cfx-server-data

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

HOW TO INSTALL FIVEM RESOURCES?

STEP 1 - OPEN GIT WITH ADMIN

STEP 3 - right click & paste the contents of InstallQBCore.txt

STEP 4 - CLOSE GIT

STEP 5 Open Git ,  right click & paste the contents of InstallOther.txt



STEP 6 - Manually install the remaining resources in ItemsThatNeedToBeInstalledManually.txt by drag and drop to [local]

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

Also when you extract the resources for the Server, you will have to extract the prison map as there is 3 files in side of it which need to be put in local.
Also there is the hospital maps that need to be extracted and 1 more I think just look for errors or check files.

$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

HOW TO IMPORT SQL FILES?

#1 INSTALL XAMPP
#2 START APACHE AND MYSQL
#3 CLICK ADMIN ON MYSQL
#4 ON THE LEFT CLICK "New" IN THE COLUMN
#5 TYPE "qbcore" FOR THE DATABASE NAME, CLICK CREATE.

6. Click on qbcore and click on IMPORT, should be located in the middle of the screen at the top.
7. Open every file seperately in SQLFiles and then click Go for each of them. 
(Go  button is at bottom right)
(make sure to import qb-core first)



$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

How to RUN SERVER?

1.) Click on artifact folder
2.) run CitizenFX once name your server and when it give you 4 options click Local Server Data.
3.) give path to your cfx-server-data folder
should be something like this: C:/Users/[your username on the pc]/Desktop/FXServer/cfx-server-data
4. When you have finished all the steps on the website close the server and the browser.
5.) make sure you imported all .sql and your database is running
and that have done all of the steps before this, make sure to change the last line of server.cfg ("change me")
6.) run the .bat in main folder to start server.


$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

