# Links and Images in HTML

## Anchor elements
To create a link in HTML, we use anchor element, anchor element is basically defined as wrapping the text or another HTML element we want to be a link with an <a> tag
```html
<a>About The Odin Project</a>
```
clicking the above link doesnt do anything, anchor doesnt know where to link to unless we tell it
<br> thereofre its used like this
```html
<a href="https://www.theodinproject.com/about">About The Odin Project</a>
```
## Opening links in a new tab
 the `<target>` attribute.
<br> specifies where the linked resource will be opened. If it is not present, then, by default, it will take on the `_self` value which opens the link in the current tab. To open the link in a new tab or window (depends on browser settings) we can set it to `_blank` as follows:
```html
<a href="https://www.theodinproject.com/about" target="_blank" rel="noopener noreferrer">About The Odin Project</a>
'''
 `rel` attribute above this attribute is used to describe the relation between the current page and the linked document.

## Links
Links: Use the `<a>` (anchor) tag to create links in HTML. The `href` attribute specifies the destination URL, and target="_blank" opens links in new tabs. 
<br> Types of Links:
<br> Absolute Links link to external sites with full URLs.
<br> Relative Links link to internal pages using file paths.

## Images
Use the `<img>` tag to display images, with src for the image location and alt for descriptive text.

