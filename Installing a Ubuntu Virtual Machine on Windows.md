**Installing a Ubuntu Virtual Machine on Windows**

## **Introduction**

## **Some Terminology**

- A Virtual Machine (VM) is a fancy program that emulates computers
  - Why would you use them? Great for developing and      testing software on different platforms, offers extraordinary amounts of      flexibility, great for businesses (because you have full control - it can      save you money, make maintenance easier, allow for remote workstations,      plus they can be manipulated, started and stopped instantly)
  - The downsides... They aren't nearly as fast. You do      still have to pay licensing fees for software that requires that (things      like Windows 10 for example), the support isn't quite as good for certain      hardware components, there can be network constraints, and there is an      additional layer of debugging if something goes wrong
  - Ideally you don't have to use them
- The HOST machine is your normal operating system (whatever you     normally use, e.g. Windows)
- The GUEST machine is the operating system that is running/going to     be run in Virtual Box (e.g. Ubuntu) One important thing, the HOST machine     is your normal operating system (whatever you normally run e.g. Windows),     the GUEST machine is the operating system that is running in Virtual Box     (e.g. Ubuntu)

### **1. Download and Install**

- Download the Ubuntu ISO file
  - Visit [this page](https://ubuntu.com/download/desktop)
  - Hit Download on the latest version (I didn't use LTS      - this stand for Long-Term Support)
  - Decide whether you want to pay or not
    - If you want to pay, click "Pay with       PayPal" and follow the prompts
    - If you don't want to, click "continue to the       download" or "not now, take me to the download"
  - ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image002.png)Start the      download and save the file in a place that you will remember (e.g. Downloads file)

 

-   
- While you are waiting for this download, you can      continue on with the following steps
- Visit the [Oracle Virtual Box page](https://www.virtualbox.org/wiki/Downloads)
- Click the link for the latest appropriate platform package     (currently the latest is 5.2.8). Note, by appropriate I mean the same as     your operating system - e.g. if you are on a Windows computer, select     Windows Host
  - [Windows](https://download.virtualbox.org/virtualbox/5.2.8/VirtualBox-5.2.8-121009-Win.exe)
  - [OSX](https://download.virtualbox.org/virtualbox/5.2.8/VirtualBox-5.2.8-121009-OSX.dmg)
- Once you have clicked that, save the file into a place you'll     remember (e.g. your Downloads folder)

![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image004.png)

- Run that file (double-click the file), follow the prompts and     install the application
- Once installed, open up the VirtualBox app

![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image006.png)

### **2. Create a Virtual Machine**

- Find out if you have a 64-bit or 32-bit CPU
  - Follow the steps [here](https://www.computerhope.com/issues/ch001121.htm)
- In the VirtualBox application, click the New Icon
- Define the Name and Operating System
  - Set the name to something      appropriate, e.g. "Linux (Ubuntu 64-bit)" (change 64 to 32 if      you are on a 32-bit CPU)
  - Set the type to      "Linux", or whatever is appropriate
  - Set the version to      "Ubuntu" 64-bit, or whatever is appropriate (change 64 to 32 if      you are on a 32-bit CPU)
  - ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image008.png)Click "Continue"
          
  
- Allocate the RAM for this Virtual Machine (Memory     Size)
  - Pick no less than the      recommended, the higher you go, the faster it will be (though stay within      the green section)
  - I picked 4096mb
  - Click "Continue"

![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image010.png)

- Create the Hard Disk
  - Select "Create a virtual      hard disk now"
  - ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image012.png)Click "Create"

 

- Define the Hard Disk File Type

- *You must have downloaded the Ubuntu ISO file (or       whatever OS you are installing) by this point. If you haven't, wait for       the download to complete or go back and start it (it is in "1.       Download and Install")*
- Select       "VDI (VirtualBox Disk Image)"
- ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image014.png)Click "Continue"

 

- Select       "Dynamically Allocated"
- Click       "Continue"

![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image016.png)

- Select       the File location and size. Make sure the size is at least 10.00GB
- ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image018.png)Click "Create"

 

### **3. Start the Virtual Machine for the first time**

- ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image020.jpg)Go to “Settings”     and click on “Storage”.
       
  
- ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image022.jpg)Click on “Empty”     and click on the disk icon on the right side then “Choose a disk file”.
       
  
- ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image024.png)Choose Ubuntu ISO file.

 

- ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image026.png)Click “Ok”
       
  
- ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image028.png)Press the "Start"     button

 

·    ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image030.png)Click on “Start”.


·    Click on try or install Ubuntu.

![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image032.jpg)

 

- ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image034.png)Choose language and press “Install     Ubuntu”

 

·    ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image036.png)Click on “continue”.




·    ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image038.png)Uncheck “Download updates while installing Ubuntu” and press “continue”.




·    Click “Install Now”.

![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image040.png)

 

·    ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image042.png)After choosing a location click on “continue” and write the required information.




·    ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image044.png)Wait until all the files are copied.




·    ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image046.png)Click on “Restart”.

 

 

·    ![img](file:///C:/Users/TLS~1/AppData/Local/Temp/msohtmlclip1/01/clip_image048.png)Press “Enter”.




·    Congratulations! you have achieved your goal.

 

**4)** **Configuring Compilers**

·    Open the Terminal in Ubuntu by pressing Ctrl + Alt + T.

·    Update the package lists by running the command:

```
sudo apt update
```

·    Install build-essential package, which includes compilers and build tools, by running:

```
sudo apt install build-essential
```

·    Verify the installation by checking the version of gcc (GNU Compiler Collection) with the command:

```
gcc --version
```

**Conclusion**

Congratulations! You have successfully installed Ubuntu distribution on your Virtual Machine and configured compilers.

GitHub Link: https://github.com/ShahbazShaddy/Operating_System_Lab