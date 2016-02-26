# ethicalweb.org

Code and content for the ethicalweb.org web site.

_Ethical Web Development_ is a series of free digital books, written by Adam Scott to be published by O'Reilly Media. They are being written as open source. The source for the books can be found at [https://github.com/ascott1/ethical-web-dev](https://github.com/ascott1/ethical-web-dev).

## Running this site locally

The site is built with [Jekyll] and includes a npm build process for front-end assets. Because of this, you will need Ruby and Node to run the site locally. If this is a barrier to entry, I'd encourage you to make recommendations for changes in the issues.

[Jekyll]: https://jekyllrb.com/

### Install

Install Jekyll:

```
gem install jekyll
```

Fork, then clone the repo:

```
git clone git@github.com:your-username/ethicalweb.org.git
```

From the ethicalweb.org directory, install the npm dependencies:

```
npm install
```

## Running the site-title

Running `npm start` will start Jekyll and watch the CSS for changes

```
npm start
```


## Code of Conduct

This project adheres to the [Contributor Covenant 1.4][code-of-conduct]. By participating, you are expected to honor this code. Please report unacceptable behavior to adamdscott@protonmail.com.
[code-of-conduct]: http://contributor-covenant.org/version/1/4/

## Content License

[Creative Commons Attribution-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/) (CC BY-SA 4.0)

## Code License

The MIT License (MIT)

Copyright (c) 2016 Adam Scott

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
