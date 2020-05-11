# Spring Boot Ember Starter

This is a small starter project that hooks up basic project pipeline to support Java Spring Boot for a server backend, and Ember.js for the frontend.

### Tech Stack
- Java Spring Boot `2.2.7.RELEASE`
- Ember Octane `v3.18.0`
- Node `v12.16.3`
- Yarn `v1.22.4`

## development

- `npm install -g ember-cli@3.18.0`
- `git clone git@github.com:erikyuzwa/spring-boot-ember-starter.git`
- `cd spring-boot-ember-starter`

## browser testing

- Run the Spring Boot backend within your favorite IDE
- Open another terminal window:
  - `cd frontend`
  - `ember serve` (or `yarn start`)
  - http://localhost:4200

## unit tests

The default Ember `testem` stack is untouched from the install. To run:
- `cd frontend`
- `ember test` (or `yarn run test`)

The default Spring Boot tests are run with:
- `mvnw test`


## building for deployment

- `mvnw clean && mvnw package`
- compiled `WAR` is in the `target` subfolder

## LICENSE

MIT License

Copyright (c) 2020 Erik Yuzwa

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
