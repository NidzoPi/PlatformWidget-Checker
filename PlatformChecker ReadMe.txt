PlatformChecker v1.02

Installation:

This tool requeres some code editor with implemented terminal. (VS Code)

How to use:

1. Installed node modules are must for this tool to work

   Process of node modules installation is:

	1. Open platform checker folder in code editor
	
	2. Open the implemented terminal and type following:
		2.1 npm -init
		2.2 npm install -D puppeteer
		2.3 npm install -D googleapis
		2.4 npm install -D nodemon
		2.5 node --trace-warnings
		2.6 Set-ExecutionPolicy RemoteSigned
	
2. After all modules are installed we run the tool by typing following in terminal
	node index.js

3. Last but not least we can open Google Sheet where we can track updates while tool is working in background:
	https://docs.google.com/spreadsheets/d/1dh_9QxfVAmjyaEPjSVsiQowT6UQ3CIJiVDN0HIT9Gls/edit#gid=0

4. Once terminal gives message that all checking is done tool can be stopped with CTRL + C command


If you get an error connected to puppeter version of Chrome just 
cd ./node_modules/puppeteer
npm install


Usage:

You need to have access to this sheet: https://docs.google.com/spreadsheets/d/1dh_9QxfVAmjyaEPjSVsiQowT6UQ3CIJiVDN0HIT9Gls/edit#gid=0

In the A column you insert URLs with (https://) for stores that you wish check presence of the Widget ID and platform.

