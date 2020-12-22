# scrapbox-alfred-workflow
Scrapbox Alfred workflow

To search in the Scrapbox project (both public and private), as well as to create new notes.

depends on [scrapbox go cli](https://github.com/ohtomi/scrapbox)

![workflow screencast](https://i.gyazo.com/6a5b23660e0d2964f65b7ed29a0d33bb.gif)

# Installation
1. install [scrapbox go cli](https://github.com/ohtomi/scrapbox)
2. install [workflow package](https://github.com/vitalibondar/scrapbox-alfred-workflow/releases/) into alfred
3. specify environment variable
  - *gohome* : your go home path
  - *site* : your scrapbox project name
  - *token* : your scrapbox auth token(in scrapbox.io cookie "connect.sid" value)
  - ![variable setting dialog button and setting value](https://i.gyazo.com/dcb822d00460b159c0f141d499135a0b.png)
  - ![connect.sid (token)](https://i.gyazo.com/14db15332b6395cf6737dfd8160a2b9b.png)
  
# Usage
- keyword "sb" : search scrapbox pages
  - enter: open selected scrapbox page
- keyword "sb:new" : create new page
  - arg: new page title
  - enter: open new scrapbox page with title
  
# Credits
Created by dotimpact, modified by Vitali Bondar
