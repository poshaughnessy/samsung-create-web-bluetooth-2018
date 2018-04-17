title: Web Bluetooth
output: public/index.html
theme: peter-theme
controls: false

--

# Web Bluetooth
## for Fun and Profit
### Samsung Create 2018

<div class="contact">
  <p>Peter O'Shaughnessy</p>
  <p>[@poshaughnessy](https://twitter.com/poshaughnessy)</p>
  <p>[@peter@toot.cafe](https://toot.cafe/@peter)</p>
</div>

--

## Bluetooth

### Born in 1994

<img src="images/bluetooth-logo.png" alt="Bluetooth logo" style="width: 20%; margin-top: 1em;"/>

--

## Fun fact...

<img src="images/bluetooth-runes.png" alt="Bluetooth runes" style="max-height: 60vh; margin-top: 1em;"/>

<div class="caption">Norse runes for Harald Bluetooth, King of Denmark, who united Denmark and Norway (10th century)</div>

--

## Bluetooth Low Energy (BLE)

### Born in 2010

<img src="images/gear-s3.png" alt="Gear S3" style="width: 25%; margin-top: 1em; vertical-align: middle;"/>

--

## Bluetooth 5

### Born in 2016

<h2 class="special-quote">"Quadruple the range, double the speed"</h2>

--

## Bluetooth Mesh

> &ldquo;Lets Bluetooth endpoints form networks among themselves, instead of having a central hub...
 
> a big advantage since it overcomes the limited range.&rdquo;

<div class="caption">[networkworld.com](https://www.networkworld.com/article/3209029/internet-of-things/bluetooth-mesh-takes-aim-at-enterprise-iot-but-hasn-t-taken-flight.html)</div>

--

## Bluetooth Mesh

> &ldquo;Particularly well-suited for... building automation, smart lighting, beacons &amp; ...industrial IoT&rdquo;

<div class="caption">[Andrew Zigani, ABI Research](https://www.networkworld.com/article/3209029/internet-of-things/bluetooth-mesh-takes-aim-at-enterprise-iot-but-hasn-t-taken-flight.html)</div>

--

## Consumer electronics

<img src="images/bluetooth-samsung-phone.png" alt="Bluetooth logo" style="width: 30%; margin-top: 1em; vertical-align: middle;"/>
<img src="images/bluetooth-speaker.png" alt="Bluetooth speaker" style="width: 30%; margin-top: 1em; vertical-align: middle;"/>

--

## Enterprise IoT

<img src="images/enterprise.png" alt="Enterprise tech" style="max-width: 60%; margin-top: 1em; vertical-align: middle;"/>
<img src="images/iot.png" alt="IoT" style="max-width: 30%; margin-top: 1em; vertical-align: middle;"/>

<div class="caption">Way finding, smart buildings, smart industry...</div>

--

## Smart _everything_
 
<img src="images/kickstarter.png" alt="Kickstarter" style="width: 80%;"/>

<div class="caption">Kickstarter.com</div>

--

# 10 million 

### Bluetooth enabled devices shipping every day

<div class="caption">Source: ABI Research, via [Martin Woolley](https://www.youtube.com/watch?v=-xtbTdOMqcg)</div>

--

## What about the Web?

> &ldquo;The web browser is arguably the most important of all platforms, especially for enterprise applications&rdquo;

<div class="caption">[Martin Woolley, Bluetooth SIG](https://medium.com/samsung-internet-dev/lets-connect-with-samsung-internet-v6-4-stable-1f197d43a812)</div>

--

## Web Bluetooth

<img src="images/pairing-prompt-drone.png" alt="Web Bluetooth pairing prompt" style="max-height: 70vh"/>

-- browser-logos

## Web Bluetooth support

![Samsung Internet](images/browsers/samsunginternet.png)
![Chrome](images/browsers/chrome.png)
![Opera](images/browsers/opera.png)

Support varies by Operating System

--

<img src="images/polyfill.png" alt="Windows 10 Polyfill" style="max-height: 80vh"/>

<div class="caption">[github.com/urish/web-bluetooth-polyfill](https://github.com/urish/web-bluetooth-polyfill)</div>

--

<video controls style="height: 80vh">
  <source src="videos/wb-slides.mp4"/>
</video>

Slides controller

--

<video controls style="width: 75%">
  <source src="videos/puckjs-web-bluetooth.mp4"/>
</video>

Puck.js via Web Bluetooth

--

<p style="margin-bottom: 0;"><img src="images/nordic-thingy.gif" style="max-height: 80vh;" alt="Nordic Thingy"/></p>

Nordic Thingy

--

<video controls style="width: 75%">
  <source src="videos/leds-luke-bonaccorsi.mp4"/>
</video>

[Pixel Grid demo by Luke Bonaccorsi](https://twitter.com/LukeB_UK/status/981639262746660865)

--

<iframe width="800px" height="550px" src="https://www.youtube.com/embed/QGb5cKL8kZ4?start=7" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

[jsyang.ca/hacks/gear-vr-rev-eng/](jsyang.ca/hacks/gear-vr-rev-eng/)

--

<iframe width="800px" height="550px" src="https://www.youtube.com/embed/Vg2e1jOug00" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>

[youtu.be/Vg2e1jOug00](https://youtu.be/Vg2e1jOug00)

--

<img src="images/hedgehog-curling.gif" style="max-height: 70vh" alt="Hedgehog Curling by Jo Balletti"/>

[bit.ly/hedgehog-curling](http://bit.ly/hedgehog-curling) by [Jo Balletti](https://twitter.com/thisisjofrank)

--

<img src="images/muse-eeg.png" style="max-height: 70vh" alt="Muse EEG Web Bluetooth"/>

[github.com/NeuroJS/angular-muse](https://github.com/NeuroJS/angular-muse) by [Uri Shaked](https://github.com/urish), [Alex Castillo](https://github.com/alexcastillo) [et al](https://github.com/NeuroJS/angular-muse/graphs/contributors) 

--

## "Central" vs "Peripheral"

<div class="grid2x2">
  <div><img src="images/phone.png" alt="Phone"/><p>Central</p></div>
  <div><img src="images/gear-s3.png" alt="Gear"/><p>Peripheral</p></div>
</div>

--

## Slides controller example

<table class="table2x2">
  <tr>
    <td><img src="images/phone.png" alt="Phone"/></td>
    <td><img src="images/laptop.png" alt="Gear"/></td>
  </tr>
  <tr>
    <td><h4>Central</h4><p>Web Bluetooth</p></td>
    <td><h4>Peripheral</h4><p>Bleno (Node) &amp; Web Sockets</p></td>
  </tr>
</table>

--

## Generic Attributes (GATT)

<img src="images/bluetooth-profiles-etc.png" alt="GATT" style="max-height: 70vh"/>

--

<img src="images/bluetooth-comms.png" alt="Bluetooth Comms" style="max-height: 80vh"/>

-- final-slide

## [bit.ly/web-bluetooth-create18](https://bit.ly/web-bluetooth-create18)

### [@poshaughnessy](https://twitter.com/poshaughnessy) <br/> [@peter@toot.cafe](https://toot.cafe/@peter) 

## Thanks! 🙏