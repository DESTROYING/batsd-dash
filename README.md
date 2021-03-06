Batsd-dash
==========

Batds-dash is a configurable dashboard for [batsd-server](https://github.com/noahhl/batsd).
The front-end uses [NVD3](http://nvd3.org/) for rendering graphs. The back-end uses 
[Sinatra](github.com/sinatra/sinatra/) for the actual web application.

The application server is designed to use a threaded [connection pool](https://github.com/mperham/connection_pool).
Thus, it is suggested that you run Batsd-dash on JRuby or Rubinius in order 
to take full advantage of threaded processing.

### Documentation

  * [Installation and
    Configuration](https://github.com/mikeycgto/batsd-dash/wiki/Installation-and-Configuration)
  * [Running the
    Application](https://github.com/mikeycgto/batsd-dash/wiki/Running-the-Application)
  * [Viewing
    Graphs](https://github.com/mikeycgto/batsd-dash/wiki/Viewing-Graphs)
  * [Data API](https://github.com/mikeycgto/batsd-dash/wiki/Data-API)
  * [Custom Pages](https://github.com/mikeycgto/batsd-dash/wiki/Custom-Pages)
  * [Contributing](https://github.com/mikeycgto/batsd-dash/wiki/Contributing)

### About

This is project is maintained and developed by [@mikeycgto](https://twitter.com/mikeycgto) 
and [@btoconnor](https://twitter.com/btoconnor) mainly for use on [BreakBase](http://breakbase.com).

### License

Copyright (c) 2012 Michael J Coyne & Brian O'Connor

Permission is hereby granted, free of charge, to any person obtaining a copy of this 
software and associated documentation files (the "Software"), to deal in the Software
without restriction, including without limitation the rights to use, copy, modify,
merge, publish, distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be included in all copies
or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR
PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE
FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
