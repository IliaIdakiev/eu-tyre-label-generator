#EU Tyre Label Generator

Using this module you can generate lables required by the EU when selling tyres.
More info: [Click here](http://www.etrma.org/tyres/tyre-labelling)

Usage:

1. Install:
    bower install eu-tyre-label-gen
2. Import scripts
3. Create elements with class 'eu-tyre-label' and necessary attributes (data-fuel, data-rain, data-noise)

```html
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="bower_components/eu-tyre-label-gen/euTyreLabel.css">
        <script src="bower_components/eu-tyre-label-gen/euTyreLabel.js"></script>
    </head>
    <body>
        <div class="eu-tyre-label" data-fuel="A" data-rain="C" data-noise="50"></div>
        <br>
        <div class="eu-tyre-label" data-fuel="B" data-rain="A" data-noise="40"></div>
    </body>
</html>
```

Result:

<img src="img/screener.png" alt="alt text" title="EU Tyre Gen Result">
