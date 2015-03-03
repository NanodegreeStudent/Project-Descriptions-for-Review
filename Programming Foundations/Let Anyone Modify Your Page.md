# ![Andy](http://i.imgur.com/fdGeWES.png) Project Specification

Your project reviewer will review and provide feedback on two aspects of your
submission: the functionality of your web page and the text you've written
about what you've learned.

## 1 - Web Page / Code Review

Your reviewer will be looking for some basic functionality in your web page.
Namely, your page should:

* Be hosted on Google App Engine
* Allow users to add content to your site by submitting a form (with or without
  signing in, that's up to you).
* Use HTML escaping so that when users enter text like this: "*`<b>` tags are
  used to make text bold*" it displays properly.
* Properly save content so that when a user adds text and then refreshes the
  page it still displays the newly-added content.

Your reviewer will also look at your code. They will be looking for:

* Proper use of GET and POST requests.
* Use of separate HTML files / templates where appropriate (no HTML longer than
  5 lines should be written in your Python file(s)).
* Reasonable code readability:
  * No unused code
  * No commented out code
  * Informative variable / function / class names.
  * No "magic numbers" (a magic number is a number that is used in the code
    without explanation. In these situations you should assign that number to a
    variable with a logical name).

## 2 - Content Review

Your project reviewer will also read the text content on your page which
pertains to course 4. They will be looking for notes which demonstrate an
understanding of:

**Servers**: Your notes should demonstrate a basic understanding of how servers
handle requests, process them, and deliver responses.

**The Importance of Validating Input**: Your notes should acknowledge the
importance of validating user input, especially the implications that
validation has on site security and user experience.

**HTML Templates and Abstraction**: Your notes should show an understanding of
why programmers use HTML templates, how these templates allow programmers to
avoid repetition, and understanding of **why** avoiding repetition is
important.

The rubric that will be used is included below:

![Rubric, Pt. 1](http://i.imgur.com/M9Ni0DF.png)
![Rubric, Pt. 2](http://i.imgur.com/Na8Fg46.png)
