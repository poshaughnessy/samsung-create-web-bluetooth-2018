# "Web Bluetooth for Fun and Profit" - Samsung Create 2018

My slides for [Samsung Create 2018](https://samsungcreate.com). 


## To view the slides

Link to come...

Use arrow keys or the arrow buttons to move left/right.


## To run locally

```
npm install
npm start
```


## To use the Bluetooth remote control

Instead of running just with `npm start` or `node server`, use `node server-bluetooth`. This will run Bleno on your
local machine, in order to act as a Bluetooth peripheral.

Then load up the Remote page on a Web Bluetooth supporting browser, e.g. Samsung Internet, on the device you want to use 
as a presentation remote: http://localhost:9000/remote.html

Press Connect and (as long as you have the Node server running and Bluetooth enabled on both devices) you should see
a device option called 'Remote Receiver'. Select that, wait til it says Connected, then you can use the buttons to send 
commands!


## To deploy (for Peter's reference)

```
npm run deploy
```
