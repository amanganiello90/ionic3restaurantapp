
# Ionic 3 Restaurant App

<img src="https://img.shields.io/github/stars/amanganiello90/ionic3restaurantapp.svg">&nbsp;<a href="https://github.com/amanganiello90/ionic3restaurantapp/issues"><img src="https://img.shields.io/github/issues/amanganiello90/ionic3restaurantapp.svg"></a>&nbsp;



**For the live demo app click** [here](https://appetize.io/app/6w0f663wabmmznbkp8wyrb4ghr?device=nexus5&scale=75&orientation=portrait&osVersion=7.1)

To download the free demo ANDROID APP INSTALLER FILE (APK) click  [here](https://github.com/amanganiello90/ionic3restaurantapp/raw/apk/ionic3restaurant.apk)

This project includes a full working PhoneGap/Ionic project
source code. It's ready to integrate (almost) any API all the Services logic are written there.


> You can also view the **Angular 5 app with web app site and admin dashboard** version (full apps to load products with CRUD api) on [Angular 5 restaurant web app](https://github.com/amanganiello90/restaurantwebapp)

|For a donation | [![](https://www.paypal.com/en_US/IT/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=XTC895QYD28TC) |
|:------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------|

Overview
========

Specifically, your pack consists of the following four
directories:

    * [project]
      Includes a Ionic Cli based ionic/cordova project. This is the project
      that is suggested to be used for development.
    * [license]
      Includes the License information and references to
      third-party licenses.
	* [documentation]
      Includes the documentation html page.
      
Firebase integration
========
The App use firebase backend. Therefore, you have to register on [firebase](https://firebase.google.com/).
There is a realtime db and api. The app use a json file as db that you can retrieve from firebase with a get call specifying https://[PROJECT_ID].firebaseio.com/.json , where PROJECT_ID is the id assigned when you create a project on firebase.
See [here](https://dev.to/aurelkurtula/introduction-to-firebases-real-time-database-89l) specially to set db rules in order to read and write on db with api.

Brief installation guide
------------------------

REQUIREMENT
========
* npm (installed with nodeJS) --> https://nodejs.org
* ionic --> npm install ionic -g (control that the version is 3.7.0 with **npm list ionic** command, that is should appear *ionic@3.7.0* )
* cordova --> npm install cordova -g
* An account on ionic site to execute the ionic cordova resources command --> https://ionicframework.com/ click in signup


STEPS TO USE
========
* enter in the project folder
* npm install
* Then ```ionic cordova platform add android``` and ```ionic cordova resources```
* If you want to view in local run ```ionic serve``` or ```ionic serve -l``` (for mobile lab view)
* If you want to only build ```ionic cordova build android``` or ```ionic cordova build ios```
* If you want to build and run the app on a your emulator ```ionic cordova run android``` or ```ionic cordova run ios```


N.B For android install ANDROID STUDIO (with sdk) and set the ANDROID_HOME environment variable to point your android sdk folder.

Problems/Questions
--------
If you experience any problem, please post a message to my email below and submit your question;
*angelo.mang@libero.it*

