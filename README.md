# IDEA Live Templates

A collection of useful live templates that you can use within your PhpStorm or IntelliJ IDEA installation.

The structure of this repository as well as the handy script to list all templates has been heavily inspired
by https://github.com/keyboardsurfer/idea-live-templates. Kudos go to the repository maintainer.

# Installation

- Find the [live templates location](https://www.jetbrains.com/help/idea/2016.2/live-templates.html) for your IntelliJ IDE version
- `cd` into that location, run `git clone https://github.com/gridonic/idea-live-templates.git gridonic`
- Copy all `.xml` files from the cloned repository into the `templates` folder `cp gridonic/*.xml .`
- Restart your IDE

### GridonicCSS.xml
- __`/****`__: "CSS sub-section comment block"
- __`/***`__: "CSS section comment block"
- __`/**`__: "CSS multi line comment"
- __`/*`__: "CSS single line comment"
- __`///`__: "sassdoc method comment block"

### GridonicJS.xml
- __`log`__: "`console.log` statement in js"

### GridonicPHP.xml
- __`dprintr`__: "Debug `print_r` statement"

### GridonicTwig.xml
- __`trans`__: "Twig `trans` shortcut"
