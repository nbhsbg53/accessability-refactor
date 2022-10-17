# accessability-refactor
## Table of Contents

* [Description](#description)
* [Code Examples](#code-examples)
* [Important Links](#important-links)
* [Languages Used](#languages-used)
* [Questions](#questions)

## Description

This challenge was a ticket to refactor a marketing agency's existing website to make it more accessible. The intention of this challenge was to create a codebase that follows accessibility standards as well as ensure the site is optimized for search engines without creating any changes to the appearance or layout of the currently deployed website.

## Code Examples

Original Code (HTML)
```js
<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>website</title>
</head>
```
```js
<h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>
```
Updates Made (HTML)
```js
<header>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>website</title>
</header>
```
```js
<h3>Brand Awareness</h3>
            <figure>
                <a href="#">
            <img src="./assets/images/brand-awareness.png" alt="Brand Awareness" /></a>
        </figure>
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </div>
```
Original Code (CSS)
```js
.search-engine-optimization img {
    max-height: 200px;
}

.online-reputation-management img {
    max-height: 200px;
}

.social-media-marketing img {
    max-height: 200px;
}
```
Updates Made (CSS)
```js
.search-engine-optimization img {
    max-height: 220px;
}

.online-reputation-management img {
    max-height: 220px;
}

.social-media-marketing img {
    max-height: 220px;
}
```

## Important Links
GitHub Repository
(https://github.com/nbhsbg53/accessability-refactor)

Deployed Application
(http://127.0.0.1:5500/accessability-refactor/index.html#search-engine-optimization)



## Languages Used

HTML- (https://www.w3schools.com/html/)

CSS- (https://www.w3schools.com/css/default.asp)

## Questions

If you have any questions about this project, you can reach me at this email: nbhsbg53@gmail.com.

Github account: [nbhsbg53](https://github.com/nbhsbg53)

