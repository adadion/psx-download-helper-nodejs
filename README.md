# PSX Download Helper NodeJS

This project is inspired from https://psxdownloadhelper.codeplex.com/

Since `psx download helper` only runs on windows machine and I don't have one,
I decided to write a simple NodeJS script for it.

### Usage
1. Clone/download this project
2. Open terminal or command prompt
3. Change to directory where you extracted the files
4. Run `npm i`. Only need to be done once.
5. Start the script `node psxdownloadhelper.js`. This will start the server on `8080` port or you may change it by modifying the source code.
4. Start downloading some game/app on your ps4. Once it has started, pause it.
5. Put your IP address and port (8080) in the network settings of ps4.
6. Resume the download. It will fail, check the console and grab the link.
7. Download the file using your favourite download manager and put it in the data folder
8. Resume download again. This time the download bar should increase. Repeat step 6-8 until all the parts are downloaded. You can save time by downloading all the parts before hand.