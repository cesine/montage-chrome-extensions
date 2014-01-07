montage-chrome-extensions
=========================

## Chrome extension getting started, in MontageJS

Example showing how to use MontageJS in a Chrome extension (using the [Chrome Extension getting started guide](http://developer.chrome.com/extensions/getstarted.html))

1. minit create:app -n montage-chrome-extensions  582007cc609421a7ab7ff4e87074cd08ed5661ad
2. add a manifest and icon a89a0cdf470f54791c01f7f0fd6af27a57b3bfbb
3. add content security policy csp unsafe-eval 6ba0fb5d6ad78799e4d6ac352e1389c6054631fd
4. add popup.html style css 7ee9dac4c9306ee70abcdc16088d97bb78e02f31
5. add popup.js f40cb5eb2ee69156fb80967880983e70645f6c9d
6. convert popup code to property descriptors instead of object notation cb049569c767020e697d81ccb47f0713ba9ab320


## Optional: MVC-ify the example

The original chrome extension is using vanilla js, with no data binding. But Montage is made for binding data, so we can use binding instead to clean up the main.js code.

7. use binding and a repetition to populate images

Why stop there? We can make our kitten app modular by moving the image search result code into a component.

8. create an image search result component for more maintainability
