# Exit Test Project Info:

## Pakages Descriptions:
* com.apidemo.base; this package conatains TestBase class which contain the workbook initailizatin of excel file and startservice, launchandInstallApp, stopService etc function.
* com.apidemo.data; this package contains excel file which have data we needed for project.
* com.apidemo.screens; this package contains all selectos
* com.apidemo.utils; this package have all utilies  like commonUtils, LogUtils, ScreenShot.
* com.apidemo.feature; this package contains all the scanrio and feature descriptions.
* com.apidemo.runner; this package contains Run.java file which is resposible for run the cucucmber test.
* com.apidemo.stepdefinition; this package have all step defintion file for all feature files.

### main/java/base description:
* TestBase.java - this class contains all capablities and launch and install and service start & service end Function.

### main/java/screens description:
* TestBase.java
* AppOptionScreen.java
* HomeScreen.java
* OSScreen.java
* RecieveResultScreen.java
* SMSMessagingScreen.java
* ThemeScreen.java
* ViewsOptionScreen.java
* VisibilityScreen.java

These classes contains selectors for element which we used to hit the android element.

### main/java/utils description:
* CommonUtils.java; this class contains all the common function.
* LogUtils.java ; this file contains cod for log
* ScreenShots.java; this file is used for taking the screen shot of failed testcases.


### test/java/feature
* ReceiveResultFeature.feature
* SMSMessagingFeature.feature
* ThemeScreenFeature.feature
* VisibilityScreenFeature.feature

These classes all feature file conatins all step of feature in Ghenkin language

### test/java/stepdefinintion
* HookFile.java; this file contains hook
* ReceivingResultStepdefinition.java
* SMSMessagingStepDefinition.java
* ThemeScreenStepDefinition.java
* VisibilityScreenStepDefinition.java
* WhenStepDefinition.java

These file hava defintion for all step in feature files

### recources folder description
this folder have .apk file, extent.propterties, log4j2.properties

### cucumber-report folder description
this folder have json and html reports of the project


### log folder description
log folder MYLogs.log file which contians all the log after run the project.

### screenshot folder description
screenshot folder screenshot of failed test cases.

#####Note : Anyone can run the project by just click on 'run.bat' or go to TestNG.xml then right click thens run as 'TestNG Suit'


 

