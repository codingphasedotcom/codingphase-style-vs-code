# CodingPhase VS Code Style
![enter image description here](https://github.com/codingphasedotcom/codingphase-style-vs-code/blob/main/thumb.png?raw=true)
## Why?
I took my time to share my vs code settings because I always get asked what vs code theme you use? and my answer is always it's too long to explain... so now you guys can come here and have the exact same theme and settings I use.

## Credit
CodingPhase Style is inspired and based on two different themes created by **[Codevars](https://github.com/codevars)** and **[thecodemonkey](https://github.com/thecodemonkey)**. My job here is to be the glue bring the best features of both themes and add my own styles. In the future I will be making this into it's own VS Code Theme and will continue to give credit to these great developers.

## Like it and want to support?
Just Subscribe to [Youtube channel CodingPhase](https://www.youtube.com/codingphase) and visit the site [CodingPhase.com](https://codingphase.com) if you looking to learn to code.

## Instructions

 1. Give this repo a star and also [outrun-meets-synthwave-repo](https://marketplace.visualstudio.com/items?itemName=codevars.outrun-meets-synthwave) + [synthwave-x-fluoromachine-epic-animations-repo](https://github.com/thecodemonkey/synthwave-x-fluoromachine-epic-animations) (If Not This Won't Work For You LOL Come On Guys it's free)
 2. Install vs code extension [Outrun Meets Synthwave](https://marketplace.visualstudio.com/items?itemName=codevars.outrun-meets-synthwave)
 3. Install vs code extension [Bearded Icons](https://marketplace.visualstudio.com/items?itemName=BeardedBear.beardedicons) 
 4. Install vs code extension [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) 
 5. Download Mononoki  and Fira Code from [Nerd Fonts](https://www.nerdfonts.com/font-downloads)(mononki it's the one I use super clean) but if you want ligatures arrows then use Fira Code)
 6. on vs code open up the user settings cmd + p then search for user settings and copy the settings on the settings.json file from this repo ( if you want it exactly like mines paste it at the bottom if you don't want to override your own settings then paste it at the top of file)
 7. Replace the `vscode_custom_css.imports` depending your operative system, and add your user or file location in your VS Code `settings.json` 
```js
On Mac:

{
  "vscode_custom_css.imports": [
    "file:///Users/{your username}/.vscode/extensions/codevars.outrun-meets-synthwave-0.0.1/synthWaveStyles.css"
    ]
}

Windows:

{
  "vscode_custom_css.imports": [
    "file:///C:/Users/{your username}/.vscode/extensions/codevars.outrun-meets-synthwave-0.0.1/synthWaveStyles.css"
    ]
}

Linux:
{
    "vscode_custom_css.imports": [
        "file:///home/{your username}/.vscode/extensions/codevars.outrun-meets-synthwave-0.0.1/synthWaveStyles.css"
    ]
}
```

