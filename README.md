# Validation Latitude & Longtitude

<br>

### What this package does? 🤔

Tiny package for validating latitude & longitude string format.

```js
/* example */
const isValidStrings = ["40.6892", "74.0445"];
validationLatitudeLongitude.latLong(...isValidStrings); // true 🗽
```

#

<br>

### Results (Boolean)

1. Valid Latitude and/or Longitude returns `true`.
2. Invalid returns `false`.

#

<br>

### Size 🔬

Less-than < 1.5 kilobytes

#

<br>

### Npm or Yarn installion <img class="irc_mut" onload="typeof google==='object'&amp;&amp;google.aft&amp;&amp;google.aft(this)" width="20" height="20" data-iml="1561951820637" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAS1BMVEXLODf////IISDIHh346ur029vKMC/JKSjnr6/ZennotbXioaHJKyr03dzIJiXJLSzvy8rinZ3agYDTX17purrYdXTmrKzHGRfx1NTuo4y/AAABDElEQVR4nO3d2xGCMBRFUUQFRSGg+Oi/UhtQJh9kEpy1Czh3VgW3qiRJkiRJkiRJkiRJkiTpS8O+nIYkwPFQTmMKYt3vyqmv/114JCQkzB4hIWH+CAkJ80dISJg/QkLC/BESEuaPkDCpcL7ENb23KnzU16hez60Kz03cvfZESEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhISEhIWLCwWxhJ8tM5TN0azffIe81t/r0yhQTCKrSrFH2vWRhJApQkSZIkSZIkSZIkSZK0/T4/OWE9ZGh4pgAAAABJRU5ErkJggg==" alt="Image result for npm svg">

```bash
npm install validation-latitude-longitude

yarn add validation-latitude-longitude
```

<br>

### Import Module 📦

```js
import { validationLatitudeLongitude } from "validation-latitude-longitude";
```

<br>

### Methods ⚙️

```js
/* Valid Latitude Format? */
validationLatitudeLongitude.latitude(MY_LATITUDE);

/* Valid Longitude Format? */
validationLatitudeLongitude.longitude(MY_LONGITUDE);

/* Valid Latitude & Longitude Formats? */
validationLatitudeLongitude.latLong(MY_LATITUDE, MY_LONGITUDE);
```

<br>

### The End 🏝️

#

<br>
<br>
<br>

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/db/Npm-logo.svg/1200px-Npm-logo.svg.png" width=200>

<br>
<br>

### We could use your help! Please share your experience & code if you got a solution 🛠️to a unique problem 🚀. The community needs your support! ❤️

### Working with npm packages

##### \*\*\* New package

1. setup an npm account (if not done aleardy)
2. `npm login`
3. `npm publish`

##### \*\*\* update package

1. `npm login`
2. `npm version` and the new version number ie: `1.0.1`
3. `npm publish`

##### \*\*\* am i still logged in?

1. `npm whoami`

#
