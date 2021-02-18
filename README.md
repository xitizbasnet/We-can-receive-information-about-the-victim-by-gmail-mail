# We-can-receive-information-about-the-victim-by-gmail-mail
We can receive information about the victim by gmail mail



 I want to tell you about a very cool osint tool for collecting information from mail.
 

 This is the data you will receive with only mail:
 

 - Owner's name
 - Date of last edit
 - Google id
 - Activated Google services (
 - Possible YouTube channel
 - Possible names
 - Public photos
 - Phone models
 - Firmware phones
 - Installed software
 - Reviews about Google Maps
 - Possible physical location
 - 

 Installation takes place in the terminal
 To do this, we enter into Termux one by one:
 

 apt update
 

 apt upgrade
 

 apt install git python
 

 git clone https://github.com/mxrch/GHunt
 

 pip3 install -r requirements.txt
 

 python check_and_gen.py
 

 And like this, we start the search by mail:
 

 python hunt.py example@gmail.com
 

