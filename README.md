# Phrase object (with palindrome detector)

This is a sample NPM module created following along the [Learn Enough JavaScript to Be Dangerous](https://www.learnenough.com/course/javascript) tutorial.

The module can be used as follows:

```
$ npm install --global andyh-palindrome
$ vim test.js
let Phrase = require("andyh-palindrome");
let napoleonsLament = new Phrase("Able was I, ere I saw Elba.");
console.log(napoleonsLament.palindrome());
$ node test.js
true
```