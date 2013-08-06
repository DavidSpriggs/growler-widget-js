growler-widget-js
=================

Growl notifications widget for the js api.

```javascript
var growler = new Growler({}, "growlerDijit");
growler.startup();

growler.growl({
 title: "Warning!",
 message: "Best check yo self, you're not looking too good.",
 level: "warning"
});
```
Available growl params:
```javascript
{
  title: "Title",
  message: "Message",
  level: "default", //can be: 'default', 'warning', 'info', 'error', 'success', if empty will be 'default'
  timeout: 10000, //set to 0 for no timeout
  opacity: 1.0,
}
```
Screen from Sample page:
![Screenshot](https://raw.github.com/ArcGIS/growler-widget-js/master/screenshot.PNG)
