This contains what you need to run JMeter scripts coded to invoke "The Internet" sample app that contains screens one can encounter.
Dave Hoeffer wrote it for Selenium functional testers use to validate their skill.
We're invoking it here to discuss best practices for coding JMeter, structuring GitHub, etc.

## Setup

This repository has everything, with the exception for Java VM, you need to run Apache Jmeter We use .envrc to automatically configure your path. If you do not use direnv you have to run a bash shell and run the command

`source .envrc`

Verify that jmeter is on your path by typing which jmeter


NOTE: This is based on the structure of folders at
* https://github.com/jmeterbyexample/jmeter-test-scripts
* https://github.com/Sunbird-Ed/sunbird-perf-tests
* https://github.com/cf-identity/jmeter pulls in Apache JMeter so that new versions will not break runs by my scripts here.
   It also contains png files of metrics generated during the last run.

* https://github.com/apolloclark/jmeter
* https://github.com/mozilla/jmeter-scripts
