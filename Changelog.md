### 2016-06-04 v2.0.0

 * Source code was rewritten from scratch
 * Block function trims given block name
 * Block function throws exception if block name isn't a string or empty string
 * Impossible to add several modifiers with the same name: `block('button')({skin: 'dark'})({skin: 'light'}); // "button_skin_light"`
 * Method `mix` doesn't support objects
 * Implemented static method `block.reset()`
 * Implemented new state-methods `is()` and `has()`

### 2016-11-05 v1.3.1

 * Class mapping support

### 2016-16-02 v1.2.2

 * Added ability to specify name/value separator for modifier

### 2015-10-06 v1.2.1

 * Bugfix: incorrect states for non boolean values in given object

### 2015-09-17 v1.2.0

 * Namespace available for setup in general settings

### 2015-09-07 v1.1.1

 * Method ```mix()``` supports another blocks

### 2015-08-12 v1.1.0

 * Breaking change for usage in browser: entry point ```Block``` renamed to ```block```
 * Method ```mix``` supports arrays and object

### 2015-05-11 v1.0.0

First stable release.

 * Generates block's name
 * Generates element's name
 * Adds modifiers with or without value
 * Mixes another class name
 * Supports SMACSS states
 * Supports custom separators
