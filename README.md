# JQuery-UI LESS adapter for TWBS 3

## v0.1.3

Have consistent (themeable) styles
from TWBS with jQuery UI components. 

This project contains a functional [demo](http://dc-development.github.io/jquery-ui-less/) with generated themes.

Just clone this repo anywhere to your machine and browse the demo folder, to see how its used.
If you want to use it standalone make sure you also clone the twbs submodule by using:

`git clone --recursive https://github.com/DC-development/jquery-ui-less.git`

Goal for this branch is to make all jQUeryUI widgets use glyphicons and follow, whatever bootstrap theme used, in your project.

Example usage:

```

@import "../bootstrap/less/bootstrap";
@import "../less/jquery.ui.less";

@import "themes/variables_cerulean";
@import "themes/bootswatch_cerulean";

@import "demovars.less";

```

The demo only contains generated css (beside the demo-less files).
The themes are downloaded here: http://bootswatch.com/yeti/. 
