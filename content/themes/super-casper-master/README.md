# super-casper

A customized version of the [Ghost](http://github.com/tryghost/ghost/) Casper default theme combined with the
bootswatch theme [superhero](http://bootswatch.com/superhero/).

Social Buttons on the navbar in ***default.hbs*** need to be updated with your appropriate profile URLs or commented
out/removed. This section can be found by looking for:

````
{{! START SOCIAL BUTTONS}}
````

and

````
{{! END SOCIAL BUTTONS}}
````

Disqus comments have been added by default, though you can remove support by editing ***default.hbs*** and
***post.hbs***. The relevant sections are between the comments:

In order to use the Disqus block, your Disqus shortname defaults to your {{@blog.url}} value without http(s) or
any dots. But this can be modified as needed if you are unable to obtain that shortname via the Disqus setup.

````
{{! START DISQUS SUPPORT}}
````

and

````
{{! END DISQUS SUPPORT}}
````

After customizing is done, the folder can be zipped and uploaded as a theme.


## Copyright & License

Copyright (c) 2014 Jeremy Battle - Released under The MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
