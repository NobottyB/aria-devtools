# <img src="https://github.com/ziolko/accessibility/raw/master/extension/logo-256.png" width="24"> ARIA DevTools

Creating accessible web applications is difficult. It gets even harder if you don't understand how people with disabilities use computers. 

With ARIA DevTools you see your website the way screen readers present it to the blind users. All page elements are presented according to their explicit or implied ARIA roles. This includes headings, images, tables and form items beyond others. 

It's now easy to spot missing ARIA labels, misused ARIA roles, and incomplete keyboard support. This makes testing and development of accessible websites easier.

![Screeshot of ARIA DevTools](https://lh3.googleusercontent.com/MhZVpZIrzkP7QEQqJYy5qOfvJuM3Ns52Ri7npeU7XHl24buihw-b8d9cl1jeL8hvuvOHaJA_=w640-h400-e365-rj-sc0x00ffffff)

This extension is available for free for [Chrome](https://chrome.google.com/webstore/detail/aria-devtools/dneemiigcbbgbdjlcdjjnianlikimpck?hl=en) and [Firefox](https://addons.mozilla.org/pl/firefox/addon/aria-devtools/).

## Usage
Install the extension, open your website and click the 
<img src="https://github.com/ziolko/accessibility/raw/master/extension/logo-256.png" width="16"> browser extension icon.

## Contributors ✨
I highly appreciate all pull requests and raised issues. You can also help by sharing this extension with your friends on Twitter and starring this repository.

[![](https://github.com/ziolko.png?size=60)](https://github.com/ziolko)
[![](https://github.com/pcorpet.png?size=60)](https://github.com/pcorpet)
[![](https://github.com/ctemplin.png?size=60)](https://github.com/ctemplin) 

## Working with this repository

### Prerequisites
1. NodeJS (e.g. 10.15.1)
2. YARN (e.g. 1.17.3)

### Development environment
1. `yarn`
2. `yarn start`
3. Load the `extension` directory as an unpacked extension 
in the browser [extensions page](Chrome extensions page). 

Note: You need to enable _Developer Mode_ in the Chrome extensions 
page to load unpacked extensions. 

### Building production artifact 
1. `yarn`
2. `yarn build` 

The build result can be found in the `extension` directory.

## License 
MIT
