# dirty-json

[ ![Codeship Status for RyanMarcus/dirty-json](https://codeship.com/projects/cbc19870-2e42-0132-d30c-4adef3b19db7/status)](https://www.codeship.io/projects/39346)  [![Coverage Status](https://coveralls.io/repos/github/RyanMarcus/dirty-json/badge.svg?branch=master)](https://coveralls.io/github/RyanMarcus/dirty-json?branch=master) ![NPM version](https://badge.fury.io/js/dirty-json.svg)


[ ![AGPL](http://www.gnu.org/graphics/agplv3-155x51.png) ](http://www.gnu.org/licenses/agpl-3.0.en.html)


```
npm install dirty-json
```


A JSON parser that tries to handle non-conforming or otherwise invalid JSON.

Turn this:

    [5, .5, 'single quotes', "quotes in "quotes" in quotes"]

Into this:

    [5,0.5,"single quotes","quotes in \"quotes\" in quotes"]

## License
> Copyright 2018, 2016, 2015, 2014 Ryan Marcus
> dirty-json is free software: you can redistribute it and/or modify
> it under the terms of the GNU Affero General Public License as published by
> the Free Software Foundation, either version 3 of the License, or
> (at your option) any later version.
> 
> dirty-json is distributed in the hope that it will be useful,
> but WITHOUT ANY WARRANTY; without even the implied warranty of
> MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
> GNU Affero General Public License for more details.
> 
> You should have received a copy of the GNU Affero General Public License
> along with dirty-json.  If not, see <http://www.gnu.org/licenses/>.
