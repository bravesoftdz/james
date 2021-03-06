# James

[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/mdbs99/james/blob/master/README.md)

**ATTENTION:** We're still in a very early alpha version, the API may and will change frequently. Please, use it at your own risk, until we release version 1.0.

James is a collection of classes and interfaces for truly object-oriented projects written in Object Pascal.
This API is being written in [Free Pascal](https://freepascal.org/) and [Lazarus](http://www.lazarus-ide.org/). However, make it compatible with Delphi could be possible or even might be a goal (we are depending of more contributors to make it possible).

**Why**. We don't want to write procedural code anymore. We want write elegant, clean, and maintainable code using OOP.

**Principles.** The code has some design principles:

* Fully interface-based
* Memory is released automatically
* All public methods are implementations of interface methods
* All public methods return an interface instance or primitive type
* No usage of NULL in arguments or returns
* No algorithms in constructors
* No getters and setters
* No type casting or reflection
* No procedures and functions, only Objects

**Dependencies**. For now, we have some dependencies:

* [Synapse](http://synapse.ararat.cz/doku.php/download)

In the future, one goal is to put all dependencies as optional, using different packages.

## How to contribute?

To contribute we suggest following these steps:

1. Fork this project (Click on **Fork** bottom)
2. Clone your forked project to your local machine (`git clone
https://github.com/USERNAME/james.git`)
3. Open an issue describing about the problem or enhancement that you are going to make.
After that, take note the issue ID (the "#" next to issue title)
4. Create a new branch following this pattern: `issue#ISSUE-ID` (`git checkout -b issue#ISSUE-ID`)
5. Make the changes and all necessary commits
6. Push the new branch to your Github repository (`git push origin issue#ISSUE-ID`)
7. Go to James' Github project and click on **Compare & Pull Request**

**Important:**
- Each PR need to work only in one issue, respecting the [single responsibility principle](https://en.wikipedia.org/wiki/Single_responsibility_principle).
- Make sure your branch builds without any warnings/issues.

If you have questions or general suggestions, don't hesitate to submit
a new [Github issue](https://github.com/mdbs99/james/issues/new).

## License (MIT)

Copyright (c) 2017 Marcos Douglas B. Santos

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
