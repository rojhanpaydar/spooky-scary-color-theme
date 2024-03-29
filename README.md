# Spooky Scary Color Theme 

Hey you! Interested in a theme that'll send SHIVERS down your spine and give you an all around Halloween vibe?! Well you've come to the right theme! Inspired by  Halloween, spooky season, and Tim Burton films, this theme was born by a dev who absolutely adores all these things!

![Preview of Spooky Scary Color Theme: a black, green, orange and purple VS Code Theme](https://media.giphy.com/media/ZljsomV1FjhgkVIjYh/source.gif)
>Let's ignore the fact that my fingers type faster than my brain, I meant to write an h2 and not an h1, ty! :)

![Preview of Spooky Scary Color Theme: a black, green, orange and purple VS Code Theme](https://raw.githubusercontent.com/rojhanpaydar/spooky-scary-color-theme/main/previewImage.png?token=ANZ5BYHQ4U2PYB34ZHEM35LBLOTBA)

The best feature is all thanks to the folks who created the extension called "POWER MODE".

[link to Power Mode extension here](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-power-mode&ssr=false#overview)

Using the genius behind Power Mode, I was able to include a little ghost friend to pop up and haunt your editor after a few key types!

![An animated looping image of a cartoon ghost flying upward and disappearing](https://media.giphy.com/media/8CZkmk6VsWmf5TfxNo/giphy.gif)
> Credits to the original author of this gif [Finkel Band](https://giphy.com/finkelband). I had to speed it up and [post my own faster version of this gif](https://media.giphy.com/media/WngnWxxekMn8DIqmwQ/giphy.gif) so it would render in a faster enough time on each click! Also, I will not be removing this gif so it can be used forever!

To add a GHOST to your editor, you'll need to install the [Power Mode Extention](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-power-mode&ssr=false#overview), open up settings.json, and paste the following code inside your settings.json:

```
// added powermode ext
"powermode.enabled": true,

"powermode.explosions.customExplosions": [
  // direct path does not work, gif I uploaded to giphy
  "https://media.giphy.com/media/WngnWxxekMn8DIqmwQ/giphy.gif"
],

// this allows the little ghost friend to pop up above your line so you can see what you're typing!
"powermode.explosions.customCss": {
  "top": "-30px",
  "z-index": 1,
  "height": "70px",
  "width": "70px",
},

// stops the editor from shaking on each type
"powermode.shake.enabled": false,

// minimizes how often there is an appearance from our little ghost friend!
"powermode.explosions.maxExplosions": 1, 

// how many key hits until our ghost friend comes out to haunt us! :scream:
"powermode.explosions.frequency": 20,
```

Additionally, I'm using the font "Fira Code", plugged into my settings.json like so: 

```
"editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
```

After you set that up, you should be good to GHOoOoOoST!

Happy Spooky Season y'all, I hope this theme brings you lots of good spooky vibes!!!

![An animated looping image of a cartoon pumpkin that reads 'happy halloween'](https://media.giphy.com/media/OoYrQPHwYpYnXhllfe/giphy.gif)

Resources and guides:
 
[Monica Powell's](https://twitter.com/indigitalcolor/) article to set up Power Mode extension: [How to Make Your VSCode Sparkle](https://aboutmonica.com/blog/how-to-make-your-vs-code-sparkle)

[Cody Hoover's](https://twitter.com/hoovercj) extension Power Mode: [Power Mode Extension](https://marketplace.visualstudio.com/items?itemName=hoovercj.vscode-power-mode&ssr=false#overview)

[Ivan Stevkovski's](https://www.linkedin.com/in/istevkovski/?originalSubdomain=mk) guide to make a VS Code theme: [Create Your Own Custom Theme Extension](https://medium.com/wearelaika/vscode-create-your-own-custom-theme-extension-96c67bd753f6)

