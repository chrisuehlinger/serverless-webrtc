serverless-webrtc
=================

To install: `npm install` (this just installs browser-sync, you can also just use a static server if you want)

To run locally:

- `npm start` 
- Visit http://localhost:9191 in two different browsers and follow the directions

To run on two devices on the same local network:

- `npm run serve:ssl`
- Visit https://localhost:9191 on your computer and tell the browser to ignore the self-signed SSL cert
- Visit https://your.computers.local.ip:9191 on the other device and tell the browser to ignore the self-signed SSL cert