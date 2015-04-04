
# [es6-features.org](http://es6-features.org/)

### ECMAScript 6: Feature Overview &amp; Comparison

This is the source of the website [es6-features.org](http://es6-features.org/),
a small overview of
[ECMAScript 6](http://wiki.ecmascript.org/doku.php?id=harmony:specification_drafts)
language features and a comparison to the older/traditional
[ECMAScript 5](http://www.ecma-international.org/publications/files/ECMA-ST/ECMA-262.pdf)
equivalents.

## Frequently Asked Questions? (FAQ)

- *Why was it setup? Is the ECMAScript 6 draft not enough?*

  It was setup by computer scientist and software
  architect [Ralf S. Engelschall](mailto:rse@engelschall.com) in March 2015 in order to
  promote ECMAScript 6 in the software engineering projects around him
  and to have bookmarkable URLs at hand for referencing certain ECMAScript 6 features.

- *Where can I find the current browser support status quo for ECMASCript 6?*

  Have a look at the regularily updated
  [ECMAScript compatibility table](http://kangax.github.io/compat-table/es6/) by kangax.

- *Where can I find the latest ECMAScript 6 standard?*

  The final ECMAScript 6 standard is still not published. But you can find the
  latest drafts on [ecmascript.org](http://wiki.ecmascript.org/doku.php?id=harmony:specification_drafts).

- *How can I use ECMAScript 6 if my JavaScript runtime still does not support it?*

  Use the awesome [Babel](http://babeljs.io/) transpiler. For Node.js/io.js environments
  just use its tricky [`require` hook](http://babeljs.io/docs/usage/require/). For browser environments use Babel in conjunction
  with [Browserify](http://browserify.org/) and its [Babelify](https://github.com/babel/babelify) plugin. For
  other tools see [Using Babel](http://babeljs.io/docs/using-babel/).

- *Why uses the website for ECMAScript 6 the "modernized style" without semicolons as
  the default, but for ECMAScript 5 the "traditional style" with semicolons?*

  ECMAScript since its earliest days supported automatic semicolon
  interference, of course. But people coding ECMAScript 5 started it
  in an era where lots of tools (especially source code compressors)
  had problems when simicolons where left out from the source code. As
  a consequence, most ECMAScript 5 coders sticked to the traditional
  coding style with semicolons. But this era is gone today. Both
  ECMAScript 6 and all tools (including compressors) perfectly support
  automatic semicolon interference nowadays. As a consequence,
  ECMAScript 6 coders nowadays finally can nearly get rid of all
  semicolons and this way clutter their source code a lot less with bare
  syntactic sugar. Ralf S. Engelschall is a strong promoter of reducing
  source codes to its bare minimum. Hence, in his personal opinion
  ECMAScript 6 should be coded without semicolons. But if you
  disagree, just switch the shown style on the website. If you even
  need to enforce a particular style for both ES6 and ES5 code snippets
  in your bookmarks, just use one of the following URLs:
  [ES6-Features (modernized style)](http://es6-features.org/#modernized) or
  [ES6-Features (traditional style)](http://es6-features.org/#traditional)

- *I still don't understand: why should I use ECMAScript 6? ECMAScript 5 looks sufficient.*

  ECMAScript 5 is a nice and decent programming language, of course. But
  because of its history, it has some nasty aspects which ECMAScript 6
  finally resolves. As programming never is just about getting the necessary
  functionality done, it is advised to also use the best language,
  too. ECMAScript 6's language design is cleaner than ECMAScript 5,
  its syntax increases the expressiveness of your code, it decreases the
  necessary boilerplate code (e.g. `function` vs. arrow syntax) and it
  especially let you get rid of some very nasty but required hacks and
  workarounds from the ECMAScript 5 era (e.g. `var self = this`).
  So, ECMAScript 5 might be sufficient, but ECMAScript 6 nevertheless
  is an important improvement.

- *I've found a mistake, how can I contribute?*

  The source is the file `features.txt`, everything else on [es6-features.org](http://es6-features.org) is
  just generated out of it. Fork this project on Github, edit the file
  `features.txt` and then please send a pull request.

