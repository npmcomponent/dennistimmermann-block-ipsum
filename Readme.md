*This repository is a mirror of the [component](http://component.io) module [dennistimmermann/block-ipsum](http://github.com/dennistimmermann/block-ipsum). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/dennistimmermann-block-ipsum`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# block-ipsum

Insert placeholders for simple mockups instead of lorem ipsum
▄▄▄▄▄▄ ▄▄▄▄▄▄▄▄▄▄▄▄ ▄▄▄ ▄▄▄▄▄▄ ▄▄▄▄▄▄▄ ▄▄▄▄▄▄▄ ▄▄ ▄▄▄▄▄ ▄▄▄▄▄

## Installation
### bower

Install with [bower](http://bower.io):

	$ bower install block-ipsum

### component

Install with [component(1)](http://component.io):

    $ component install dennistimmermann/block-ipsum

## API

block-ipsum automatically inserts ▄▄▄▄ ▄ ▄▄▄▄▄ for you in every DOM-Node with the data-ipsum attribute.

### Usage

	<p data-ipsum="20"></p>

will be converted to

	<p>▄▄▄ ▄▄▄▄▄▄ ▄▄ ▄▄ ▄▄▄</p> 



## License

  The MIT License (MIT)

  Copyright (c) 2014 <copyright holders>

  Permission is hereby granted, free of charge, to any person obtaining a copy
  of this software and associated documentation files (the "Software"), to deal
  in the Software without restriction, including without limitation the rights
  to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
  copies of the Software, and to permit persons to whom the Software is
  furnished to do so, subject to the following conditions:

  The above copyright notice and this permission notice shall be included in
  all copies or substantial portions of the Software.

  THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
  IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
  FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
  AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
  LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
  OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
  THE SOFTWARE.