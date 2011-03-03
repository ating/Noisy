Noisy is a jQuery plugin that adds random noise to a given element.

#### Here's an example:
    $('body').noisy({
        noise: 0.9, 
        tileSize: 200, 
        maxNoiseOpacity: 0.08,
        fallbackImage: 'fallback.png',
        monochromatic: false
    });

But since all parameters are optional you can just use it like this:
    $('body').noisy();

You can try the interactive demo [here](http://rappdaniel.com/other/noisy-sample/).

Contact
----
If you have any questions or suggestions that doesn't fit GitHub, send them to [@DanielRapp](http://twitter.com/DanielRapp)