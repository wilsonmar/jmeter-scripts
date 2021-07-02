This contains what you need to run sample JMeter scripts.

Several sample applications are used as the basis for learning and discussing best practices:

   * In "The-Internal" folder are scripts to invoke "The Internet" sample app Dave Hoeffer wrote for Selenium functional testers use to validate their skill. This is similar to https://wilsonmar.github.io/flood-the-internet/#challenges-on-the-internet-app


## Setup

Scripts in this repo can be run in Blazemeter (using a free account) for single transactions only (not performance/load tests).
That's simpler than setting up JMeter on your laptop (even on a Chromebook with no local storage).

1. Get account
2. ...

But if you're editing scripts, install JMeter on your laptop:

1. TODO:
2. If you're running on your local laptop, to automatically configure your path if you do not use direnv:

   `source .envrc`

3. Verify that jmeter is on your path by typing which jmeter

To run performance/load tests, we spin up instances of "The-internet" app in a cloud (AWS, Azure, GCP, etc.):

1. TODO ...


## References

NOTE: This is based on the structure of folders at
* https://github.com/jmeterbyexample/jmeter-test-scripts
* https://github.com/nighteblis/JmeterBook is a JMeter tutorial in Chinese and English at https://translate.google.com/translate?hl=&sl=auto&tl=en&u=https%3A%2F%2Fwww.hissummer.com%2F
* https://github.com/Sunbird-Ed/sunbird-perf-tests
* https://github.com/cf-identity/jmeter pulls in Apache JMeter so that new versions will not break runs by my scripts here.
   It also contains png files of metrics generated during the last run.
* https://github.com/ambertests/JMeterExamples has a PropExample.jmx - Script which takes properties from the command-line

Others:
* https://github.com/apolloclark/jmeter
* https://github.com/mozilla/jmeter-scripts
