# Linux_MacFanControl_GUI
WIP/DEMO: A GUI for controlling the fan speed of Intel-based Apple Mac computers.

This is just something I rushed together, using Node and Electron. The code is messy and there is definitely LOTS of room for improvement and I'd super appreciate any useful contribution!

Currently this program requires an active internet connection to operate properly, as it is currently fetching content for the Material Design Lite framework from Googles CDN. I do intend on changing this eventually however.

# Screenshots.

![Screenshot 01](https://raw.githubusercontent.com/lavanoid/Linux_MacFanControl_GUI/master/Screenshot%20from%202018-08-21%2020-56-09.png)

![Screenshot 02](https://raw.githubusercontent.com/lavanoid/Linux_MacFanControl_GUI/master/Screenshot%20from%202018-08-21%2020-56-31.png)

# Running/testing.

This only works on a Linux-based distribution and so far I've tested it on Ubuntu 18 and Manjaro. You need an up to date version of `node`, with the `npm` package manager. After installing those and cloning this repo, you should be able to run LMFC from the command line, like so:

    npm install && sudo npm start
    
The program needs to be ran as root to be able to interface with the Apple SMC driver. You only need to do `npm install` once.

Please remember this program wasn't written with much love and I know it's pretty messy in terms of quality and optimization, so I'd like to consider this as a demo rather than a daily-driver solution. I do hope there will be contributions towards this project, to give it the love it needs. 
