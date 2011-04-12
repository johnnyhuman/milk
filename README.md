# gButtons - CSS3 buttons framework #

gButtons is a lightweight but powerful CSS3 *framework* for creating good-looking buttons.
It supports skins and plugins (o_0) which allows you to manage buttons design and behaviour easily.  

Originally it was a fork of Nicolas Gallagher's [CSS3 GitHub Buttons](https://github.com/necolas/css3-github-buttons).
But the project structure was completely changed? the code was partially 
rewritten and I decided to create a separate project.
See the project evolution in the "Acknowledgements" section.

## Demo ##

Framework demo: [gButtons CSS3 Framework](http://lab.aam.me/gbuttons#demo)

## Installation ##

 1. Copy `css/gbuttons` into your stylesheets folder and link to `gbuttons/standart.css` in the head of your HTML document.
 2. Copy `images/gbuttons` into your images folder.
 3. Add `button` class to the `<button>`, `<input>` or `<a>` HTML element.

## Buttons ##

The "buttons" can be created by adding `class="button"` to any appropriate 
`<a>`, `<button>`, or `<input>` element. Add a further class of `pill` to 
create a pill-like button. Add a further class of `primary` to emphasise 
more important actions.

    <a href="#" class="button">Post comment (link)</a>
    <input class="button" type="submit" value="Post comment (input)">
    <button class="button" type="submit">Post comment (button)</button>

Pill-like buttons with a primary action:

    <a href="#" class="button pill primary">Create Project</a>
    <a href="#" class="button pill">Create Other</a>

## Buttons with icons ##

A range of icons can be added (only for links and buttons) by adding a class 
of `icon` and any one of the provided icon classes.

    <a href="#" class="button icon search">Search</a>

## Buttons size ##

If you need a bigger or smaller buttons you can get them easily by addind the 
class `medium`, `big` or `huge`.

    <a href="#" class="button medium">Publish</a>
    <a href="#" class="button big">Create Project</a>
    <a href="#" class="button huge">Sign Up</a>

## Buttons with dangerous and safe actions ##

If you have a button that triggers a dangerous action, like deleting data, 
this can be indicated by adding the class `danger`.

    <a href="#" class="button danger">Delete post</a>

If you have a button that triggers a save action, this can be indicated by 
adding the `safe` class.

    <a href="#" class="button safe">Save the world</a>

## Button groups ##

Groups of buttons can be created by wrapping them in an element given a class 
of `button-group`. A less important group of buttons can be marked out by adding 
a further class, `minor-group`.

    <div class="button-group minor-group">
        <a href="#" class="button">Inbox</a>
        <a href="#" class="button">Drafts</a>
        <a href="#" class="button">Sent</a>
        <a href="#" class="button">Spam</a>
        <a href="#" class="button">Trash</a>
    </div>

## Mixed groups ##

Displaying a mixture of grouped and standalone buttons, as might be seen in a 
toolbar, can be done by adding another wrapping element with the class `button-container`.

    <div class="actions button-container">
        <a href="#" class="button primary">Admin</a>

        <div class="button-group">
            <a href="#" class="button primary">Unwatch</a>
            <a href="#" class="button">Fork</a>
            <a href="#" class="button danger">Pull Request</a>
        </div>

        <div class="button-group minor-group">
            <a href="#" class="button">10 Watchers</a>
            <a href="#" class="button">1 Forks</a>
        </div>
    </div>

## Browser compatibility ##

Firefox 3.5+, Google Chrome, Safari 4+, IE 8+, Opera 10+.

Note: Some CSS3 features are not supported in older versions of Opera and 
versions of Internet Explorer prior to IE 8.
The use of icons is not supported in IE 6 or IE 7.

## License ##

<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="http://i.creativecommons.org/p/mark/1.0/88x31.png" 
style="border-style: none;" alt="Public Domain" /></a>

Public domain: [http://unlicense.org](http://unlicense.org)

## Acknowledgements ##

Inspiration path:
[GitHub](http://github.com) → [David Walsh](http://davidwalsh.name)'s [GitHub-Style Buttons with CSS and JavaScript](http://davidwalsh.name/github-css) → 
[Michael Henriksen](http://michaelhenriksen.dk)'s [CSS3 Buttons](http://github.com/michenriksen/css3buttons) → 
[Nicolas Gallagher](nicolasgallagher.com)'s [CSS3 GitHub Buttons](https://github.com/necolas/css3-github-buttons) → 
You are here.

Icons from [Iconic pack](http://somerandomdude.com/projects/iconic/) by 
[some random dude](http://somerandomdude.com/) which are licensed as 
[CC Attribution-Share Alike 3.0](http://creativecommons.org/licenses/by-sa/3.0/us/).
