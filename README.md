# React Server Rendering

**renderToString()**

ReactDOMServer.renderToString(element)

Render a React element to its initial HTML. This should only be used on the server. React will return an HTML string. You can use this method to generate HTML on the server and send the markup down on the initial request for faster page loads and to allow search engines to crawl your pages for SEO purposes.

If you call ReactDOM.render() on a node that already has this server-rendered markup, React will preserve it and only attach event handlers, allowing you to have a very performant first-load experience.

## References

[React renderToString() Performance and Caching React Components](https://codedump.io/share/xjW15JpT26nT/1/react-rendertostring-performance-and-caching-react-components)

[Strategies for server-side rendering of asynchronously initialized React.js components](http://stackoverflow.com/questions/25983001/strategies-for-server-side-rendering-of-asynchronously-initialized-react-js-comp)

[Server-Side Rendering With React, Node And Express](https://www.smashingmagazine.com/2016/03/server-side-rendering-react-node-express/)

[Discussion: Support asynchronous server rendering (waiting for data before rendering)](https://github.com/facebook/react/issues/1739)

[Suggestions: Speeding up Isomorphic app](http://stackoverflow.com/a/34835754/1672655)

[React DOM Stream](https://github.com/aickin/react-dom-stream)

[You’re Missing the Point of Server-Side Rendered JavaScript Apps](http://tomdale.net/2015/02/youre-missing-the-point-of-server-side-rendered-javascript-apps/)

[How to build React apps that load quickly using server side rendering](https://www.terlici.com/2015/03/18/fast-react-loading-server-rendering.html)

## Videos

[Hastening React SSR with Component Memoization and Templatization](https://www.youtube.com/watch?v=sn-C_DKLKPE)

[Reactjs - Speed up Server Side Rendering - Sasha Aickin](https://www.youtube.com/watch?v=PnpfGy7q96U)

## Discussions

[Support asynchronous server rendering (waiting for data before rendering)](https://github.com/facebook/react/issues/1739)