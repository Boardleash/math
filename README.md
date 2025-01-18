# math
![Alt text](./images/euclid_glitched.png)

Bash script that performs basic math functions, in addition to a few algebraic equations for various shapes/objects.

## Description

***eq_calculatr*** is an interactive bash script that will pull perform basic and some algebraic math on objects such as cubes, spheres, etc.  In addition to this, the user can select which unit of measurement they prefer.

The intent behind the script started out as just a basic math calculator, but then there was an interest in trying to get in some other equations.  This script consists of the following equations:

>	*Basic Math*
>
>		*- Addition*
>		*- Subtraction*
>		*- Multiplication*
>		*- Division*
>		
>	*Area Math (for the following objects):*
>
>		*- Square*
>		*- Rectangle*
>		*- Triangle*
>		*- Circle*
>		*- Ellipse*
>		
>	*Surface Area Math (for the following objects):*
>
>		*- Cube*
>		*- Sphere*
>		*- Cylinder*
>		
>	*Volume Math (for the following objects):*
>
>		*- Cube*
>		*- Sphere*
>		*- Cylinder*

The user will be asked if they would like some calculations to be performed.  If they are not interested, they can simply type "***no***" at the initial prompt.

If the user is interested in some math being performed, then they can answer the first prompt, which is to enter a number between -100 and 100, excluding 0.  The second prompt will ask for the same information.

## Limitations

This script is created to only use **two numbers** to perform math on.  Additionally, there is the limitation of numbers being **a range of -100 to 100, excluding zero**.

The number "pi" is limited to 3.14159.  There is a **decimal limit set to 5 places**, so using pi as an example above, only 5 numbers after the decimal are permitted for answer outputs.
## Technologies Used

The script within the "**centos**" directory has been tested in the CentOS Stream 9 distribution, in both graphical and multi-user targets (GUI and Server). The script within the "**ubuntu**" directory has been tested in the Ubuntu 24.04 LTS distribution, also in both graphical and multi-user targets.

The CentOS version of the script should also work with other similar flavors like Red Hat Enterprise Linux (RHEL), Fedora, Oracle, etc.

The Ubuntu version of the script should also work with similar Ubuntu flavors and Debian based distributions like Kali, Kubuntu, Parrot OS, etc.

This script does utilize the "**bc**" utility to facilitate a majority of the math functions.  This utility my not be native to your distribution and may require installing.  Having this installed is HIGHLY recommended for use of this script.  If the script is ran without the "**bc**" utility being available, the output will be very limited and potentially useless.

### OPTIONAL: How to Download and Install "bc"

**For CentOS**
>	- Elevate your privileges by either using "***sudo***" or switching to root user with "***su***"
>	- Type the following: `dnf install bc -y`
>	- The install will begin

**For Ubuntu**
>	- Elevate your privileges by either using "***sudo***" or switching to root user with "***su***"
>	- Type the following: `apt install bc -y`
>	- The install will begin
## How To Download and Use

###### Method 1: Directly from my GitHub Repository

> If not already in the repository, access it via the link below: [https://github.com/Boardleash/math/]

> Click on either "**centos**" or "**ubuntu**" (based on whichever OS you are using)

> Click on the "**eq_calculatr**" file and then click on the download raw file option.

> After the download is complete, go to where you downloaded the file. The file will likely have been downloaded as a text file (.txt extension). Rename the file to "**eq_calculatr**" (don't inlcude the .txt extension).

> Right click the file and click on "**Properties**", then click on the "**Permissions**" tab. Check the "**Allow executing file as program**" box.

> After doing the above, you can right click on the file and select the "**Run as a program**" option. The script will open a terminal session and execute.

###### Method 2: Via the Terminal

> In your terminal, navigate to the directory that you wish to clone the repository into: `cd <DIRECTORY TO CLONE REPO INTO>`

> In the directory that you have just changed into, type the following:
> 
> > `git clone https://github.com/Boardleash/math/`

> This should successfully clone the entire **math** repository into the directory that you have chosen and you are now able to access the contents locally on your terminal

> Navigate to where the "***eq_calculatr***" script is located. By default this should be in `/PATH/TO/math/centos/` OR `/PATH/TO/math/ubuntu/,` but if this script was moved, then navigate to that appropriate directory.

> Change file permissions for the script by typing the following: `chmod 755 eq_calculatr`

> Run the script by typing the following: `./eq_calculatr`

> The script will proceed.  It will ask you a few questions and then perform some math.
