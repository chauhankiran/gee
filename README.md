# gee

> A component-first small style framework with simplicity and easiness.

**Attention: Currently, in heavy development! Contributions are welcome.**

Currently supported components (in-basic forms) are

1. Reboot
2. Typography
3. Grid
4. Buttons
5. Navigations
6. Lists
7. Alert
8. Tables
9. Forms
10. Text Utilities
11. Space Utilities

## Build

Gee is written in CSS. So, theoretically, it does not require any build process. You can use `gee.css` file in your webpage. But, that requires to have other `import`ed files. So, this build process generate only one file for you to use.

The currently build process is simple and somewhat a hack. You might not like it. But, I'm improving it!

1. Install `postcss-cli` globally.
   ```
   $ npm i -g postcss-cli
   ```
2. Install `postcss-import` globally.
   ```
   $ npm i -g postcss-import
   ```
3. Install `postcss-clean` globally.
   ```
   $ npm i -g postcss-clean
   ```

The requires packages are installed. To build development version of Gee, use following command.

```
$ npm run dev
```

This will create `gee.css` file in root directory.

To build minified or production version of Gee, use following command.

```
$ npm run prod
```

This will create `gee.min.css` file in root directory.

## License

```
MIT License

Copyright (c) 2020 Kiran Chauhan

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
```
