# server-only

Version of React's [server-only](https://www.npmjs.com/package/server-only) that doesn't throw an error when used in node runtime. Useful in monorepos where shared packages shouldn't be exposed to client code but are used in both react-server and node runtimes.