# x-carousel

`x-carousel` allows user to navigate through an overflowed section using button or touch depending on the device.

## Installation

1. Clone this repo
2. Install the dependencies with `bower install`

## Usage

Import the component into your project, e.g.

```
<link rel="import" href="../bower_components/x-carousel/x-carousel.html">
```

And declare the component with content to fill the slots (buttons are optional):

```
<x-carousel>
    <button type="button" slot="left-button" carousel-control-left>
        &lt;
    </button>
    <div class="cards" slot="content">
        <div class="card"></div>
        <div class="card"></div>
        ...
    </div>
    <button type="button" slot="right-button" carousel-control-right>
        &gt;
    </button>
</x-carousel>
```

## Contributing

1. Fork this repo and clone it locally
2. Follow the installation instructions above
3. Use [Polyserve](https://github.com/Polymer/polyserve) in development
4. Make a new branch and commit your changes
5. Push to your repository and make a pull request

## Credits

Developed at Kano Computing Ltd.

## License

GNU GENERAL PUBLIC LICENSE, version 3. See LICENSE.
