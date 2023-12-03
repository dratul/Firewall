# Firewall login using python
In this repository, there are two programs for Automatic Firewall login using Python 
## Prerequisites
You should have installed python version 3.0 or above 
Here are the steps to prepare you to be able to open a webpage and log in using Python and some third-party applications:

1. Setting up your workspace
2. Downloading the necessary tools
3. How to hide our passwords
4. Reviewing necessary imports
Watch
[YouTube video] (https://youtu.be/NMVEU2KSY84?si=wdo0_F1TcHGYz8Hy) link showing all steps Click on the link below to watch the video: https://youtu.be/NMVEU2KSY84?si=wdo0_F1TcHGYz8Hy

## Downloads

### ChromeDriver oe Edge Driver
If you are using Google Chrome, download Chromedriver, or if you are using Microsoft Edge, then use EdgeDriver. You can download the program by searching on Google.

Once on the page, choose the appropriate link for your chrome version. Then you will choose the appropriate link according to your system. If you are on Windows, the 32-bit link works regardless. You will then be downloading a zip file. Once downloaded, we will move this zip file and extract it into the folder we have created. If you get stuck here, here is a video of how to download ChromeDriver for Windows and Mac.

### Selenium
Selenium is a great program for working with automation and web applications; we will be using it for these exact purposes. The installation process for Selenium is simple; you open the command prompt by searching for "cmd" on your computer. Open the command prompt and enter the following command:
> pip install selenium 
## Save ID and password in a file
If we must show our passwords while using this program we are not really able to show it off to our friends and where is the fun in that? In this article, I will show you a way to keep your login information hidden so you can share this with friends and not have worries about security. We will be creating another file and call it "login_details.py". We are going to keep this file as basic as possible inserting only 2 lines of code:
> username = "username"
> password = "password"
