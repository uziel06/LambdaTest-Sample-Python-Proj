# LambdaTest-Sample-Python-Proj
A simple cross-browser testing on LambdaTest Platform

This project is an example of how to run an Automated Test on LambdaTest Platform.

* You need to register an account first in https://www.lambdatest.com/

To configure the project, replace the username and accessKey in the conftest.py with your own username and accessKey that will be provided by lambdatest after logging in to their app.

Then for you to be able to run the test, type and execute the following command in the terminal:

pytest -s -v -n=1

or

py.test -s -v -n=1

-n serves as the number of cpu's
