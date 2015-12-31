BrowserStack-Runner Jasmine Sample
==============

Sample project to run Jasmine tests on BrowserStack using BrowserStack-Runner

###Clone this repository
- `git clone https://github.com/UmangSardesai/Comparators.js.git`

###Install browserstack-runner
- `npm install browserstack-runner`

###Configuring the json
 - Open `browserstack.json`
 - Since these are Jasmine tests, `test_framework` parameter will be `jasmine2`
 - Add `username` and `automate-key`. These credentials are available [here](https://www.browserstack.com/accounts/automate), after you haved logged in to your account.

###Sample test
 - To run: `browserstack-runner`
