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

### Step 1- Download jmeter-scripts Repo from GitHub

1. Navigate to https://github.com/wilsonmar/jmeter-scripts

![DJMSR_01](https://user-images.githubusercontent.com/10678180/124376825-6b524880-dc6e-11eb-8c13-4205efcdd6d5.png)

2. Click on Code and click on Download ZIP.

![DJMSR_02](https://user-images.githubusercontent.com/10678180/124376826-6beadf00-dc6e-11eb-9d1b-ff0470020591.png)

Zip file is downloaded.

![DJMSR_03](https://user-images.githubusercontent.com/10678180/124376827-6beadf00-dc6e-11eb-9c48-505a9ce27c1c.png)

3. Navigate to download folder and unzip the folder. You may save the unzipped folder to your desired location, or you can access from download folder.

![DJMSR_04](https://user-images.githubusercontent.com/10678180/124376828-6beadf00-dc6e-11eb-8ebb-660be859ce9f.png)

jmeter-scripts-main folder is unzipped.

![DJMSR_05](https://user-images.githubusercontent.com/10678180/124376829-6beadf00-dc6e-11eb-9230-d0ea2d318963.png)

### Step 2 – Sign up for BlazeMeter Account

1. Navigate to https://www.blazemeter.com/

![BMA_01](https://user-images.githubusercontent.com/10678180/124376016-8cb13580-dc6a-11eb-91cc-42471ddcfbb2.png)

2. Click on Start Testing Now Link.

![BMA_02](https://user-images.githubusercontent.com/10678180/124376017-8cb13580-dc6a-11eb-9b86-1f556e08b07c.png)

3. Enter First name, Last name, Email and Click on REGISTER link.

![BMA_03](https://user-images.githubusercontent.com/10678180/124376019-8cb13580-dc6a-11eb-817c-4219670a39ce.png)

4. Pop up screen appears. Click on Close.

![BMA_04](https://user-images.githubusercontent.com/10678180/124376022-8d49cc00-dc6a-11eb-9705-0245e808e007.png)

![BMA_05](https://user-images.githubusercontent.com/10678180/124376023-8d49cc00-dc6a-11eb-93d3-23948d8240a7.png)

Congratulations! You have now created a BlazeMeter Account.

### Step 3- Run JMeter Scripts on BlazeMeter
1. Click on Projects and click on create new project.

![RJMSFBM_01](https://user-images.githubusercontent.com/10678180/124377429-7e1a4c80-dc71-11eb-8ed0-65f651434ece.png)

2. Provide a name “the-internet” and click on Create project.

![RJMSFBM_02](https://user-images.githubusercontent.com/10678180/124377514-e5380100-dc71-11eb-967b-fe3384064be8.png)

3. Click on Create New Test link.

![RJMSFBM_03](https://user-images.githubusercontent.com/10678180/124377779-68a62200-dc73-11eb-9b9f-179165e16c15.png)

4. Click on Performance Test link.

![RJMSFBM_04](https://user-images.githubusercontent.com/10678180/124377780-693eb880-dc73-11eb-855b-abecae3a10c2.png)

5. Navigate to your previous downloaded “jmeter-scripts-main” folder and upload the script which you want to run by clicking on the Plus Sign.

![RJMSFBM_05](https://user-images.githubusercontent.com/10678180/124377781-693eb880-dc73-11eb-9e64-03e9195a4983.png)

In my case

C:\Users\anilm\Projects_wWilsonMar\jmeter-scripts\the-internet.

![RJMSFBM_06](https://user-images.githubusercontent.com/10678180/124377783-693eb880-dc73-11eb-9683-5e681a72de5b.png)

The script is uploaded onto BlazeMeter.

![RJMSFBM_07](https://user-images.githubusercontent.com/10678180/124377785-693eb880-dc73-11eb-8668-7de90ce33579.png)

6. Next, Complete the Load Configuration.Set up total users - 1 User, Duration - 5 Minutes and ramp up time - 1 Min

![RJMSFBM_08](https://user-images.githubusercontent.com/10678180/124377923-4660d400-dc74-11eb-8281-d35990dceb43.png)

7. Next, set up the load distribution. Select the desired location for LG.

![RJMSFBM_09](https://user-images.githubusercontent.com/10678180/124378163-a86e0900-dc75-11eb-882e-0a6f7c37eb64.png)

8. Click on Debug Test.

![RJMSFBM_10](https://user-images.githubusercontent.com/10678180/124378164-a86e0900-dc75-11eb-9f7e-e105ecd3898f.png)

9. Click on Start Debug Run.

![RJMSFBM_11](https://user-images.githubusercontent.com/10678180/124378165-a86e0900-dc75-11eb-9a2a-a743117f9aac.png)

Warming Up message

![RJMSFBM_12](https://user-images.githubusercontent.com/10678180/124378166-a9069f80-dc75-11eb-80a0-63d3d211d5fd.png)

Your test will begin shortly message. Wait for some time until the test starts.

![RJMSFBM_13](https://user-images.githubusercontent.com/10678180/124378167-a9069f80-dc75-11eb-8887-7bd6e04df3e2.png)

The Load Test starts.

![RJMSFBM_14](https://user-images.githubusercontent.com/10678180/124378168-a9069f80-dc75-11eb-8d88-a99ba5aa4413.png)

The test completes after 5 Min with 0 % Errors

![RJMSFBM_15](https://user-images.githubusercontent.com/10678180/124378169-a9069f80-dc75-11eb-91ad-36288f06e276.png)

Congratulations! Now you have learnt how to Downloaded Repo from GitHub, Sign Up and run a test using BlazeMeter.

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
