IRS-CS-2019-04-27-IS01PT-GRP-AMAB
---

## SECTION 1 : PROJECT TITLE
ISS AMAB 
(ASK-ME-ANYTHING-BOT)

---
## SECTION 2 : EXECUTIVE SUMMARY / PAPER ABSTRACT
A Chatbot (sometimes referred to as a chatterbot) is a computer program that attempts to simulate the conversation of a human being via text or voice interactions.
Commands or inputs are received from the user and the Chatbot will respond in a satisfactory way to the user which results in the completion of the action or conversation initiated by either of them.
This project aims to provide a viable Chatbot for NUS ISS website.   

---
## SECTION 3 : CREDITS / PROJECT CONTRIBUTION

| Official Full Name  | Student ID (MTech Applicable)  | 
| :------------ |:---------------:| 
| KHOO WEE BENG | A0195308Y | 


---
## SECTION 4 : VIDEO OF SYSTEM MODELLING & USE CASE DEMO

[![Power Supplier Recommender](http://img.youtube.com/vi/mmfMunHuYzE/0.jpg)](https://youtu.be/mmfMunHuYzE "Power Supplier Recommender")

---
## SECTION 5 : USER GUIDE
### [ 1 ] To run the system using iss-vm

> download pre-built virtual machine from http://bit.ly/iss-vm

> start iss-vm

> open terminal in iss-vm

> $ git clone https://github.com/dion797/IRS-CS-2019-04-27-IS01PT-GRP-AMAB.git

### as there is an existing npm of lower version, upgrade npm with the following instructions

> open terminal in iss-vm

> $ sudo npm cache clean -f

> $ sudo npm install -g n

> $ sudo n stable

### find folder installed for new npm
### usually during mkdir e.g. “/usr/local/n/versions/node/10.16.0/bin”
### symlink nodejs to /usr/bin/node

> ln -s /usr/local/n/versions/node/10.16.0/bin /usr/bin/node

### if link exists, 'unlink /usr/bin/node' first than execute the command above

> go to IRS-CS-2019-04-27-IS01PT-GRP-AMAB/SystemCode/ folder in 'Files'

> unzip dialogflow-web-v2.zip into dialogflow-web-v2 folder

> go to terminal

> $ cd IRS-CS-2019-04-27-IS01PT-GRP-AMAB/SystemCode/dialogflow-web-v2/

> $ npm install

> $ npm run dev

> go to IRS-CS-2019-04-27-IS01PT-GRP-AMAB/SystemCode/ folder in 'Files'

> **open iss.html in Chrome

### [ 2 ] To run the system in other/local machine:
### Install npm, get latest nodejs n npm

> $ sudo apt-get update

> $ sudo apt-get install npm 

> $ git clone https://github.com/dion797/IRS-CS-2019-04-27-IS01PT-GRP-AMAB.git

> go to IRS-CS-2019-04-27-IS01PT-GRP-AMAB/SystemCode/ folder in 'Files'

> unzip dialogflow-web-v2.zip into dialogflow-web-v2 folder

> go to terminal

> $ cd IRS-CS-2019-04-27-IS01PT-GRP-AMAB/SystemCode/dialogflow-web-v2/

> $ npm install

> $ npm run dev

> go to IRS-CS-2019-04-27-IS01PT-GRP-AMAB/SystemCode/ folder in 'Files'

> **open iss.html in Chrome

---
## SECTION 6 : PROJECT REPORT / PAPER

amab.pdf
`<Github File Link>` : <https://github.com/dion797/IRS-CS-2019-04-27-IS01PT-GRP-AMAB/blob/master/ProjectReport/amab.pdf>

---
## SECTION 7 : MISCELLANEOUS

ChatBot.xlsx
`<Github File Link>` : <https://github.com/dion797/IRS-CS-2019-04-27-IS01PT-GRP-AMAB/blob/master/Miscellaneous/ChatBot.xlsx>

---
