# firefox-psp-config
A firefox config optimized for privacy, security, and performance at the cost of some convenience

The auto-config script has only been tested in Arch Linux.

## Features
- Uses ghacks' user.js
- Enables more privacy, security, and performance features in user.js
- Sets DuckDuckGo Lite as the default search engine
- Installs Https Everywhere
- Installs Unblock Origin
- Installs NoScript
- Installs h264ify to improve performance and reduce battery usage
- Enables dark-compact mode

## References
- https://duckduckgo.com/lite
- https://github.com/ghacksuserjs/ghacks-user.js/
- https://github.com/EFForg/https-everywhere
- https://github.com/gorhill/uBlock
- https://github.com/hackademix/noscript
- https://github.com/erkserkserks/h264ify-firefox
- https://unix.stackexchange.com/questions/326897

## TODO:
- For malware protection reasons, search engine and theme can't be set with user.js
	- Use ESR to set DuckDuckGo Lite as default search engine
	- Use ESR to set Dark Compact theme as default
