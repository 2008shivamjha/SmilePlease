# SmilePlease
## Disclaimer:-
Do not attempt to violate the law with anything contained here. If you planned to use the content for illegal purpose, then please leave this REPOSITORIES immediately! We will not be responsible for your any illegal actions.

![ab](ab.png)

## How it works?

The tool generates a malicious HTTPS page using Serveo or Ngrok Port Forwarding methods, and a javascript code to cam requests using MediaDevices.getUserMedia.

The MediaDevices.getUserMedia() method prompts the user for permission to use a media input which produces a MediaStream with tracks containing the requested types of media. That stream can include, for example, a video track (produced by either a hardware or virtual video source such as a camera, video recording device, screen sharing service, and so forth), an audio track (similarly, produced by a physical or virtual audio source like a microphone, A/D converter, or the like), and possibly other track types.

See more about This here : _https://developer.mozilla.org/en-US/docs/Web/API/MediaDevices/getUserMedia_.

To convince the target to grant permissions to access the cam, the page uses a javascript code made by _https://github.com/wybiral_ that turns the favicon into a cam stream.

## Installing (Kali Linux/Termux/Terminal):

>git clone _https://github.com/2008shivamjha/SmilePlease_

>cd SmilePlease

>bash smileplease.sh
