# **Instagram-Account-Creator**

This project is a branch of https://github.com/beephole/instagram-Account-Creator/
with the help of project https://github.com/cubicbyte/tempmail-python
I have completed this project.

THIS BOT IS FOR FUN AND EDUCATIONAL PURPOSES PLEASE BE NICE WITH IT!

With the help of this project you can generate instagram accounts


Hi there ! This is a selenium bot that Creates Instagram Accounts . It saves the credentials in a .txt file !

You can Generate Accounts using free Proxy, the Bot will grab free proxys from "https://free-proxy-list.net" and it will
test them if they Work. If yes the Ip is going to be added on the proxylist.txt and then randomly used to Create an account.


## *HOW TO INSTALL*
```      
git clone https://github.com/Master-kp/instagram-Account-Creator.git
```
```
cd  instagram-Account-Creator
```
```
pip install -r requirements.txt
```
```
python generateAccount.py
```


### **WORK TO BE DONE BEFORE STARTING THE BOT**

1. Download Chromedriver(Check for Version of Chromedriver and your Chrome Browser it should be the same)

2. Check your Chromedriver PATH and edit with your PATH at the script

   > line 95 - generateAccount.py
   
   
   > Ex. Download Chromedriver and move it from downloads to Program Files (x86) 
   > and the PATH should be ok!
   


*PAY ATTENTION*

1. New Username is saved at username.txt
2. Free Proxys are added to proxylist.txt and then chosen randomly .
3. Password is going to be the same for all accounts.(You can change it.)
4. Too many requests with the same proxy ,may get banned the proxy from the website you're sending requests at,
   You have to have over 5 proxys , the bot will choose a random proxy each time an account is being created !

This creates 1 account per 64 seconds (due to sleep functions you can decrease them as you like)


Author : Kushagra Pal (https://github.com/Master-kp) and
         cubicbyte (https://github.com/cubicbyte) and
         beephole (https://github.com/beephole)

Thanks to beephole for base project and cubicbyte for wrapper of 1secmail

