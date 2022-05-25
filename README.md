# VSCODE - SilverStripe

Forked from [the original SilverStripe plugin](https://marketplace.visualstudio.com/items?itemName=adrian.silverstripe) by Adrian Humphreys.

-   Allows SilverStripe control tags inside html tags &lt;tag &lt;% here %&gt;&gt;
-   Fixes the matcher for ID tags (I <span title="I don't really understand TextMate">think</span>)

Basically this makes .ss files look good again and adds a few snippets to .ss files and .php files that I found handy.

## Make emmet work

Open `Preferences` -> `Settings`

Add below settings to enable Emmet for .ss files:

```json
"emmet.includeLanguages": {
    "SilverStripe": "html"
}
```

Snippets are taken from:
[LiamW's SilverStripe Atom bundle](https://github.com/LiamW/silverstripe-atom).
Grammar taken from:
[benjamin-smith's SilverStripe Sublime bundle](https://github.com/benjamin-smith/sublime-text-silverstripe/blob/master/SilverStripe.tmLanguage)

### Contributions

Go for gold, if it adds value, add it and I'll merge it
