# ZRender

ZRender is a lightweight graphic library which provides 2d draw for
[Apache ECharts](https://github.com/apache/echarts).

This repository is the ThingsBoard-maintained fork of
[zrender](https://github.com/ecomfe/zrender), consumed by the
[ThingsBoard fork of Apache ECharts](https://github.com/thingsboard/echarts) as
a GitHub archive tarball. Fork releases are tagged with a `-TB` version suffix.
The fork carries a pointer-transformer fix on top of the upstream 5.5.0 release
and commits the `lib` build output, which upstream generates only when
publishing to npm, so that the GitHub archive tarball installs the way the npm
package would; the `dist` bundles are rebuilt from this fork. See the Git
history for details of the changes.

## License

ZRender is licensed under the [New BSD License](LICENSE).

Some files in this repository are licensed under the
[Apache License, Version 2.0](licenses/LICENSE-Apache-2.0), some under the
MIT License ([Zepto](licenses/LICENSE-MIT-Zepto),
[snabbdom](licenses/LICENSE-MIT-snabbdom)), and the array diff helper is
derived from jsdiff under the
[New BSD License](licenses/LICENSE-BSD-3-Clause-jsdiff).

The original work is Copyright (c) 2017, Baidu Inc.
