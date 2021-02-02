# Electron Node-RED

This is an Electron template to embed [Node-RED](https://nodered.org) with an existing Node-RED project to create a native application.  

This Repositories forked from: [dceejay/electron-node-red](https://github.com/dceejay/electron-node-red) .  
I have post a issues if you want to see: [Feature request: Save .node-red on current folder and others suggesting](https://github.com/dceejay/electron-node-red/issues/13)  

The Target is Easy-To-Use Industrial Automation HMI.  

------------
## For EndUser or System Integrator
Please visit [Releases](https://github.com/feecat/electron-node-red/releases) to download package.  
Just unzip and run. You will see it like this:  
![](https://github.com/feecat/electron-node-red/blob/master/example/images/1.jpg)  
![](https://github.com/feecat/electron-node-red/blob/master/example/images/2.jpg)  
  
I'm suggest to use TCP/UDP to create program communication with plcs or others.  
There is a example, Included tcp communication, ui display, retain data, control and so on. will provider later.
![](https://github.com/feecat/electron-node-red/blob/master/example/images/3.jpg)  

------------
## For Developer:  
Please make sure you have installed [node.js](https://nodejs.org/) and [yarn](https://yarnpkg.com/).  
After Clone or Download and unzip this repositories, use cmd to act folder.  
Use `yarn` to automatic download packages.  
Use `yarn start` to start program.  
Use `yarn dist -w` to compile and compress electron app, use RunME_AfterBuild.bat to copy config and flow.  
Zip **./dist/win-unpacked** and send it to use.  

Tips of install nodes on node-red:  
before zip win-unpacked folder, run Node-RED Electron.exe once, it will create .node-red folder automaticly.  
cd ./node-red, use npm install packagename to install package, like here [node-red-dashboard](https://flows.nodered.org/node/node-red-dashboard)  
  
Tips of config.json:  
You can change `listenPort` to other port if you want.  
Change `width` and `height` to change default window size.  
Change `fullscreen` or `hidetotray` to change default start action.  
For others option i'm suggesting you can change the sources code if you want.  

------------

Thanks [dceejay/electron-node-red](https://github.com/dceejay/electron-node-red)
