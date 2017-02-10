# weechat-pushjet

A [WeeChat](https://weechat.org/) plugin that automatically sets the user as away if there are no relay clients connected, and clears the away status if connected.

### Installation

In WeeChat install the script by typing the following:
```
/script install detach-away.py
```

### Options

The plugin allows you to set a few options through the normal WeeChat settings system.  
You'll find all of them under _`plugins.var.python.detach-away`_, and all of them have helpful descriptions.

To set them use _`/set plugins.var.python.detach-away.foo bar`_ or through the [iset.pl](https://weechat.org/scripts/source/iset.pl.html) plugin.

- `message`
	- away message (default: "I am away")
- `debug`
	- debug messages flag (default: "off")
