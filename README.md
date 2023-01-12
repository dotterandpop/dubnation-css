# dubnation-css
## CSS for dubnation.social

There is very little documentation for how to customize the CSS on Mastodon.

One example is here, and the author also had trouble finding good examples. 
https://battlepenguin.com/tech/using-custom-css-with-mastodon/


## How to adjust the look of Mastodon without a new theme
This repo contains an example of how to adjust the look of Mastodon to use a new color scheme, without introducing a theme.

At this time there is only CSS for the dark theme.  It seems likely that minor changes to Mastodon could affect the CSS. I had to poke around with browser developer tools to fix a few things. 

Feedback welcome!

### Configuration

Log in as administrator, and edit the CSS to your liking and then paste into the tab at 

```
Administration > Server Settings > Appearance
```

### Restart the Web Service

```
// as root. phased restart w zero downtime
$ systemctl reload mastodon-web		
```

That's all folks! 
