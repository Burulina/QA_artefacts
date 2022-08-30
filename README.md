## Description 
1. This is telnyx.com test cucumber project ver. 1.0
Documentation for project (test cases) is located in the root directory in the "Docs" folder.

## Setup
1. Before using cypress with cucumber, you need download and install
- [last version of VS Code](https://code.visualstudio.com/) or any other IDE of your choice;
- [at least Node.js 14](https://nodejs.org/uk/download/).
2. Download git repository:
gi

## Steps to run
1. To run auto tests manually on local machine with Cypress test runner type:
- type ***"npm run cy_open"*** in termainal and press ***enter***;
- choose ***"E2E testing"*** and after ***"Chrome"***;
- click ***"Start E2E testing in Chrome"***;
- click on ***"*.feature"*** file in opened window and wait for auto test execution;


2. To run all auto tests manually on local machine with command line type in VS Code Terminal:
`npm run cy_run`

- Or with another config file:
~~~
npm run cy_staging_run
~~~

~~~
4. To generate HTML report after test execution type in VS Code Terminal:
 ***"cy_generate_report"*** and press ***enter***. 
 Generated report is located in the root directory in the "reports" folder, open ***"index.html"*** file to see report;  
 
~~~
5. Project included .yml file, which run auto tests from telnyx project in GitHub actions after every push on main branch of repository.
