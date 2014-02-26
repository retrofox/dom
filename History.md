
1.0.2 / 2014-02-26 
==================

  * cmp: change isArray component dep by is-array
  * ignoring npm-debug.log file
  * Release 1.0.1
  * update component/to-function dep
  * pin component/to-function
  * Release 1.0.0
  * cleaner testing
  * Merge pull request #72 from bmcmahen/master
  * add #focus
  * pin component/css
  * Merge pull request #69 from dominicbarnes/ie8_compat
  * component/css@ie8_compat has been merged
  * using matthewp/text where necessary for IE8, handling document fragments differently in some places for IE8, adjusting tests for IE8 as well
  * using matthewp/keys in place of Object.keys (IE8 support)
  * using component/each for array iteration (IE8 support)
  * Merge pull request #65 from chemzqm/master
  * rebuild dom to use an array-like object
  * fix link
  * Merge pull request #63 from amasad/master
  * Use new iteration methods with the events lib
  * Merge pull request #60 from component/jquerify
  * separate .forEach(fn) and .each(fn). Based on: https://github.com/component/dom/pull/60#issuecomment-31502716
  * update css component to point to it's new home
  * update dom.use(fn) to support plugins
  * Use an array-like object (like jquery) & reorganize project.
  * Merge pull request #54 from ianstormtaylor/add/replace
  * add .replace() to the readme
  * add .replace() method with tests
  * fix makefile to "just work" for testing
  * Merge branch 'master' of github.com:component/dom
  * fix .html() return value of self
  * Merge pull request #52 from daynekilheffer/master
  * updated trim logic based on code review
  * trimming html on initial do call to clean up messy html. resolves issue #34 on component/dom
  * updated a .parent() unit test that would not have failed if the selector logic of parent was broken
  * Merge pull request #51 from daynekilheffer/master
  * correcting .html() test case
  * ocd
  * add mocha dep to package.json
  * add package.json back to try testling again
  * Merge pull request #46 from tyandell/patch-1
  * Fix insertAfter on a NodeList
  * build

1.0.1 / 2014-02-05
==================

 * pin component/to-function

1.0.0 / 2014-02-04
==================

 * BREAKING: Use an array-like object (like jquery) & reorganize project.
 * add: dom.use(fn) to support plugins
 * add: .replace()
 * fix: .html() return value of self
 * add: trimming html on initial to clean up messy html
 * fix: insertAfter on a NodeList

0.9.0 / 2013-08-03
==================

 * add "action" and "method" to attr shorthand methods
 * add `.parent([selector])`
 * add `.parents([selector])`
 * add `.next([selector])`
 * add `.prev([selector]])`
 * add `.is(selector)`

0.8.0 / 2013-07-01
==================

 * add .insertAfter()
 * add "type" attribute

0.7.1 / 2013-06-18
==================

 * add .reject()
 * pin deps

0.7.0 / 2013-05-27
==================

 * add .removeAttr(name)

0.6.0 / 2013-04-24
==================

  * add Enumerable iterator support. Closes #35

0.5.0 / 2013-04-14
==================

  * add .value([val])

0.4.0 / 2013-03-14
==================

  * add query dep for `.find()`
  * add `.empty()`

0.3.0 / 2013-03-13
==================

  * add component/css support. Closes #29
  * add `dom.js` build target

0.2.0 / 2013-02-23
==================

  * add event delegation example
  * add manipulation example
  * add initial .remove() implementation
  * add .text(str) tmp implementation
  * add `.prop()` method
  * add `.get()` == `.get(0)`
  * add `.appendTo()`
  * add `.removeClass(regexp)` support
  * add `.css(object)` support
  * change .append() and .prepend() to return new list
  * change `.attr()` to set attribute for each element

0.1.0 / 2013-01-04
==================

  * add .toggleClass(name, bool) support
  * fix for latest domify()

