This contains what you need to run sample JMeter scripts.

Several sample applications are used as the basis for learning and discussing best practices:

   * In "The-Internal" folder are scripts to invoke "The Internet" sample app Dave Hoeffer wrote for Selenium functional testers use to validate their skill. This is similar to https://wilsonmar.github.io/flood-the-internet/#challenges-on-the-internet-app

Several people contributed to this project:
   * Anil Mainali 
   * Wilson Mar
   * <em>How about you?</em>

They may be available for tutoring.

## Setup

Apache JMeter is a Git submodule to ensure that the scripts continue working even when JMeter is changed.
Also, submodules provide a way to analyze what went wrong (for forensics).

See https://devcenter.heroku.com/articles/git-submodules

Scripts in this repo can be run in Blazemeter (using a free account) for single transactions only (not performance/load tests).
That's simpler than setting up JMeter on your laptop (even on a Chromebook with no local storage).

### Step 1 – Sign up for BlazeMeter Account

1. Navigate to https://www.blazemeter.com/

![BMA_01](https://user-images.githubusercontent.com/10678180/124376016-8cb13580-dc6a-11eb-91cc-42471ddcfbb2.png)

2. Click on Start Testing Now Link.

![BMA_02](https://user-images.githubusercontent.com/10678180/124376017-8cb13580-dc6a-11eb-9b86-1f556e08b07c.png)

3. Enter First name, Last name, <strong>business</strong> email (not Gmail), Company and Click on REGISTER link.
4. Pop up screen appears. Click on Close.

Congratulations! You have now created a BlazeMeter Account.

### Step 3- Run in JMeter Scripts Blazemeter

TODO:

## Run JMeter scripts on laptop

But if you're editing scripts, install JMeter on your laptop:

### Step 1- Download jmeter-scripts Repo
1.	Navigate to https://github.com/wilsonmar/jmeter-scripts
2.	Click on Code and click on Download ZIP.
3.	Zip file is downloaded.
4.	Navigate to download folder and unzip the folder. You may save the unzipped folder to your desired location, or you can access from download folder later.

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
