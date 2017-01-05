# ionic2-tests
Easy way to add tests to Ionic 2 project 

Install the dependencies:

     npm install --save-dev @types/jasmine @types/node angular-cli jasmine-core karma karma-chrome-launcher karma-cli karma-   jasmine karma-mocha-reporter karma-remap-istanbul

Run this commands to get the files into your project:

    for file in angular-cli.json karma.conf.js
    do
      wget https://raw.githubusercontent.com/drdpedroso/ionic2-tests/master/${file}
    done

    cd src

    for file in mocks.ts polyfills.ts test.ts tsconfig.test.json
    do
      wget hhttps://raw.githubusercontent.com/drdpedroso/ionic2-tests/master/src/${file}
    done
