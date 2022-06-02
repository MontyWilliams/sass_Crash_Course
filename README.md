# using partials
using an "_" before a name indicates to the sass compiler that the file is a partial and therfore 
will skip it during compilation. you can import it in another sass file.

```
_base.scss

@use 'base';
```
In this demo sass variables are places in partial file called _config

# Mixin & Functions

functions return something while mixins are used mainly for substitution

# conditionals
sass allows for if statements within css
