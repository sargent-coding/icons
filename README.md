# Sargent Coding Icons
These icons were originally created for Sargent Coding projects, but they're open to everyone to use now.

## How to use
The icons framework has three ways of adding icons:
### Inline icons
You can add an inline icon by placing something like:
```html
<saco-icon name="pencil"></saco-icon>
```
### Adding icons via Javascript
You also have ***two*** methods of adding icons using Javascript:

#### The `new` keyword
It's simpler to use the `new` keyword to make icons:
```javascript
let myNewIcon = new Icon("pencil");
document.body.append(myNameIcon);
```

#### The `Element.setAttribute()` method
But, you can also create an element and set its `name` attribute:
```javascript
let myNewIcon = document.createElement("saco-icon");
myNewIcon.setAttribute("name", "pencil");
document.body.append(newNewIcon);
```

### Changing an icon
Changing an icon is really easy-- and you also have two ways to do it:

#### Setting the `name` property
You can set the `name` property to something else:
```javascript
myNewIcon.name = "javascript";
```

#### Settings the `name` attribute
or you can also use `document.setAttribute()`:
```javascript
myNewIcon.setAttribute("name", "javascript");
```

## Credits
All icons as of 20 April 2022 were designed by @aetinx.
