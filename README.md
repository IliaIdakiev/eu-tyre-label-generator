#EU Tyre Label Generator

    Using this module you can generate lables required by the EU when selling tyres.
    More info: [Click here](http://www.etrma.org/tyres/tyre-labelling)

Usage:

    1. Import css and script
    2. Create elements with class 'eu-tyre-label' and necessary attributes (data-fuel, data-rain, data-noise)

```html
<!DOCTYPE html>
<html>
    <head>
        <link rel="stylesheet" href="euTyreLabel.css">
        <script src="./euTyreLabel.js"></script>
    </head>
    <body>
        <div class="eu-tyre-label" data-fuel="A" data-rain="C" data-noise="50"></div>
        <br>
        <div class="eu-tyre-label" data-fuel="B" data-rain="A" data-noise="40"></div>
    </body>
</html>
```

Result:

![alt text](img/screener.png "EU Tyre Gen Result");
