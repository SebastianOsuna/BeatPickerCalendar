BeatPicker
==========

**All credits to:** https://github.com/ACT1GMR

Simple and powerful date picker widget for jQuery
## Dependencies
* jQuery1.8.0+
* BeatPicker.min.js
* BeatPicker.min.css

## Links
* [Original repo](https://github.com/ACT1GMR/BeatPicker)
* [Download page](http://act1gmr.github.io/BeatPicker/)
* [Live demo](http://act1gmr.github.io/BeatPicker/demos.html)
* [Docs](http://act1gmr.github.io/BeatPicker/docs.html)

## Disclaimer from @SebastianOsuna
This repo has been modified for my own needs. Refer to the original repo for updates and support.

## Changes from original
* Icon and clear modules disabled by default.
* Icon data removed to reduce file size.
* Added Spanish support.

``` var options = {dateInputNode:$("input"), locale: 'es'}; ```

* Removed readonly property as default
* Added 'Declarative syntax' support for locale (only Spanish)
* Added support to select multiple dates

```javascript
var options = {selectionRules: { multiple: false }};
elem.on('select', function (event) {
  // event = {dates: [], string: 'date1, date2', timeStamp: now)};
});
```

* Added support for simple months name

```
var options = {dateFormat: { format: ['YYYY', 'SM', 'DD'] }}
// 2016-Aug-08
var options = {dateFormat: { format: ['YYYY', 'NM', 'DD'] }}
// 2016-August-08
```

