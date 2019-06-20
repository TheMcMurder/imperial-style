# Imperial Style
Welcome to the Imperial Style Guide. This resource was created to facilitate consistency in our communications throughout all sectors, with an emphasis on clear and direct conveyance of our mission to uphold order in the galaxy through constant exploration of new technologies and an ideology that fear of force is as, if not more, effective as force itself. Adapted from https://imperialstyleguide.com/

## Installation

```bash
npm install imperial-style
```

## Usage
Add a `Link` tag to your app:

```html
<link rel='stylesheet' href='/node_modules/imperial-style/imperial.css'>
```

or from unpkg.com

```html
<link rel='stylesheet' href='https://unpkg.com/imperial-style/imperial.css'>
```

## Images
```html
<img src="/node_modules/imperial-style/img/imperial-logo.svg" >
```

or from unpkg.com

<img src="https://unpkg.com/imperial-style/img/imperial-logo.svg" >

## Optional API

```js
import { imperialBackground, characterMorph } from 'imperial-style';
import jQuery from 'jquery';

imperialBackground();   // Render a background canvas old "tv" effect
characterMorph(jQuery); // Render a character animation from Aurebesh to English
```