# Compass Normalize.css

This simple plugin for [Compass](http://compass-style.org/) enables you to use [normalize.css](http://necolas.github.com/normalize.css/) in your stylesheets without having to download it.


## Installation

From the command line:

	$ (sudo) gem install compass-normalize

You can also install the gem from your local fork:

	$ git clone git://github.com/ksmandersen/compass-normalize.git
	$ rake build
	$ rake install

When creating a new project with compass:

	$ compass create new_project -r compass-normalize --using compass-normalize

If using an existing project, edit your config.rb and add this line:

	require 'compass-normalize'


## Usage

To use the normalize plugin, just import and include normalize:

	@import normalize;

You can also just import parts you need:

	@import "normalize/base";  // Basic styles
	@import "normalize/html5"; // HTML5 elements
	@import "normalize/forms"; // Form elements

## Acknowledgements
Many thanks to [Frederic Hemberger](https://github.com/fhemberger/) who contributed greatly to this project.

## License
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to [The Unlicense](http://unlicense.org/)

### Major components:

* [normalize.css](http://necolas.github.com/normalize.css/): Public domain