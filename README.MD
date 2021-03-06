# docker-money

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://github.com/wharley/docker-money)

> My money for Docker using MERN.

![Markdown Course](image/docker-money.png)

# Development

* Cloning the repo

```bash
$ git clone https://github.com/wharley/docker-money.git
```

# Create file '.env' inside directory ./backend/src/
```json
module.exports = {
	"authSecret": "Youcanchangethiskey"
}
```

# Docker

> To start the application you will need docker and docker-compose installed on the machine.

* Build image

```bash
$ docker-compose build
```

* Start containers

```bash
$ docker-compose up
```

# License

Copyright (c) 2017 Wharley Ornelas da Rocha

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
