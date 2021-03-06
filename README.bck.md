# [Find and Replace](https://github.com/thierryc/Sketch-Find-And-Replace/) for Sketch

![Find and Replace for Sketch](https://raw.githubusercontent.com/thierryc/Sketch-Find-And-Replace/master/assets/icon.png)

## V2 is ready for Sketch 53, 54...

[Folow me on twitter](https://twitter.com/@Autre_planete) to be posted.

For Sketch 52 and previous use the V1.

## How to

Finds text in selected layer(s) and all layers contained within - and replaces it with different text. Features partial, case sensitive and full-document matching.

Now works with symbol overrides. 🎉

Find and Replace [Sketch Plugin source code](https://github.com/thierryc/Sketch-Find-And-Replace/) on github

![Find and Replace dialog](https://raw.githubusercontent.com/thierryc/Sketch-Find-And-Replace/master/Screenshots/screenshot.png)

## Installation

Download and unzip, then double-click on the `Find and Replace.sketchplugin` file.
Sketch will copy it to the plugins folder and install it automatically.

## Update > 1.6

Use Sketch Automatic Update (Sketch 45+).

## Usage
**Menu** - You can access it from the menu **Plugins → Find and Replace**
**Keyboard** - Alternatively, use the keyboard shortcut **cmd + shift + f**

**Complex documents** - If you have an extremely complex document, and set the scope to the entire document, it might take a few seconds longer to process it all. Don't panic if you get a beach ball, it hasn't crashed Sketch, it just has to go through every layer in every artboard in every page and do a comparison.

## Options

### Search scope
How much of your document it will actually search

* If you have selected layers to search in, then **Selected layers** will be chosen automatically.
* You can also choose to search all layers in the **Current page**
* Or you can search the **Whole document** and it will search every layer in every artboard in every page of your document.

### Case matching
Whether it matches exactly as you typed or not

**Case insensitive** by default ("john" will match "John")

**Case sensitive** it will match exactly as you typed it ("john" won't match "John").

### Match whole words or phrases only

Whether it matches whole or partial words

**Yes** (default) will match whole words ("oh" will not match "John")

**No** will match partial words ("oh" will match "John", if you wanted to change him to "Joan" for example)

## Other features

**Remembers your settings** - Remembers your settings for next time you do a find/replace (doesn't remember find/replace/scope as these will change each time)

## Regex new feature

Get the Regex Power ! ⚡️

### "John Smith" to "Smith John"

Find
```
(\w+)\s+(\w+)
```

Replace with
```
$2 $1
```

Result: Smith John.


#### Replace all double spaces

Find
```
\s{2,}

```

Replace with
```
(one space)

```

Follow me on twitter for more tips.

https://twitter.com/Autre_planete


## Issues or ideas

If you have any problems, or ideas, please open an issue!

### Credits and Thanks

V1 Created by [Martin Steven - @mscodemonkey](https://github.com/mscodemonkey) - Thank you Martin.

V2 Created by [Thierry Charbonnel - @thierryc](https://anotherplanet.io).

V1 and V2 Maintained and improved by [Thierry Charbonnel - @thierryc](https://anotherplanet.io).

Thanks to [Aby Nimbalkar - @abynim](https://github.com/abynim) - for the SketchPlugin-Remember code to save user settings.

Thanks to [Autre Planete - @thierryc](https://github.com/thierryc) - for writing the code to change text within symbol overrides.

Thanks to [Vincenzo Petito - @vincenzopetito](https://github.com/vincenzopetito) - for code within [Shapr](https://github.com/vincenzopetito/Shapr) showing how to focus the text field on start and tabbing between input fields found within the dialog.

Thanks to [Sean Dellis - @seandellis](https://github.com/seandellis) - for his help, test sketch doc and issues review.

Thanks to [@iconmaster](https://github.com/iconmaster) - for his test.

### Disclaimer

I take no responsibility for what you find and replace, or for any changes made unintentionally due to this software erroring. I do test it before I release it so the chances of bugs are minimised, but still, use wisely and completely at your own risk. Remember, cmd-z is your saviour.*



[![Install PLUGIN NAME with Sketchpacks](http://sketchpacks-com.s3.amazonaws.com/assets/badges/sketchpacks-badge-install.png "Install PLUGIN NAME with Sketchpacks")](https://sketchpacks.com/YOUR_NAME/PLUGIN_NAME/install)
