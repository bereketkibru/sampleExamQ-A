<style type="text/css">
    ol { list-style-type: upper-alpha; }
</style>
# SampleExamQ-A

## QUESTION 70
You are modifying a blog site to improve search engine readability.
You need to group relevant page content together to maximize search engine readability.
Which tag should you use?
1. `<article>`
2. `<span>`
3. `<tbody>`
4. `<cd>`
## Answer A
## Explanation
   The `<article>` tag allows to mark separate entries in an online publication, such as a blog or a magazine. It is expected that when articles are marked with the `<article>` tag, this will make the HTML code cleaner because it will reduce the need to use `<div>` tags. Also, probably search engines will put more weight on the text inside the `<article>` tag as compared to the contents on the other parts of the page.
  
  The `<article>` element specifies independent, self-contained content.

An article should make sense on its own, and it should be possible to distribute it independently from the rest of the web site.

> Examples of where an `<article>` element can be used:

* Forum post
* Blog post
* Newspaper article
___

## QUESTION 72
You develop a webpage by using HTML5. You create the following markup:

`<input type='url' name='website' required='required'>` 

You need to ensure that the value that the user enters contains a secure URL.

What should you do?
1. Add the following attribute to the input tag: value="https://"
2. Add the following attribute to the input tag: pattern="https://.+"
3. Add the following attribute to the input tag: value="ssl"
4. Add the following attribute to the input tag: itemtype="secure"
## Answer B
## Explanation
>The input pattern attribute specifies a regular expression that the input field's value is checked against, when the form is submitted.

The pattern attribute works with the following input types: text, date, search, url, tel, email, and password.
___
## QUESTION 73
You develop a webpage by using HTML5. You create the following markup and code: (Line numbers are included for reference only.)
![sample code](./img/73.png)
You need to ensure that the values that users enter are only numbers, letters, and underscores, regardless of the order.

Which code segment should you insert at line 04?
![choices](./img/73c.png)
## Answer A
## Explanation
>let see the syntax used on each regexp

* ^ Start of string or start of line depending on multiline mode. (But when [^inside brackets], it means "not")

* [set_of_characters] Matches any single character in set_of_characters. By default, the match is case-sensitive.

* `+` It tells the computer to repeat the preceding character (or set of characters) for at least one or more times(up to infinite).

* `$`	End of string or end of line depending on multiline mode. Many engine-dependent subtleties.

* /W : matches any non-word character

* /d : matches any digit character
* /S : matches any non-whitespace characters

To get a string contains only letters (both uppercase or lowercase)  numbers, and underscores, regardless of the order we use a regular expression  (/^[A-Za-z0-9_]+$/).
 Next the match() method of string object is used to match the said regular expression against the input value.
 ___

  