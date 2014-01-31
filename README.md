# se-tests
## Selenium + Nightwatch Test Runner

[Nightwatch](http://nightwatchjs.org/) is a testing solution that uses the Selenium WebDriver API
to run tests written in Node.js.

### Install
By default the tests run in Firefox. Make sure it is installed on your computer.
Clone the repo and run ```npm install```

### Run Tests
cd into the directory in which it is cloned and run ```npm test```

Test output will be displayed in the console and in the reports folder.

### Write Tests
By default, tests live in the tests directory. Any files within the directory will be run automatically.
The settings.json file holds configuration for Nightwatch, the details of which be found [here](http://nightwatchjs.org/guide#settings-file)
