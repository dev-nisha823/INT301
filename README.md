# INT301

# TOPIC : Using desired Open Source Software provide details of the motherboard, network, storage devices, and display. Also, create an HTML report of everything and create favorites to have instant access to any hardware component from the menu bar.

# Introduction
1.	Objective : To get the detailed information about the motherboard, network, storage devices and display of hardware component by using any open source software tool. Creating the favorites to get an access of hardware component of the system directly from the menu bar.
2.	Description : In this project, lshw command/tool is used to get the detailed information of motherboard, network, storage device and display of hardware component. It is a lightweight and easy to use tool which provides basic hardware information about the hardware system. If any user want to quickly get the detail of hardware components of a system, without navigating through a lot of additional information. lshw can also report exact memory configuration, firmware version, mainboard configuration, CPU version and speed, cache memory configuration, bus speed, etc,.

 # Lshw command features:
A.	To diagnose hardware issues 
B.	To gather information about your system
C.	To verify hardware compatibility
D.	To aid in system administration

# Analysis Report
System description : Commands that is used in this project step wise
1.	sudo lshw : to get the detailed information about motherboard, network, storage devices and display of hardware component.
2.	lshw –short : It is a useful command to display a condensed, simplified output of the hardware components of a Linux system. Because it simplify the output, save screen space and include only essential information.
3.	sudo lshw –html > hardwareInfo.html : It is used to create html file whose name will be hardwareInfo.html where all the code related to informaion of hardaware component of system will be written and we can display the information on any browser easily like a simple html webpage.
4.	sudo apt install alacarte : This command will be used to create favorites in the menu bar. Go into the Activities and in search bar option write main menu and open it where we will create new item and in this give name, path of the favorite and add icon as well.
5.	sudo lshw –html : command to print hardware information in html format.

Full Analysis :
# Step 1 : open the terminal and write sudo lshw command.
  
# Step 2 : write lshw –short command 
 
# Step 3 : write sudo lshw –html > hardwareInfo.html to create html file in the home page. 
 
Go to the file and then search for hardwareInfo.html file. Right click on this file and select open with firefox web browser to see the html report where all the detailed information of motherboard, storage device, network and display will be shown.
 
Code of these detail written in hardwareInfo.html file
 
# Step 4 : write sudo apt install alacarte to install the "alacarte" package which is a graphical menu editor for the GNOME desktop environment in Linux. 
 
After writing above command go to activites and search for main menu and then go inside it and click on the New Item button and then a pop up box will open where we will create menu. Write name of the menu and in the command write  xdg-open "/home/vboxuser/hardwareInfo.html"

To change the icon select any picture for icon by going in picture section

Now click on ok button to add “Hardware Info” file to menu bar as a favorite.
 
Now go to Activities and search for the menu name which you have created and right click on the file to make it favorites after clicking it will add to the menu bar section and from there anyone can easily access and open it to see the html report where all the detail of hardware component is displayed. 

After ubuntu software Hardware Info file is added to the menu bar.
 
After clicking on “Hardware Info” file it will open the harwareInfo.html file either in the text editor or firefox web browser it depends what you have selected to open this particular file. User can also delete this favorite by right click on “Hardware Info” file and then click on remove from favorites it will be removed from menu bar but not from the system it will be in the system but not in the favorite list. 
 
# Step 5 : write sudo lshw –html command in the terminal.
 


