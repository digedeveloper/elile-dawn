# elile


elile represents a HTML-first, JavaScript-only-as-needed approach to theme development. It's Shopify's first source available theme with performance, flexibility, and Online Store 2.0 features built-in and acts as a reference for building Shopify themes.

* **Web-native in its purest form:** Themes run on the evergreen web. We leverage the latest web browsers to their fullest, while maintaining support for the older ones through progressive enhancement—not polyfills.
* **Lean, fast, and reliable:** Functionality and design defaults to “no” until it meets this requirement. Code ships on quality. Themes must be built with purpose. They shouldn’t support each and every feature in Shopify.
* **JavaScript not required, fails gracefully:** We extract every bit of speed and functionality out of HTTP, semantic HTML, and CSS before writing our first line of JavaScript. JavaScript can only be used to progressively enhance features.
* **Server-rendered:** HTML must be rendered by Shopify servers using Liquid. Business logic and platform primitives such as translations and money formatting don’t belong on the client. Async and on-demand rendering of parts of the page is OK, but we do it sparingly as a progressive enhancement.
* **Functional, not pixel-perfect:** The Web doesn’t require each page to be rendered pixel-perfect by each browser engine. Using semantic markup, progressive enhancement, and clever design, we ensure that themes remain functional regardless of the browser.



## License

Copyright (c) 2021-present Shopify Inc. See LICENSE for further details.
