# _Doctor_Search_

![alt text](/img/results.png)

#### _Implementing API and Asynchrony in JavaScript, 10.20.2017_

#### By _Michael A. Brooks_

## Description

_Create an app using an API call to BetterDoctor to search for medical providing by user's medical issues or by doctor name._

## Specs

* _A user should be able to enter a medical issue to receive a list of doctors in the Portland area that fit the search query._
* _A user should be able to to enter a name to receive a list of doctors in the Portland area that fit the search query._
* _If the query response includes any doctors, the following information should be included about each doctor: first name, last name, address, phone number, website and whether or not the doctor is accepting new patients (the API provides this data)._
* _If the API call results in an error (any message not a 200 OK), the application should return a notification that states what the error is._
* _If the query response doesn't include any doctors (for instance, if no doctors meet the search criteria), the application should return a notification that states that no doctors meet the criteria. (This is not an error so it should be handled separately from any errors.)_

## Setup/Installation Requirements

* _clone project from GitHub.com_
* _navigate to https://developer.betterdoctor.com/ and sign up for your free API key_
* _create a .env file in your project root directory and copy in
`exports.apiKey = "YOUR_API_KEY_HERE";`
* _in project directory via terminal run:_
* `npm install`
* `bower install`
* `gulp build`
* `gulp serve`
* _navigate your browser to localhost:3000_

## User experience screenshots:

Example search result:

![alt text](/img/example.png)

Example error response: 

![alt text](/img/error.png)

## Known Bugs

_Location search needs rewritten to be able to take in input by zipcode.  Currently location works and returns correct results but has a very restrictive input of or-portland type formatting, not acceptable in user experience._

## Support and contact details

_If you have any updates or suggestions please contact [Michael A. Brooks] or make a contribution yourself._

[Michael A. Brooks]: mailto:mikealphabravo1982@gmail.com

### License

MIT License

Copyright (c) 2017 Michael A. Brooks
