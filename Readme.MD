Automation project for Yahnac application (Login page)

This project aims to automate the login flow for Yahnac apk. This project can be found here: https://github.com/malmstein/yahnac

I am using here:
Python
Pytest
Appium-Python-Client

How to install it?
just run requirements.txt by using following command:

pip install -r requirements

Test environment setup
Application folder and serial number for Android product are registered on /setup folder. Just insert your serial number (adb devices) <<File name here>> on file.

Reports are generated by, so, to execute with report just use following command:
pytest --template=html1/index.html --report=report.html