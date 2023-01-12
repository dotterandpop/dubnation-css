# dubnation-css

## CSS for dubnation.social

There is little documentation for how to customize the CSS on Mastodon.

One example is here:
https://battlepenguin.com/tech/using-custom-css-with-mastodon/

This repo has the CSS for dubnation.social

This is an example of adjusting the look of Mastodon to use a new color scheme, without introducing a theme.

At this time there is only CSS for the dark theme.

Feedback welcome!

### Configuration

Edit the CSS to your liking and then paste into the tab at 
Administration > Server Settings > Appearance

### Restart the Web Service

```
// phased restart w zero downtime
$ systemctl reload mastodon-web		
```

That's all folks! 
