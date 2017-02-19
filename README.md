# Setting up Jasmine Karma and TestBed for Ionic2 / Angular2

## Optional
If you are just starting, create you project
```
ionic start ionic2.yourAppName blank --v2
cd ionic2.yourAppName

```

## 1. Dependencies 

### Global 
```
npm install -g karma-cli
```
### Local
```
npm install angular-cli --save-dev
npm install codecov --save-dev
npm install jasmine-core --save-dev
npm install jasmine-spec-reporter --save-dev
npm install karma --save-dev
npm install karma-chrome-launcher --save-dev
npm install karma-jasmine --save-dev
npm install karma-mocha-reporter --save-dev
npm install karma-remap-istanbul --save-dev
npm install ts-node --save-dev
npm install tslint --save-dev
npm install tslint-eslint-rules --save-dev
npm install @types/jasmine --save-dev
npm install @types/node --save-dev
karma init karma.conf.js

```
After the last command you just have to put continue(enter) to all the options.

If you want to run all at once you can use 
>npm install angular-cli --save-dev && npm install codecov --save-dev && npm install jasmine-core --save-dev && npm install jasmine-spec-reporter --save-dev && npm install karma --save-dev && npm install karma-chrome-launcher --save-dev && npm install karma-jasmine --save-dev && npm install karma-mocha-reporter --save-dev && npm install karma-remap-istanbul --save-dev && npm install ts-node --save-dev && npm install tslint --save-dev && npm install tslint-eslint-rules --save-dev && npm install @types/jasmine --save-dev && npm install @types/node --save-dev && karma init karma.conf.js

That comes from:
```
A; B    Run A and then B, regardless of success of A
A && B  Run B if A succeeded
A || B  Run B if A failed
A &     Run A in background.
```
## 2. Files
Copy all the files form this repository

