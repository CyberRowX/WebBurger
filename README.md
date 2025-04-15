![Blue Futuristic Technology Presentation](https://startechcrl.com/CyberRowX.png)

# WebBurger
This is a simple tool to automatically deface vulnerable websites.

(Tutorial video link at last of this page ⚠️)

It uses WebDav vulnerability to exploit.
This script sends a PUT requests to the websites given in the targets.txt file. Unauthenticated requests will be accepted and your html script will be uploaded in the website. You will get the link with your script whch you can see it. (sometimes it defaces the homepage directly.)

You need to put your website urls in the targets.txt file and put your deface script in the same folder ie: white-deface. then use the tool


# Note

⚠️Only defaces websites with WebDAV vulnerability(Accepts unauthenticated PUT requests)⚠️

Thank you [CyberRowX](https://facebook.com/CyberRowX)


# Installation
____________________

    apt update -y && apt upgrade -y
    pkg install git -y
    pkg install python -y
    pip2 install requests
    git clone https://github.com/CyberRowX/WebBurger
    cd WebBurger
    pip install -r requirements.txt
    git pull
    python tony.py
   
   
# Single installation command
_______________________________________

    apt update -y && apt upgrade -y && pkg install git -y && pkg install python -y && pip2 install requests && git clone https://github.com/CyberRowX/WebBurger && cd WebBurger && pip install -r requirements.txt && git pull && python tony.py
  
***Tutorial video : yourLink***

Tool used for vulnerable website defacing

Tool devoloped by Tony Stark 


Telegram : https://t.me/CyberRowX


# What the code does


The code is a simple program in Python that attempts to upload a provided HTML file to multiple websites as specified in a target file named "targets.txt". The uploaded HTML file is intended to replace the content of the index page on the target websites. The program uses the "requests" library to handle the HTTP requests. The user is asked to input the name or path of the HTML file to be uploaded. If the file is found, the program then reads the contents of the file and the "targets.txt" file, which contains a list of target websites. The program then loops through each website in the list and attempts to upload the HTML file using a HTTP PUT request. If the upload is successful, a message is displayed indicating that the upload was successful. If the upload fails, a message is displayed indicating that the upload failed.


***You can get a new version of this project named CyberRowX with many features to exploit WebBurger vulnerability. Click [here](https://github.com/CyberRowX/WebBurger) to go to the project.***


Tutorial video : videoLink


***You can get a new version of this project named WebBurger with many features to exploit WebBurger vulnerability. Click [here](https://github.com/CyberRowX/WebBurger) to go to the project.***

