# check_in_thingy
check in thingy
- install CORS unblock extension on browser firefox or whatever, it will need to be on at all times so might as well do it on a browser you dont usually use
- set up task in windows task scheduler
- set up the triggers ( weekly->tick all weekdays)
- acction program: "C:\Program Files\Mozilla Firefox\firefox.exe", arguments: (your html file's location)
- download ifttt on your phone:
- create widget: location trigger - > add row to google spreadsheet
- go to your google spreadsheet:
- publish it
- in sharing options, set to allow all with link to access
- copy the sharing link
- go to the checkIn.html file:
- fill in the variables from officeLoginUrl to staffLoginToken
- sheetId is the long string in your sheet's share url
- sheet number should be default as 1
- you might want to test run the html file by running it in the browser you have CORS unblock in to make sure it goes well
- you will not be able to double check in and overwrite your previous check in time with the goToWorkLight api so dont worry
- you might want to still open up your portal after checking in for the first couple of days at the front gate just to make sure everything went well
- button spreedsheet -> button widget, proximity spreed sheet -> location widget
