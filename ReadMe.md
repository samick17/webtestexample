## Example of simple-web-automator

#### SourceCode

    https://github.com/samick17/simple-web-automator

#### Installation

    npm install simple-web-automator --save

#### API Reference

	openApp: []
	newBrowser: []
	closeAll: []
	navigatie: [url: string]
	delay: [seconds: string]
	click: [selector: string]
	click: [selector: string]
	enterText: [selector: string, text: string]
	getText: [selector: string],
	getTextArray: [selector: string],
	screenshot: []
	drag: [selector: string, points: [{x: <x>, y: <y>}...]]
	newTabs: [[url: string...]]
	switchTab: [index: int]
	maximize: []
	minimize: [],
	fullscreen: []
	setScreenSize: [w: int, h: int]
	getScreenSize: [],
	setScreenPosition: [x: int, y: int]
	getScreenPosition: []
	setScreenRect: [x: int, y: int, w: int, h: int]
	requestGET: [endPoint: string]
	requestDELETE: [endPoint: string]
	requestPUT: [endPoint: string]
	requestPOST: [endPoint: string]
	log: [value: any]
	exit: []


#### Run

`
const simpleWebAutomator = require('simple-web-automator');
simpleWebAutomator
.setwd('./testscripts')
.run('testcase1');
`

#### Run step-by-step

`
const simpleWebAutomator = require('simple-web-automator');
simpleWebAutomator
.setwd('./testscripts')
.run('testcase1');
`
