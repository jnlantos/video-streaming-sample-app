# Ricoh Two-way Video Streaming Sample
Bidirectional video streaming sample.

## Requirements
* Google Chrome 51+ or Mozilla Firefox 47+
* Web Camera accessible from your browser.
* Enable Web Camera access in your browser setting.
* Node.js 5.0 or newer.

You'll also need

* Ricoh API Client Credentials (client_id & client_secret)
* Ricoh ID (user_id & password)

If you don't have them, please register them at [THETA Developers Website](http://contest.theta360.com/).

## Setup

```sh
$ git clone https://github.com/ricohapi/video-streaming-sample-app.git
$ cd video-streaming-sample-app/samples
$ npm install
$ npm run build
```
Make config.js from config_template.js.

```sh
$ cd twoway
$ cp ../config_template.js ./config.js
```
and put your credentials into the `config.js`.

## Video Streaming
Connect the Web Camera and execute `npm start`, then the browser will be opened.  
Select the Web Camera, put your Ricoh ID & password, and submit the login button.  
Let the peer user login on his own device following the instruction above and click Open button,  
then put the peer's User ID to the Peer-ID field and submit Connect button,  
then streaming connection will start between you and the peer.

```sh
$ npm start
```

## THETA View
If the peer user is using THETA, push THETA View button, then you'll see the draggable & zoomable 360° view.
