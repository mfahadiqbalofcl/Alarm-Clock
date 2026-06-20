# Alarm Clock

A simple, no-dependency alarm clock built with vanilla HTML, CSS, and JavaScript. Pick an hour, minute, and AM/PM, hit **Set Alarm**, and a ringtone plays when your time arrives. The clock face updates live every second.

**Live demo:** https://mfahadiqbalofcl.github.io/Alarm-Clock/

## Screenshot

![Alarm Clock screenshot](./assets/images/clock.png)
<!-- Replace with an actual screenshot of the running app -->

## Features

- Live digital clock (12-hour format with AM/PM), refreshing every second
- Set an alarm for any hour / minute / AM-PM combination
- Plays a looping ringtone when the alarm time is reached
- "Clear Alarm" to stop the ringtone and reset
- Pure front-end — no build step, no frameworks, no dependencies

## Tech stack

- HTML5
- CSS3
- Vanilla JavaScript (no libraries)

## Run it locally

No build tools required. Clone and open in a browser:

```bash
git clone https://github.com/mfahadiqbalofcl/Alarm-Clock.git
cd Alarm-Clock
```

Then open `index.html` in your browser, or serve the folder so audio loads reliably:

```bash
# Python 3
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Project structure

```
Alarm-Clock/
├── index.html
├── favicon.png
└── assets/
    ├── css/style.css
    ├── js/script.js
    ├── files/ringtone.mp3
    └── images/
```

## Note

The ringtone path in `assets/js/script.js` is currently `"../files/ringtone.mp3"`; for the deployed structure it should be `"./assets/files/ringtone.mp3"` so the sound loads correctly.

## License

Released under the [MIT License](./LICENSE).