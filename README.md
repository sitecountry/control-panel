# control-panel
Install DirectAdmin Control Panel on your VPS/Dedicated Server with a single command

This Installation Script would allow any User to Install the Control Panel software on any VPS/Dedicated Server.

Step 1 :  Login into your server using SSH as root user.

Step 2: Use the wget linux utility to fetch the file from our servers to the source server ( your VPS/Dedicated server ).
 To do so, run the command :  wget https://raw.githubusercontent.com/sitecountry/control-panel/main/install.sh

         
Step 3 : Finally, use bash to execute the script on the server. You will need the control Panel license key to execute the script.
( You will get the key for free for a personal license which includes 1 User account and 10 Domains.)
Once executed, depending on the server's hardware peformance and network speed, it may take sometime.
Run : bash install.sh YOUR_LICENSE_KEY

Note : Make sure to replace YOUR_LICENSE_KEY with your actual license key.

Once the installation is finished, you will get all the necessary information like login username ( which is admin)  and password.
