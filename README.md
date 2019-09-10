### Installation

Include the widget script at the end of body:
```html
<script src="https://carbon.dentist/js/widget.js" type="text/javascript"></script>
```

>Note: NPM version coming soon.

### Usage

Place the following div wherever you want on your page:
```html
<div id="carbon-widget"></div>
```
The widget will be rendered inside this div.

Next, use the following script to initialize the widget:

```html
<script type="text/javascript">
  window.onload = function () {
    CarbonWidget.init({
      key: 'my-key',
    });
  };
</script>
```

Here `my-key` is your online appointments url identificator. For example having the url https://carbon.dentist/online-appointments/ng1m43b54jg5 the key would be `ng1m43b54jg5`.
