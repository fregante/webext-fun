# webext-fun

WebExtension packages for every need, by [@fregante](https://github.com/fregante).

![Sand in your node_modules folder](https://user-images.githubusercontent.com/1402241/127905928-829c007b-0b04-4162-99b5-a4fd2e6305bf.JPG)

## Helpers

* [webext-alert](https://github.com/fregante/webext-alert) - `alert()` for background pages/workers in Web Extensions.
* [webext-storage](https://github.com/fregante/webext-storage) - A more usable typed storage API for Web Extensions.
* [webext-patterns](https://github.com/fregante/webext-patterns) - Convert the patterns of your WebExtension manifest to regex.
* [webext-polyfill-kinda](https://github.com/fregante/webext-polyfill-kinda) - Super-lightweight Promised wrapper around `chrome.*` API to be used in modules.
* [webext-storage-cache](https://github.com/fregante/webext-storage-cache) - Cache values in your Web Extension and clear them on expiration.
* [webext-detect](https://github.com/fregante/webext-detect) - Detects where the current browser extension code is being run.
* [webext-tools](https://github.com/fregante/webext-tools) - Utility functions for Web Extensions.
* [webext-events](https://github.com/fregante/webext-events) - High-level events and utilities for events in Web Extensions.
* [webext-msg](https://github.com/fregante/webext-msg) - Simple message handler
* [webext-content-scripts](https://github.com/fregante/webext-content-scripts) - Utility functions to inject content scripts from a WebExtension.
* [webext-permissions](https://github.com/fregante/webext-permissions) - Get any optional permissions that users have granted you.

## Solutions

* [webext-dynamic-content-scripts](https://github.com/fregante/webext-dynamic-content-scripts) - Automatically registers your content_scripts on domains added via permission.request
* [webext-options-sync](https://github.com/fregante/webext-options-sync) - Helps you manage and autosave your extension's options.
* [webext-options-sync-per-domain](https://github.com/fregante/webext-options-sync-per-domain) - Helps you manage and autosave your extension's options, separately for each additional permission
* [webext-permission-toggle](https://github.com/fregante/webext-permission-toggle) - Browser-action context menu to request permission for the current tab.
* [webext-inject-on-install](https://github.com/fregante/webext-inject-on-install) - Automatically add content scripts to existing tabs when your extension is installed.
* [webext-base-css](https://github.com/fregante/webext-base-css) - Extremely minimal stylesheet/setup for Web Extensions’ options pages (also dark mode)
* [webext-active-tab](https://github.com/fregante/webext-active-tab) - Track `activeTab` permission; automatically inject content scripts.
* [webext-bugs](https://github.com/fregante/webext-bugs) - Useful fixes and workarounds for browser extension shortcomings.

<!--

* [webext-content-script-ping](https://github.com/fregante/webext-content-script-ping) - One-file interface to detect whether your content script have loaded.

-->

Also check out:

* [Awesome-WebExtensions](https://github.com/fregante/Awesome-WebExtensions) - A curated list of awesome resources for WebExtensions development.
* [promise-fun](https://github.com/sindresorhus/promise-fun) - The inspiration for this repo.

Examples of personal Web Extensions using the patterns above:

* [refined-github](https://github.com/refined-github/refined-github) Browser extension that simplifies the GitHub interface and adds useful features
* [GhostText](https://github.com/fregante/GhostText) 👻 Use your text editor to write in your browser. Everything you type in the editor will be instantly updated in the browser (and vice versa).
* [npmhub](https://github.com/npmhub/npmhub) 🔎 A browser extension to explore npm dependencies on GitHub repos
* [github-issue-link-status](https://github.com/fregante/github-issue-link-status) Colorize issue and PR links to see their status (open, closed, merged)
