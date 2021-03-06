# Milk - CSS3 UI framework #

Milk is a lightweight but powerful CSS3 UI framework.
It supports skins and plugins.  

## Demo ##

Framework demo: [Milk CSS3 Framework](http://lab.aam.me/gbuttons#demo)

## Installation ##

 1. Copy `css/milk` into your stylesheets folder and link to 
 `milk/packages/standart.css` in the head of your HTML document.
 2. Copy `images/milk` into your images folder.
 3. Add `button` class to the `<button>`, `<input>` or `<a>` HTML element to 
 create nice buttons.

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
class `tiny`, `small`, `little`, `big`, `huge`, `great` or `giant`.

    <a href="#" class="button tiny">Edit comment</a>
    <a href="#" class="button huge">Create Project</a>
    <a href="#" class="button giant">Sign Up</a>

## Buttons with dangerous and safe actions ##

If you have a button that triggers a dangerous action, like deleting data, 
this can be indicated by adding the class `danger`.

    <a href="#" class="button danger">Delete post</a>

If you have a button that triggers a save action, this can be indicated by 
adding the `safe` class.

    <a href="#" class="button safe">Save the world</a>

## Simple button groups ##

Groups of buttons can be created by adding a classes 
`g-first`, `g-item`, `g-last` and `next-g` or `previous-g` to the group 
elements. Use `next-g` or `previous-g` classes to add margin between the
button groups in one row.

    <a href="#" class="button safe g-first">+</a>
    <a href="#" class="button danger g-last next-g">-</a>

    <a href="#" class="button g-first">Publish</a>
    <a href="#" class="button g-item">Edit</a>
    <a href="#" class="button g-last">Delete</a>

## Skins ##

info

## Plugins ##

Plugins can be used to control buttons behaviour, or to add new functions.

### Advanced Groups plugin ###

#### Groups and Minor groups ####

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

#### Mixed groups ####

Displaying a mixture of grouped and standalone buttons, as might be seen in a 
toolbar, can be done by adding another wrapping element with the class `button-container`.

    <div class="actions button-container">
        <a href="#" class="button primary">Admin</a>

        <div class="button-group">
            <a href="#" class="button primary">Unwatch</a>
            <a href="#" class="button">Fork</a>
            <a href="#" class="button">Pull Request</a>
        </div>

        <div class="button-group minor-group">
            <a href="#" class="button">10 Watchers</a>
            <a href="#" class="button">1 Forks</a>
        </div>
    </div>

## Browser compatibility ##

Full support: Firefox 3.5+, Chrome 3+, Safari 4+, IE 9+, Opera 11.10+

Good support: Firefox 3+, Chrome 1+, Safari 4+, IE 8+, Opera 10+

**Issues in older versions of browsers.**

IE 6:

- button icons and gradient is supported only trough additional fixer-skin (ie67.css)
- rounded corners and pill-like buttons is not supported
- size issues with `<button>` and `<input>` elements
- issues in Advanced Groups plugin

IE 7:

- button icons and gradient is supported only trough additional fixer-skin (ie67.css)
- rounded corners and pill-like buttons is not supported
- size issues with `<button>` and `<input>` elements

IE 8:

- gradient is supported only trough additional fixer-skin (ie67.css)
- rounded corners and pill-like buttons is not supported

Opera 10, 11.00:

- CSS3 gradient is not supported

## License ##

<a rel="license" href="http://creativecommons.org/publicdomain/mark/1.0/">
<img src="http://i.creativecommons.org/p/mark/1.0/88x31.png" 
style="border-style: none;" alt="Public Domain" /></a>

Public domain: [http://unlicense.org](http://unlicense.org)

## Acknowledgements ##

Originally it was a fork of Nicolas Gallagher's
[CSS3 GitHub Buttons](https://github.com/necolas/css3-github-buttons), 
but it grows up to a separate project.

Project evolution:
[GitHub](http://github.com) → [David Walsh](http://davidwalsh.name)'s [GitHub-Style Buttons with CSS and JavaScript](http://davidwalsh.name/github-css) → 
[Michael Henriksen](http://michaelhenriksen.dk)'s [CSS3 Buttons](http://github.com/michenriksen/css3buttons) → 
[Nicolas Gallagher](nicolasgallagher.com)'s [CSS3 GitHub Buttons](https://github.com/necolas/css3-github-buttons) → 
[gButtons](https://github.com/johnnyhuman/gbuttons) → Milk CSS3 UI Framework (You are here).

Icons from [Iconic pack](http://somerandomdude.com/projects/iconic/) by 
[some random dude](http://somerandomdude.com/). Licensed as 
[CC Attribution-Share Alike 3.0](http://creativecommons.org/licenses/by-sa/3.0/us/).
