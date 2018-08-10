# responsiveDevices.css

![responsiveDevices.js Logo](logo.png)

*Fresh, responsive CSS-only devices that scale with your content and look great on any screen!*

It's rather annoying to have badly scaled CSS devices on your landing/demo page. Often they'll not quite fit your screenshots properly, and may resize badly on certain devices, resulting in annoying overflow (scroll) here or there.

ResponsiveDevices.css fixes that by giving you simple, componentised CSS classes to 'build' your own neatly scaled devices. All the classes are responsive and you can add or remove features (such as speakers or screen reflections) as you please.

## Devices

- Android Phone (16:9 aspect ratio)
- iPhone (16:9 aspect ratio)
- iPhoneX (16:9 aspect ratio)
- Android Tablet (4:3 aspect ratio)
- iPad (4:3 aspect ratio)
- iMac (16:9 aspect ratio)

You just need to worry about setting the correct aspect ratio for your content, and the CSS classes will take care of scaling themselves. Your demo pages will look great on any screen!

All devices are available in black and white skins, except the iMac :)

## Example: White iPhone

Simply include the appropraite css files (for an iPhone you need `common.css` and `iphone.css`). Then add the following markup and you're done!

```html

<div class='deviceContainer' style='width: 50%; max-width: 500px;'>
    <div class="iphone white portrait">
        <div class="caseBorder"></div>
        <div class="case"></div>
        <div class="reflection"></div>
        <div class="screen"></div>
        <div class="camera"></div>
        <div class="speaker"></div>
        <div class="homeButtonBorder"></div>
        <div class="homeButton"></div>
        <div class="content" style=""></div>
    </div>              
</div>
```
Scale the width of the containing `div` as per your requirements. Also, feel free to add or remove device features (simply add or remove the inner most `div` elements). Ordering of the inner `div` elements does not matter.

## Demos + Documentation
Demo: https://osrec.github.io/ResponsiveDevices.css/samples.html - like what you see? Give us a :star: !

For your convenience, device markup is available at: https://osrec.co.uk/products/responsivedevicescss (click any device in the **device library** section to view it's corresponding HTML markup)

## Credits

Created by OSREC Technologies (https://osrec.co.uk) - give us a shout for any consulting enquiries at https://osrec.co.uk/contact :smile:

Funded by the Bx project (https://usebx.com) - check them out if you need a slick, free business/project management/time tracking app :dollar: :watch: :thumbsup:

## License

Free for personal/non-commercial use. Small fee applies for commercial use to help support the library (see https://osrec.co.uk/products/responsivedevicescss)

## Issues

Raise a ticket on github and we will respond ASAP. If you've bought a commercial license, [contact us here](https://osrec.co.uk/contact), quoting your license code and we'll respond even quicker :wink:
