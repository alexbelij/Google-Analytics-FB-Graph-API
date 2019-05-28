I have used the GOOGLE ANALYTICS API and FB GRAPH API to retrieve information about the campaigns runnning on google adwords and FACEBOOK.

CLONE the repository

Put the `Google Analytics` `API` Credentials in `auth.json`

Put the `Parse` `API` Credentials in `parseCredentials.json`

Put the `Facebook` `access_token` in the `access_token` key present in `parseCredentials.json`

`time.js` holds the date format which is used in all the api calls.

`Report.js` is the main file through which the function runs. 

Note -> You can make your own report.js file, in which you have to do following things:
        1: First Read about excel4node-npm module
        2: Then Use it in report.js file
        3: Require the other files, as you have seen that i have exported `arrayJson` from each file.
        4: Write the required excel generation code and run node report.js.
        
Any comments and feedbacks are welcome, THANKS.




