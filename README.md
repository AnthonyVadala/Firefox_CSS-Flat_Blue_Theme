# Firefox CSS: Flat Blue Theme

**NOTE** - I stopped working on this. May revisit it after WebExtensions are implemented.

This Firefox theme is meant to be used with the latest version of Firefox (29+ for australis).

Copy and paste [this CSS](https://github.com/AnthonyVadala/Firefox_CSS-Flat_Blue_Theme/blob/master/Firefox-CSS)  into an addon like [Stylus](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) to apply the theme to your browser.

Find this part in the CSS and change min-width: to ***YOUR*** monitor's max width to fix overflow issue:

    /* Fullscreen margin fix */
    /* CHANGE TO YOUR MONITOR'S MAX WIDTH!*/
    @media screen and (min-width: 1920px) { 
       #titlebar { margin-top:0; }
    }

## PREVIEW
![Alt text](https://raw.githubusercontent.com/AnthonyVadala/Firefox_CSS-Flat_Blue_Theme/master/Previews/firefox-theme-preview.png)
