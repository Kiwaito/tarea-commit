# Dark&Light Toggle Theme + Header

## Description
### D&L
When you click the button, the theme can change into black or white deppens of what you want. 

### Header
When you scroll down, the header turns into a navbar with a cool efect.

## Badges & Visuals
### D&L
![](https://i.imgur.com/Kx0tVGz.jpg)

### Header
![](https://i.imgur.com/gwcWQxN.gif)

## Usage
### D&L
```
const body = document.querySelector('body');
document.querySelector('.toggle').onclick = function() {
    body.classList.toggle('light')
}
```

First of all, we need to select wich will be our principal theme (black or white) and build the page, then in the CSS we are gonna change into the other one using this structure:

```
body.light .divname {
    the properties you gonna change
}
```

### Header
```
window.addEventListener("scroll",function(){
    const header = document.querySelector('header');
    header.classList.toggle('sticky', window.scrollY > 0);
});
```

Like the last one, we build our header and then we gonna edit our navbar like this:

```
header.sticky .menu  {
    properties
}
```

****

The "default" CSS of ich script are into the code.

## Authors
[How to toggle between dark and light mode](https://www.youtube.com/watch?v=JhVMAzrvdos)
[Responsive fullscreen animated sticky header](https://www.youtube.com/watch?v=dhmrN2EjkSg)

