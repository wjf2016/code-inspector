# Changelog

## 0.5.1

- 【optimize】Enhance the cache strategy for injecting loader in `webpack`, significantly improving the performance of HMR.

## 0.5.0

- 【optimize】When the `injectTo` option is set, the injection loader of the interaction logic in `webpack/rspack` only takes effect for files specified in `injectTo`.
- 【feat】Added `dev` parameter, allowing users to customize the logic for determining the development environment.
- 【feat】Added `forceInjectCache` parameter, allowing users to enforce the caching strategy for the injection loader of the interaction logic in `webpack/rspack`.
- 【feat】Added `match` parameter, allowing users to specify the file types participating in source code location compilation to reduce the compilation of irrelevant files.

## 0.4.6

- 【fix】Resolved the issue where opening the corresponding code in VSCode was not possible on Windows systems when the installation path of VSCode contained Chinese characters.
- 【optimize】Improved the caching logic of `inject-loader` in `webpack/rspack`.

## 0.4.5

- 【fix】Fix the warning in the Vue framework related to `[Vue warn]: Extraneous non-props attributes (data-insp-path)`.

## 0.4.4

- 【fix】Fix the issue of plugins not working on Windows.

## 0.4.3

- 【fix】Fixed the issue of plugin in sub-applications not work in micro-frontends framework.

## 0.4.2

- 【fix】Fix the issue of server not starting and `net::ERR_CONNECTION_REFUSED` error caused by caching.

## 0.4.1

- 【feat】Support importing webpack plugin in ESM format.

## 0.4.0

- 【feat】Add support for SSR, Umijs, and all projects using `webpack, vite, rspack` as the underlying bundlers.

## 0.3.2

- 【fix】Fix the issue of failure to execute the `ps aux xxx` command on certain Linux systems to obtain running processes.
- 【fix】Fix the issue of failing to retrieve `rootPath` in some scenarios when used in Vite projects.

## 0.3.1

- 【fix】Fix the issue of incompatible use of the plugin with `eslint-loader` in webpack
- 【fix】Fix the issue of being able to recognizing the `code-insiders` IDE in macOS system

## 0.3.0

- 【feat】Support using in project whose framework is `solid` or `preact`
- 【feat】Rename the dom attribute `vc-path` to `data-insp-path`
- 【style】Optimize the style of inspect overlay
- 【fix】Compatible with users using `sudo` to start the dev service

## 0.2.0

- 【feat】Support using in project whose bundler is `rspack`

## 0.1.13

- 【fix】Invalid prop `data-insp-path` supplied to `Fragment`

## 0.1.12

- 【feat】Add parameters: `hideConsole` and `editor`

## 0.1.11

- 【optimize】Optimize dependencies version

## 0.1.10

- 【fix】Fix the issue of injecting path information into the React built-in component, which will cause an error to be reported on the console

## 0.1.9

- 【optimize】Removing file path verification for Windows systems

## 0.1.8

- 【feature】Added the `needEnvInspector` parameter to support scenarios where the plugin only takes effect when `CODE_INSPECTOR=true` is configured in `.local.env`
- 【fix】Fix the issue of full page refresh during hot updates when used in webpack

## 0.1.7

【fix】Fix the issue where the position of the jsx syntax positioning column will move forward one grid

## 0.1.6

【fix】The code locate function eliminates the compilation and recognition for nodes_modules

## 0.1.5

【feature】Add the locating of jsx syntax in ``.js' and '.ts' files

## 0.1.4

【fix】Optimizing the judgment criteria for the development environment when used in webpack

## 0.1.3

【docs】Update content of Readme

## 0.1.2

【feature】Optimize the combination key prompt function in the browser console on Mac and Windows systems

## 0.1.1

【types】Optimize typescript prompts for the `bundle` parameter during use

## 0.1.0

【feature】First Release!
