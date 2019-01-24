# mithril.js 2.0 Resources

mithril 2.0 is coming. It's exciting news because it is a well refined improvement of mithril. Online documentation of mithril is somewhat a "mixed bag", as old and new documents intertwine. Here are my notes dedicated to mithril 2.0, and hopefully it helps others too.


## Useful libraries and samples
* [create-mithril-app](https://www.npmjs.com/package/create-mithril-app) : like create-react-app, it sets up a mithril.js project with webpack already configured, plus webpack-dev-server
* [nile-mithril](https://nile-mithril.idgen.com) : A sample online bookstore written in mithril. It demonstrates how to interact with backend servers, maintain sessions, state and shoping history. [Source code is here](https://github.com/highmountaintea/nile-mithril). The backend is [nile-server](https://www.npmjs.com/package/nile-server). 
* [mithril-json-viewer](https://www.npmjs.com/package/mithril-json-viewer) : Renders a JSON structure into a tree structure that is collapsable. Here is the [demo](https://hungry-raman-deb8e1.netlify.com/).
* [mithril Forum](https://gitter.im/mithriljs/mithril.js) : where all the mithril experts hang out and give useful advices
* [bss](https://www.npmjs.com/package/bss) : popular way to do css in mithril.
* [Polythene](https://arthurclemens.github.io/polythene-demos/mithril/#/) and [construct-ui](https://vrimar.github.io/construct-ui/#/introduction/getting-started) : Two UI libraries that work with mithril. Promising, but haven't used yet.

See more [useful libraries](useful-libraries.md), or see some [mithril sample apps](sample-apps.md)

## Closure Components Notes
* It is the preferred way to create stateful component.
* You can create/maintain state via closure creation, or via oninit(), there is no difference.

## Class Components
* Still usable, but closure components preferred

## Deprecations
* `props()` and `withAttr()`
* replacement of `withAttr` is `oninput: e => val = e.target.value` (thanks to @osban)

## Router Notes
