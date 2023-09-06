# app-percy-react-demo
 


Steps to configure Percy: 
1)	Create a project account with Percy; It will create a NEW token for the new project.
2)	Install @percy/webdriverio
$ npm install --save-dev @percy/cli @percy/webdriverio
3)	Write a test script with WebdriverIO
4)	Set PERCY_TOKEN environment variable based on OS you are using
set PERCY_TOKEN=XXXXXXXXXXX
5)	Run the Test Project and go to App Percy website to see the screenshots comparison
npx percy exec wdio run ./wdio.config.js --spec test/specs/VisualTestUsingPercyTest.js

 
 

6)	Open Percy.io to open the screenshots build uploaded for comparison.
 

REFERENCES: 
1)	App Percy Website: WebdriverIO with Javascript: [WebdriverIO for JavaScript (percy.io)](https://docs.percy.io/v2-app/docs/webdriverio-for-javascript-1)https://docs.percy.io/v2-app/docs/webdriverio-for-javascript-1

