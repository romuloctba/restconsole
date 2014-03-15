# REST Console ![GitHub version][github-image]

[![Build Status][travis-image]][travis-url]
[![Code Climate][codeclimate-image]][codeclimate-url]
[![Dependency Status][daviddm-image]][daviddm-url]
[![devDependency Status][daviddm-dev-image]][daviddm-dev-url]
[![Coverage Status][coveralls-image]][coveralls-url]
[![Total views][sourcegraph-image]][sourcegraph-url]

an HTTP Request Visualizer and Constructor tool, helps developers build, debug and test RESTful APIs.

## Features
- Syntax highlighting (multiple themes)
- Custom headers
- Construct POST or PUT body via raw input
- Auto Complete
- File upload
- Easy query parameters creation
- Add custom headers through intuitive ui
- Authentication support: Plain, Basic, OAuth + Custom
- Keyboard navigation and shortcuts
- Customizable Interface

## Table of contents

- [Download](#download)
- [Change Log](#changelog)
- [Documentation](#documentation)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Compiling](#compiling-)
- [Contributing](#contributing)
- [Contribute and Earn](#contribute-and-earn)
- [Donating](#donating)
- [Community](#community)
- [Versioning](#versioning)
- [Authors](#authors)
- [License](#license)

## Download

Download the latest production release on the [Chrome Web Store](http://restconsole.com)

## ChangeLog
* v4.0.2 oAuth improvements, Collapsible sections, Clickable Links in Response, UI enhancements, Bug Fixes.
* v4.0.1 Corrupted images in the previous build now fixed.
* v4.0.0 Brand New UI, enhanced oAuth, Multiple files upload, HTML Response preview.
* v3.0.7 Moving project to github.
* v3.0.6 UI enhancements, File uploads + "Save Default" Option.
* v3.0.5 More keyboard shortcuts.
* v3.0.4 Bug Fixes.
* v3.0.3 Keyboard navigation, Bug Fixes.
* v3.0.2 Syntax Highlighting themes, Collapsible sections, Options.
* v3.0.1 RAW request body, Bug Fixes.
* v3.0.0 Brand New UI.
* v2.1.1 Bug Fixes.
* v2.1.0 Added OAuth1.0a support, Bug Fixes.
* v2.0.0 Revamped Design.
* v1.0.0 Released!

## Documentation

Refer to the [Wiki](https://github.com/codeinchaos/restconsole/wiki) for detailed API documentation.

## Bugs and feature requests

Have a bug or a feature request? Please first read the [issue guidelines](CONTRIBUTING.md#using-the-issue-tracker) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/codeinchaos/restconsole/issues/new).

## Compiling [![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

this project uses [Grunt](http://gruntjs.com/). If you haven't used Grunt before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide.

### Available Grunt commands

| Function  | Command       | Description                                                                                                                               |
| --------- | ------------- | --------------------------------------------- |
| Build     | `grunt`       | Compiles.                                     |
| Tests     | `grunt test`  | Runs tests.                                   |
| Watch     | `grunt watch` | This is a convenience method for watching.    |

### Troubleshooting dependencies

Should you encounter problems with installing dependencies or running Grunt commands, uninstall all previous dependency versions (global and local). Then, rerun `npm install`.

## Contributing

Please read through our [contributing guidelines](CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

More over, if your pull request contains JavaScript patches or features, you must include relevant unit tests.

Editor preferences are available in the [editor config](.editorconfig) for easy use in common text editors. Read more and download plugins at <http://editorconfig.org>.

### Contribute and Earn

Donate bitcoins to this project or make commits and get tips for it. If your commit is accepted by project maintainer and there are bitcoins on its balance, you will get a tip!

[![tip for next commit][tip4commit-image]][tip4commit-url]

## Donating

Donations are welcome to help support the continuous development of this project.

[![GitTip][gittip-image]][gittip-url]
[![PayPal][paypal-image]][paypal-url]

## Community

Keep track of development and updates.

- Follow [@AhmadNassri](http://twitter.com/ahmadnassri) & [@RESTConsole](http://twitter.com/restconsole) on Twitter.
- Tweet [@RESTConsole](http://twitter.com/restconsole) with any questions/personal support requests.
- Implementation help may be found at Stack Overflow (tagged [`restconsole`](http://stackoverflow.com/questions/tagged/restconsole)).
- Read and subscribe to [My Blog](http://ahmadnassri.com).

## Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, this project is maintained under the Semantic Versioning guidelines. Sometimes we screw up, but we'll adhere to these rules whenever possible.

Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

- Breaking backward compatibility **bumps the major** while resetting minor and patch
- New additions without breaking backward compatibility **bumps the minor** while resetting the patch
- Bug fixes and misc changes **bumps only the patch**

For more information on SemVer, please visit <http://semver.org/>.

## Authors

**Ahmad Nassri**

- Twitter: [@AhmadNassri](http://twitter.com/ahmadnassri)
- Website: [ahmadnassri.com](http://ahmadnassri.com)

## License

Licensed under [the MIT license](LICENSE).

[github-image]: https://badge.fury.io/gh/codeinchaos%2Frestconsole.png
[bower-url]: http://badge.fury.io/bo/restconsole
[bower-image]: https://badge.fury.io/bo/restconsole.png
[npm-url]: http://badge.fury.io/js/restconsole
[npm-image]: https://badge.fury.io/js/restconsole.png
[travis-url]: https://travis-ci.org/codeinchaos/restconsole
[travis-image]: https://travis-ci.org/codeinchaos/restconsole.png?branch=master
[codeclimate-url]: https://codeclimate.com/github/codeinchaos/restconsole
[codeclimate-image]: https://codeclimate.com/github/codeinchaos/restconsole.png
[daviddm-url]: https://david-dm.org/codeinchaos/restconsole
[daviddm-image]: https://david-dm.org/codeinchaos/restconsole.png
[daviddm-dev-url]: https://david-dm.org/codeinchaos/restconsole#info=devDependencies
[daviddm-dev-image]: https://david-dm.org/codeinchaos/restconsole/dev-status.png
[coveralls-url]: https://coveralls.io/r/codeinchaos/restconsole
[coveralls-image]: https://coveralls.io/repos/codeinchaos/restconsole/badge.png
[sourcegraph-url]: https://sourcegraph.com/github.com/codeinchaos/restconsole
[sourcegraph-image]: https://sourcegraph.com/api/repos/github.com/codeinchaos/restconsole/counters/views.png
[gittip-url]: https://www.gittip.com/ahmadnassri/
[gittip-image]: http://img.shields.io/gittip/ahmadnassri.svg
[paypal-url]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=UJ2B2BTK9VLRS&on0=project&os0=restconsole
[paypal-image]: http://img.shields.io/badge/PayPal-Donate-green.svg
[tip4commit-url]: http://tip4commit.com/projects/638
[tip4commit-image]: http://tip4commit.com/projects/638.svg
