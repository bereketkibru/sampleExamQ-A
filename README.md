
# SampleExamQ-A

## QUESTION 70
You are modifying a blog site to improve search engine readability.
You need to group relevant page content together to maximize search engine readability.
Which tag should you use?

A. `<article>`

B. `<span>`

C. `<tbody>`

D. `<cd>`

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

# QUESTION 71
You develop an HTML application that contains a table that displays a list of products. The table is defined with the following HTML markup:

![sample code](https://github.com/bereketkibru/sampleExamQ-A/blob/master/img/71q1.PNG)

You must style the table to look like the following image:

![sample code](https://github.com/bereketkibru/sampleExamQ-A/blob/master/img/71q2.PNG)

You need to implement the CSS selectors to select the rows that must have a blue background.
Which CSS selector should you use?

A. thead:only-child, tbody:after, table:before

B. tr [line |-0, 1, 3]

C. tr:first-of-type, tr:last-of-type

D. tr:first-line, tr:last-child


## Answer C
## Explanation

>The :first-of-type selector matches every element that is the first child, of a particular type, of its parent.

>The :last-of-type selector matches every element that is the last child, of a particular type, of its parent.
___
## QUESTION 72
You develop a webpage by using HTML5. You create the following markup:

`<input type='url' name='website' required='required'>` 

You need to ensure that the value that the user enters contains a secure URL.

What should you do?

A. Add the following attribute to the input tag: value="https://"

B. Add the following attribute to the input tag: pattern="https://.+"

c. Add the following attribute to the input tag: value="ssl"

D. Add the following attribute to the input tag: itemtype="secure"
## Answer B
## Explanation
>The input pattern attribute specifies a regular expression that the input field's value is checked against, when the form is submitted.

The pattern attribute works with the following input types: text, date, search, url, tel, email, and password.
___
## QUESTION 73
You develop a webpage by using HTML5. You create the following markup and code: (Line numbers are included for reference only.)
![sample code](https://github.com/bereketkibru/sampleExamQ-A/blob/master/img/73.PNG)
You need to ensure that the values that users enter are only numbers, letters, and underscores, regardless of the order.

Which code segment should you insert at line 04?
![choices](https://github.com/bereketkibru/sampleExamQ-A/blob/master/img/73c.PNG)
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

>To get a string contains only letters (both uppercase or lowercase)  numbers, and underscores, regardless of the order we use a regular expression  (/^[A-Za-z0-9_]+$/).
 Next the match() method of string object is used to match the said regular expression against the input value.
 ___

 ## QUESTION 74
You are creating an HTML5 application that allows users to play video on a page by using the VIDEO element.
You need to enable the user to start, stop, and pause the video.
Which line of code should you add to the page?

A. `<video id= "myVideo" height="320" width="400" src="myVideo.vtt" contextmenu="pauseplay"> </video>`

B. `<video id="myVideon height"="320" width="400" src="myVideo.vtt" controls> </video>`

C. `<video _d="myVideon height="320" width="400" src="myVideo.vtt" autoplay> </video>`

D. `<video id="myVideo" height="320" width="400" src="myVideo.vtt" contextinenu="Startstopn> </video>`
## Answer B
## Explanation
The HTML `<video>` 

>Element To show a video in HTML, use the `<video>` element:

>The __controls__ attribute adds video controls, like play, pause, and volume

___
## QUESTION 75
You are creating a web page that contains a canvas with text.
The page contains the following JavaScript code. 

var canvas = document.getElementById("myCanvas");

var context = canvas.getContext("2d");

The text on the canvas must rotate 90 degrees when a user clicks a button on the page.

You need to ensure that the text rotates when the user clicks the button.
Which line of code should you add at line 03?

A. context.transform(90);

B. context.content.getRotation(90);

C. context.rotate(90);

D. context.content.rotate (90);
## Answer B
## Explanation
>The `<canvas>` tag is used to draw graphics, on the fly, via scripting (usually JavaScript).

>The `<canvas>` tag is transparent, and is only a container for graphics, you must use a script to actually draw the graphics.

### Draw on the Canvas With JavaScript 

#### Step 1: Find the Canvas Element

First of all, you must find the `<canvas>` element.

This is done by using the HTML DOM method getElementById():
```javascript
var canvas = document.getElementById("myCanvas");
```
#### Step 2: Create a Drawing Object

Secondly, you need a drawing object for the canvas.

The getContext() is a built-in HTML object, with properties and methods for drawing:

```javascript
var context = canvas.getContext("2d");
```

#### Transformations

The __rotate()__ method rotates the current drawing.

Note: The rotation will only affect drawings made AFTER the rotation is done.

>JavaScript syntax:	  context.rotate(angle);

>*To calculate from degrees to radians: degrees*Math.PI/180.
Example: to rotate 5 degrees, specify the following: 5*Math.PI/180*

The __transform()__ method replaces the current transformation matrix. It multiplies the current transformation matrix with the matrix described 
>JavaScript syntax:	context.transform(a,b,c,d,e,f);

>The transform() method behaves relatively to other transformations made by rotate(), scale(), translate(), or transform(). Example: If you already have set your drawing to scale by two, and the transform() method scales your drawings by two, your drawings will now scale by four.
___

## QUESTION 76
You develop an HTML5 webpage that contains the following HTML markup:
![sample code](https://github.com/bereketkibru/sampleExamQ-A/blob/master/img/76q.PNG)

The page includes the following JavaScript code:

var selectedValues='';
>You have the following requirements:

  * Retrieve the content for any OPTION elements when the value of the selected attribute equals selected.
  * Add the content to a comma separated string.

You need to retrieve the required data.

Which two code segments should you add to the webpage?

Each correct answer presents a complete solution.
>NOTE: Each correct selection is worth one point

![choices](https://github.com/bereketkibru/sampleExamQ-A/blob/master/img/76c.PNG)

## Answer C & D
## Explanation
>:checked->
Select all checked elements (checkboxes or radio buttons):

>:selected->

* Select the pre-selected item(s) in a drop-down list:
* The :selected selector selects option elements that are pre-selected.

>we can use different ways to address the options elements 
  * select options:selected
  * #loanTypes options:selected
>Then the each function loop over the values genereted by the selector not loanTypes.
___

## QUESTION 77
You develop an HTML5 application. You give users a numeric access code that can be used only one time.
Users must enter the numeric access code in the login form of the application. 
The numeric characters must be hidden by a __masking character__.

You need to implement the form element for users to enter the code.

Which HTML element should you use?
![choices](https://github.com/bereketkibru/sampleExamQ-A/blob/master/img/77c.PNG)

## Answer A
## Explanation

The characters in a password field are masked (shown as asterisks or circles)

The autocomplete attribute specifies whether or not an input field should have autocomplete enabled.
___

## QUESTION 78

You are developing an HTML5 web application that displays stock information.
The application loads information from a web service by using AJAX.
The following code defines a Stock object and loads stock data.

![sample code](https://github.com/bereketkibru/sampleExamQ-A/blob/master/img/78q.PNG)

You need to implement the loadStock function.
Which code segment should you use?
![choices](https://github.com/bereketkibru/sampleExamQ-A/blob/master/img/78c.PNG)
## Answer A
Not clear for me?

___

# QUESTION 79
You are developing a web page that includes the following HTML

`<span id="myTextSpan" class="redText">Hello There!</span>`

The font color of text inside the span must be red.

You need to develop the web page to meet the requirement.

Which two code segments achieve the goal? Each correct answer presents a complete solution.

NOTE: Each correct selection is worth one point.

![choices](https://github.com/bereketkibru/sampleExamQ-A/blob/master/img/79c.PNG)
## Answer B & C
## Explanation 
> css() :-Sets or returns one or more style properties for selected elements
* . class selector

* \# id selector
___

<style type="text/css">
    ol { list-style-type: upper-alpha; }
</style>