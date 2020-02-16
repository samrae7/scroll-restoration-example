# Scroll Restoration Demo

Basic demo of Scroll Restoration

By default browsers will automatically scroll to your previous scroll position if you click the back button.

This can be overidden by setting `history.scrollRestoration` to `"manual"` ( it is `"auto"` by default).

You can try it out by running this example, opening the dev tools console, typing `window.history.ScrollRestoration = "manual"` and hitting return. After that you will see the default scrolling stops.

See [MDN](https://developer.mozilla.org/en-US/docs/Web/API/History/scrollRestoration)
