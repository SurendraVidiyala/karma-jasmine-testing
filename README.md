# karma-jasmine-testing
- unit testing in your Angular applications. You will learn about Angular mocks, Karma, and      Jasmine and learn how to use them to carry out unit testing and e2e testing.
  - Configure a Karma configuration file and Set up unit tests using Jasmine and carry out the   unit test automatically
  - Setting up the Unit Test Environment
- First, set up Jasmine core to be available for use within your project:

# install karma and karma-jasmine

```````
npm install karma --save-dev
npm install jasmine-core --save-dev
````````
- Then, set up the Karma command line tools globally as follows:

``````
     npm install karma-cli -g
``````

Remember to use sudo if you are in OSX or Linux environments.
Then set up karma-jasmine plugin to make use of Jasmine with Karma:
``````````
     npm install karma-jasmine --save-dev
````````````
- In order to set up browser environments to carry out the tests, set up PhantomJS, and Karma launchers for PhantomJS and Chrome as follows:

````````
     npm install phantomjs karma-phantomjs-launcher karma-chrome-launcher karma-edge-launcher  --save-dev
`````````` 

- You can also set up for Firefox, IE and Safari if you use these browsers.
Setting up Angular Mocks
You should also install the ngMock module as follows:

``````````
     bower install angular-mocks -S
``````````````

