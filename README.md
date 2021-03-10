# Cortex Video Service
## What is Cortex Video Service?
Cortex Video Service (CVS) is an open-source Video API that brings people together globally through interactive live video calls.

CVS makes it easy to build a custom video experience within any mobile, web, or desktop application and is built on the WebRTC industry standard that is available on billions of devices.
## CVS advantages
1. Fast build and launch. All the functionality is available out-of-the-box.
2. There are examples of applications and all the manuals.
3. Docker files are ready and configured.
## CVS features
* Video: supports all your video use-cases with 1:1 video, group video chat up to 6 participants
* Voice: Video sessions can be video and voice, voice-only or mixed.
* Encryption: All voice, video and signaling traffic is encrypted.
* Easily manage services: simple registration and url share.
* From web to mobile, use our SDKs to create apps and services for all your devices: Chrome + Android.
## What's under the hood of CVS?
CVS is an open-source WebRTC based server with the client designed and developed on top of Janus.
The server is tailored in Python and can be easily integrated into any existing project.
The client-side is currently tailored in the form of React SDK for the web browser-based client.
For mobiles, CVS is currently limited to Android.
## Design goals
CVS server-side library and its client-side SDKs are designed to accomplish the following goals:
* Support WebRTC for input and output;
* Python module on the server-side;
* React SDK on the client-side on the web;
* Android SDK for Mobile side clients;
* Be minimalistic: just handle the media layer;
* Be super low-level API;
* Support all existing WebRTC endpoints.
## Architecture
![CVS general diagram](https://github.com/CortexVideoServices/Description/blob/main/CVS%20general%20diagram.png)
## Features
* Front-end client library supporting TypeScript and Javascript;
* Middleware library: Asynchronous Python;
* Mobile library: Android;
* WebRTC compatibility;
* IPv6 ready;
* ICE / DTLS / RTP / RTCP over UDP and TCP;
* Easy to implement, deploy and use.
## Issues
Supports browsers latest versions: Firefox — 43 and later, Chrome — 55 and later.
Does not support IE.
## Demo: [cvs.solutions](https://cvs.solutions/);
## Contributors:
Alexey Poryadin;

Zakhar Nedashkovskiy;

Maxim Smirnov.
## Contacts: [cx.technology/#contacts](https://cx.technology/#contacts)
## License
GNU Lesser General Public License v.3
