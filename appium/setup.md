#  Prerequisite to use APPIUM

1. Node
3. Download Android studio


NVM install and use:-
https://medium.com/@isaacjoe/best-way-to-install-and-use-nvm-on-mac-e3a3f6bc494d
--------------------------------------------------------------------------------
steps to create a appium react-native project

1) create a react-native project
       react-native init <project name>

2) Enable ES6+ syntax for Jest (mainly for import, async/await)
       yarn add --dev babel-preset-react-native

3) Install appium, appium-doctor
       yarn add --dev appium appium-doctor

4) Add web driver devDependencies to package.json
       "wd": "^1.4.0" or run :- yarn add --dev wd

5) Add usefull scripts to package.json, so that we can run them using yarn
	"appium": "appium",
        "appium:doctor": "appium-doctor"


---------------------------------------------------------------------------------

steps to run tests

1) Start appium server
        yarn run appium

2) Start emulator

3) Start React Native dev server
	react-native start

4) run jest tests
	yarn test


-------------------------------------------------------------------------------
steps to start android emulator

1) open adv manager from android studio

2) start any emulator listed

------------------------------------------------------------------------------

inspect element

1) install https://github.com/jhen0409/react-native-debugger

2) yarn install and yarn build for  build application code which opens on simulator

3) on build application talks to react-native-debugger

_

















appium project setup with react native
https://medium.com/front-end-weekly/how-to-do-end-to-end-e2e-testing-for-react-native-android-using-jest-and-appium-27d75e4d831b

not to use babelrc, just babel.config.js

start appium server with yarn run appium

start emulators 

yarn tests

Simulator localtion iphone
/Applications/Xcode.app/Contents/Developer/Applications/Simulator.app

tricks
https://medium.com/@ankitkumargupta/ios-simulator-command-line-tricks-ee58054d30f4


--------------------------------------------------------------------------------------
react-native Debugger

1) yarn ios or android

2) start react-native Debugger

3) start remote debug (cmd+m for android and cmd+d for ios)

4) tuggle inspect

------------------------------------------------------------------------------------- 


