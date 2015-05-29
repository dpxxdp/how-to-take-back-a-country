# how-to-take-back-a-country
###winding back voter turnout to 1876

Thank you for stopping by.  The end game is to make it as easy for people to vote as it ever has been.  Given **the internet** this seems like it should be a simple task.  And it is, if we crowd source the heavy work.  Which is why we need as much of your time as you're willing to give to take back your country.

We're going to try to take this task in increments, but our first project is below.   If you are not comfortable with working in json, write the below information in simple bullet form and email it to dpxxdp@gmail.com.  Better yet if you have time, make a Google Spreadsheet and start filling in data.  The data fits a relational model pretty well so that would be immensely helpful actually.

###Current Project

We are currently working on [registration.json](./registration.json)  This file contains all the information voters need to register for their party's primary no matter what state they're in.  But it's a work in progress so we need your help to build it.

Please pick your home state and do a little research.

 Pick your favorite party (or both) and add the following data:
       * Registration Deadline (yyyy-mm-dd)
       * List of Registration Methods (ie. email, mail, in person, etc.). 
            For each method add instructions broken down into easy steps. Be specific and
            include necessary phone-numbers, links, and addresses.  
            Don't include extraneous information- we want to provide the path of least resistence.
      * Add links to all of your sources.

 If someone else has already filled your state in, verify that the information is correct and up to date.
 If you have time, do research into a state that has not yet been done.
 
 Sample format:
 
 ```json
     {
        "name": "Massachusetts",
        "abbreviation": "MA",
        "parties": {
            "Democrat": {
                "registrationDeadline": "",
                "registrationMethods" : [
                    {
                      "method": "internet",
                      "instructions": ["step1","step2","step3"],
                      "sources": [],
                    },
                    {
                      "method": "mail",
                      "instructions": ["step1", "step2", "step3"],
                      "sources": [],
                    },
                    {
                      "method": "inPerson",
                      "locations": [],
                      "sources": [],
                    },
                    {
                      "method": "phone",
                      "instructions": ["step1", "step2", "step3"],
                      "sources": [],
                    },
                ],
            },
            "Republican": {
                "registrationDeadline": "",
                "registrationMethods" : [
                    {
                      "method": "internet",
                      "instructions": ["step1","step2","step3"],
                      "sources": [],
                    },
                    {
                      "method": "mail",
                      "instructions": ["step1", "step2", "step3"],
                      "sources": [],
                    },
                    {
                      "method": "inPerson",
                      "locations": [],
                      "sources": [],
                    },
                    {
                      "method": "phone",
                      "instructions": ["step1", "step2", "step3"],
                      "sources": [],
                    },
                ],
            },
        },
    },
 ```
 
 
 
 
 
 
