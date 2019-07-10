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

### Results 🙋

1. Valid Latitude and/or Longitude returns `true`.
2. Invalid returns `false`.

#

<br>

### Size 🔬

Less-than < 1.5 kilobytes

#

<br>

### OK! Lets Get Started 💥

### Npm or Yarn installion

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

1. Setup an npm account (if not done aleardy)
2. Create a `package.json` at application root.

```json
{
  "name": "unique-npm-project-name",
  "version": "1.0.0", //_begin_with_1.0.0
  "description": "Descripton of my application",
  "main": "index.min.js",
  "license": "MIT", //_open_source_license!
  "keywords": ["list", "of", "searchable", "key", "words"]
}
```

3. `npm login`
4. `npm publish`

##### \*\*\* update package

1. `npm login`
2. `npm version` and the new version number ie: `1.0.1`
3. `npm publish`

##### \*\*\* am i still logged in?

1. `npm whoami`

#
