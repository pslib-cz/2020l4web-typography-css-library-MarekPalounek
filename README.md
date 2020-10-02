# Typography CSS library
**Author:** *Marek Palounek*
## Demo site
Link to **[demo](http://www.github.io)** site for preview.

## Description
This typgrahy library is mainly identified for blog writers.
It is created with CSS which is based on styling HTML tags, but there are a few classes. 

## Implementation
Just link 2 CSS files into your web head.

*Note: The normalize.css must be first in order.*

+You have to link google fonts as you see in dependecies

## Dependecies
```html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./normalize.css">
    <link rel="stylesheet" href="./style.css">
    <link
        href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;200;300;400;600;700;800;900&family=Roboto:wght@100;300;400;700;900&display=swap"
        rel="stylesheet">
    <title>Your web</title>
</head>
```

## Components
### Typography
Usable tags are:
```html
<h1> - <h4>
<p> <b> <em> <small> <strong> <a> <article> <img> <figure> <figcaption>
```

### Order and unorder lists
```html
<ul class="ul1">
    <li> List 1</li>
    <ul class="ul2">
        <li>List 1.1</li>
    </ul>
</ul>

<ol class="ol1">
    <li> List 1</li>
    <ol class="ol2">
        <li>List 1.1</li>
    </ol>
</ol>
```
### Images
```html
<figure>
    <img src="./.../your image.jpg" alt="image">
    <figcaption> Your possible image (<i>Author: Somebody</i>) </figcaption>
</figure>
```
