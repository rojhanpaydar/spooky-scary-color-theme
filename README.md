# Spooky Scary Color Theme :skull:

Hey you! Interested in a theme that'll send SHIVERS down your spine and give you an all around Halloween vibe?! :jack_o_lantern: Well you've come to the right theme! Inspired by  Halloween, spooky season, and Tim Burton films, this theme was born by a dev who absolutely adores all these things! :sparkles:

![Preview of Spooky Scary Color Theme](spooky-scary-color-theme/spookyscarycolortheme/previewImage.png)

The best feature is all thanks to the folks who created the extension called "POWER MODE". :boom:

[link to Power Mode extension here](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-power-mode&ssr=false#overview)

Using the genius behind Power Mode, I was able to include a little ghost friend to pop up and haunt your editor after a few key types! :ghost:

To add this, you'll need to paste in the following to your settings.json:

```
// added powermode ext
"powermode.enabled": true,

"powermode.customExplosions": [
  // direct path does not work, gif I uploaded to giphy
  "https://media.giphy.com/media/WngnWxxekMn8DIqmwQ/giphy.gif"
],

// this allows the little ghost friend to pop up above your line so you can see what you're typing!
"powermode.customCss": {
  "top": "-30px",
  "z-index": 1,
  "height": "70px",
  "width": "70px",
},

// stops the editor from shaking on each type
"powermode.enableShake": false,

// minimizes how often there is an appearance from our little ghost friend!
"powermode.maxExplosions": 1, 

// how many key hits until our ghost friend comes out to haunt us! :scream:
"powermode.explosionFrequency": 20,
```

Additionally, I'm using the font "Fira Code", plugged into my settings.json like so: 

```
"editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
```

After you set that up, you should be good to GHOST! :stuck_out_tongue_winking_eye: 

Happy Spooky Season y'all, I hope this theme brings you lots of good spooky vibes!!! :tada:
