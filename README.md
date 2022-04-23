# control-panel
Install Control Panel on your VPS/Dedicated Server with a single command

This Installation Script would allow any User to Install the Control Panel software on any VPS/Dedicated Server.

Step 1 :  Login into your server using SSH as root user.

Step 2: Use the wget linux utility to fetch the file from our servers to the source server ( your VPS/Dedicated server ).

Step 3 : Once you fetch the script, the defauly permisssions for the files are not executable, make sure to make the file executable by running 
         chmod +x install.sh
         
Step 4 : Finally, use bash to execute the script on the server.
Once executed, depending on the server's hardware peformance and network speed, it may take sometime.

Once the installation is finished, you will get all the necessary information like Login URL, login username and password.
