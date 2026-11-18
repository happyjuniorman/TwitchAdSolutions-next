# TwitchAdSolutions-next

This repo aims to provide multiple solutions for blocking Twitch ads.

## Scripts

- vaft - [userscript](https://github.com/pixeltris/TwitchAdSolutions/raw/master/vaft/vaft.user.js)
  - Attempts to get a clean stream as fast as it can
  - If it fails to get a clean stream it removes ad segments (no playback until ad-free stream is found)

## Applying a script (userscript)

Viewing one of the userscript files should prompt the given script to be added when you have a userscript manager installed.

Userscript managers:

- https://violentmonkey.github.io/
- https://www.tampermonkey.net/
- https://apps.apple.com/us/app/userscripts/id1463298887

*Greasemonkey doesn't work with the scripts.*

## Issues with the scripts

If the script doesn't work or you're experiencing freezing / buffering issues see [issues.md](issues.md)
