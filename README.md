# Aurelia Snippets for VS Code

This extension for Visual Studio Code adds snippets for Aurelia for TypeScript, Javascript and HTML.

## Usage
Type part of a snippet, press `enter`, and the snippet unfolds.

##TypeScript Snippets
```javascript
configuration          // creates an Aurelia startup configuration
bootstrapper           // creates an Aurelia explicit startup configuration
feature                // add a feature
plugin                 // add a plugin
useView                // creates an Aurelia component
created, attached, bind, unbind          // Aurelia component lifecycle
inject                 // Aurelia declaring dependencies
lazy, all, optional    // Aurelia using resolvers contains
transient, singleton   // Aurelia explicit registration 
containerless          // Aurelia containerLess Templating
computed               // Aurelia declaring computed property dependencies
configureRouter        // creates an Aurelia basic route configuration class
canActivate, activate, canDeactivate, deactivate // Aurelia screen lifecycle
customAttribute        // Aurelia customAttribute Decorator
valueChanged           // creates an Aurelia valueChanged function
subscribe              // creates an Aurelia event aggregator subscribe function
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
configuration          // creates an Aurelia startup configuration
bootstrapper           // creates an Aurelia explicit startup configuration
feature                // add a feature
plugin                 // add a plugin
useView                // creates an Aurelia component
created, attached, bind, unbind          // Aurelia component lifecycle
inject                 // Aurelia declaring dependencies
lazy, all, optional    // Aurelia using resolvers contains
transient, singleton   // Aurelia explicit registration 
containerless          // Aurelia containerLess Templating
computed               // Aurelia declaring computed property dependencies
configureRouter        // creates an Aurelia basic route configuration class
canActivate, activate, canDeactivate, deactivate // Aurelia screen lifecycle
customAttribute        // Aurelia customAttribute Decorator
valueChanged           // creates an Aurelia valueChanged function
subscribe              // creates an Aurelia event aggregator subscribe function
```
Alternatively, press `Ctrl+Space` (Windows, Linux) or `Cmd+Space` (OSX) to activate snippets from within the editor.

##Installation
1. Install Visual Studio Code 0.10.x or higher
2. Launch Code
3. From the command palette Ctrl-Shift-P (Windows, Linux) or Cmd-Shift-P (OSX)
4. Select Install Extension
5. Choose the extension
6. Reload Visual Studio Code
