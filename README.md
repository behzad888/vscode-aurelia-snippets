# Aurelia Snippets for VS Code

This extension for Visual Studio Code adds snippets for Aurelia for TypeScript, Javascript and HTML.

## Usage
Type part of a snippet, press `enter`, and the snippet unfolds.

##TypeScript Snippets
```javascript
au-configuration          // creates an Aurelia startup configuration
au-bootstrapper           // creates an Aurelia explicit startup configuration
au-feature                // add a feature
au-plugin                 // add a plugin
au-useView                // creates an Aurelia component
au-created, au-attached, au-bind, au-unbind          // Aurelia component lifecycle
au-inject                 // Aurelia declaring dependencies
au-lazy, au-all, au-optional    // Aurelia using resolvers contains
au-transient, au-singleton   // Aurelia explicit registration 
au-containerless          // Aurelia containerLess Templating
au-computed               // Aurelia declaring computed property dependencies
au-configureRouter        // creates an Aurelia basic route configuration class
au-canActivate, au-activate, au-canDeactivate, au-deactivate // Aurelia screen lifecycle
au-customAttribute        // Aurelia customAttribute Decorator
au-valueChanged           // creates an Aurelia valueChanged function
au-subscribe              // creates an Aurelia event aggregator subscribe function
```
Alternatively, press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (OSX) to activate snippets from within the editor.

##HTML Snippets
HTML language:
``` html
if                   //    if.bind="expression"
with                 //    with.bind="expression"
value                //    value.bind="expression"
input                //    input.bind="expression"
href                 //    href.bind="expression"
click.delegate       //    click.delegate="delegate"
click.trigger        //    click.trigger="trigger"
repeat.for           //    rrepeat.for="item of list"    
value.two-way, value.one-way, value.one-time // value.two-way="binding"
and etc.
```
Alternatively, press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (OSX) to activate snippets from within the editor.

##JavaScript Snippets
```javascript
au-configuration          // creates an Aurelia startup configuration
au-bootstrapper           // creates an Aurelia explicit startup configuration
au-feature                // add a feature
au-plugin                 // add a plugin
au-useView                // creates an Aurelia component
au-created, au-attached, au-bind, au-unbind          // Aurelia component lifecycle
au-inject                 // Aurelia declaring dependencies
au-lazy, au-all, au-optional    // Aurelia using resolvers contains
au-transient, au-singleton   // Aurelia explicit registration 
au-containerless          // Aurelia containerLess Templating
au-computed               // Aurelia declaring computed property dependencies
au-configureRouter        // creates an Aurelia basic route configuration class
au-canActivate, au-activate, au-canDeactivate, au-deactivate // Aurelia screen lifecycle
au-customAttribute        // Aurelia customAttribute Decorator
au-valueChanged           // creates an Aurelia valueChanged function
au-subscribe              // creates an Aurelia event aggregator subscribe function
```
Alternatively, press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (OSX) to activate snippets from within the editor.

##Installation
1. Install Visual Studio Code 0.10.x or higher
2. Launch Code
3. From the command palette Ctrl-Shift-P (Windows, Linux) or Cmd-Shift-P (OSX)
4. Select Install Extension
5. Choose the extension
6. Reload Visual Studio Code
