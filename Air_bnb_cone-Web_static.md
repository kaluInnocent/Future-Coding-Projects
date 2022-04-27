

0x01. AirBnB clone - Web static
===============================

Concepts
--------

*For this project, students are expected to look at these concepts:*

-   [HTML/CSS](https://alx-intranet.hbtn.io/concepts/2)
-   [The trinity of front-end quality](https://alx-intranet.hbtn.io/concepts/4)

![](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2021/9/135ef103cf7ed150c9760aadc66844113dfc3d35.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20220427%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220427T200514Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d2abbe579f79651896082bb61471e99d813e81d6f592609425d1a63215918931)

Background Context
------------------

### Web static, what?

Now that you have a command interpreter for managing your AirBnB objects, it's time to make them alive!

Before developing a big and complex web application, we will build the front end step-by-step.

The first step is to "design" / "sketch" / "prototype" each element:

-   Create simple HTML static pages
-   Style guide
-   Fake contents
-   No Javascript
-   No data loaded from anything

During this project, you will learn how to manipulate HTML and CSS languages. HTML is the structure of your page, it should be the first thing to write. CSS is the styling of your page, the design. I really encourage you to fix your HTML part before starting the styling. Indeed, without any structure, you can't apply any design.

Before starting, please fork or clone the repository `AirBnB_clone` from your partner if you were not the owner of the previous project.

Resources
---------

**Read or watch**:

-   [Learn to Code HTML & CSS](https://alx-intranet.hbtn.io/rltoken/T9KyiA6_Tm3Ny6oTn08S-A "Learn to Code HTML & CSS") (*until "Creating Lists" included*)
-   [Inline Styles in HTML](https://alx-intranet.hbtn.io/rltoken/7NdYbImFNofpB_FXXn3otg "Inline Styles in HTML")
-   [Specifics on CSS Specificity](https://alx-intranet.hbtn.io/rltoken/z_OTPFCjmhXJJi7KJqBCbQ "Specifics on CSS Specificity")
-   [CSS SpeciFishity](https://alx-intranet.hbtn.io/rltoken/7iqk-el4ZVnKeyLoON8Rqg "CSS SpeciFishity")
-   [Introduction to HTML](https://alx-intranet.hbtn.io/rltoken/okP4V3RxFXHkEcQo19AnuQ "Introduction to HTML")
-   [CSS](https://alx-intranet.hbtn.io/rltoken/Ir8Ka59FO6Z_vJQ-gkSG_w "CSS")
-   [MDN](https://alx-intranet.hbtn.io/rltoken/BpSXtcWOGH0UT4XLCoQyJg "MDN")
-   [center boxes](https://alx-intranet.hbtn.io/rltoken/Tlje4XYwyZbUfHkQWGi1WQ "center boxes")

Learning Objectives
-------------------

At the end of this project, you are expected to be able to [explain to anyone](https://alx-intranet.hbtn.io/rltoken/Zb9sTIct2xdhDCDLGF-RyQ "explain to anyone"), **without the help of Google**:

### General

-   What is HTML
-   How to create an HTML page
-   What is a markup language
-   What is the DOM
-   What is an element / tag
-   What is an attribute
-   How does the browser load a webpage
-   What is CSS
-   How to add style to an element
-   What is a class
-   What is a selector
-   How to compute CSS Specificity Value
-   What are Box properties in CSS

Requirements
------------

### General

-   Allowed editors: `vi`, `vim`, `emacs`
-   All your files should end with a new line
-   A `README.md` file, at the root of the folder of the project, is mandatory
-   Your code should be W3C compliant and validate with [W3C-Validator](https://alx-intranet.hbtn.io/rltoken/NzQ96QXtBTCMRDicPORzbA "W3C-Validator")
-   All your CSS files should be in `styles` folder
-   All your images should be in `images` folder
-   You are not allowed to use `!important` and `id` (`#...` in the CSS file)
-   You are not allowed to use tags `img`, `embed` and `iframe`
-   You are not allowed to use Javascript
-   Current screenshots have been done on `Chrome 56` or more.
-   No cross browsers
-   You have to follow all requirements but some `margin`/`padding` are missing - you should try to fit as much as you can to screenshots

More Info
---------

![](https://s3.amazonaws.com/intranet-projects-files/concepts/74/hbnb_step1.png)

Quiz questions
--------------

#### Question #0

Is the following HTML markup valid?

```
<html></html>

```

(elements are correctly tagged, we don't care about `!Doctype` here)

-   [ ]

    Yes

-   [ ]

    No

#### Question #1

Is the following HTML markup valid?

```
<html>
    <head>
    </head>
    <body>
    </body>
</html>

```

(elements are correctly tagged, we don't care about `!Doctype` here)

-   [ ]

    Yes

-   [ ]

    No

#### Question #2

Is the following HTML markup valid?

```
<html>
    <head>
    </head>
    <body>
    <body>
</html>

```

(elements are correctly tagged, we don't care about `!Doctype` here)

-   [ ]

    Yes

-   [ ]

    No

#### Question #3

Is the following HTML markup valid?

```
<html>
    <head>
    </head>
    <body>
        <img src="logo.png" />
    </body>
</html>

```

(elements are correctly tagged, we don't care about `!Doctype` here)

-   [ ]

    Yes

-   [ ]

    No

#### Question #4

Is the following HTML markup valid?

```
<html>
    <head>
    </head>
    <body>
        <h1>Best <b>School</h1></b>
    </body>
</html>
[O
```

(elements are correctly tagged, we don't care about `!Doctype` here)

-   [ ]

    Yes

-   [ ]

    No

#### Question #5

Is the following HTML markup valid?

```
<html>
    <head>
    </head>
    <body>
        <h1>
            <a href="www.google.com'>Google</a>
        </h1>
    </body>
</html>

```

(elements are correctly tagged, we don't care about `!Doctype` here)

-   [ ]

    Yes

-   [ ]

    No

#### Question #6

Is the following HTML markup valid?

```
<html>
    <head>
    </head>
    <body>
        <h1>
            <a href="www.google.com">Go to <b>Google</b>
        </h1>
    </body>
</html>

```

(elements are correctly tagged, we don't care about `!Doctype` here)

-   [ ]

    Yes

-   [ ]

    No

#### Question #7

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #8

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

* {
    font-size: 14px;
}

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #9

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

* {
    font-size: 14px;
    font-weight: 400
    text-align: center;
}

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #10

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

* {
    font-size: 14px;
    text-align: center;

    h1 {
        margin: 30px;
    }
}

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #11

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

* {
    font-size: 14px;
    text-align: center;
    margin: 30px 12px 4px;
}

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #12

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

h1.title {
    font-size: 16px;
}

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #13

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

div.filters h2 {
    font-size: 16px;
}

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #14

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

div.filters p.title h2 span.text.big {
    font-size: 20px;
}

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #15

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

h3,
div.full_text,
div.small_text h4,
div.filters p.title {
    font-size: 20px;
}

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #16

Is following CSS syntax valid?

```
body {
    color: #FF0000;
}

h3,
div.full_text
div.small_text h4
div.filters p.title {
    font-size: 20px;
}

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #17

In the following code, is the text `Best School` red?

*css:*

```
h1 {
    color: red;
}

```

*html:*

```
<h1>Best School</h1>

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #18

In the following code, is the text `Best School` red?

*css:*

```
h2 {
    color: red;
}

```

*html:*

```
<h1>Best School</h1>

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #19

In the following code, is the text `Best School` red?

*css:*

```
h1.title {
    color: red;
}

```

*html:*

```
<h1>Best School</h1>

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #20

In the following code, is the text `Best School` red?

*css:*

```
h1 div.title {
    color: red;
}

```

*html:*

```
<h1>Best School</h1>

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #21

In the following code, is the text `Best School` red?

*css:*

```
h3 span.text,
h1,
div.title {
    color: red;
}

```

*html:*

```
<h1>Best School</h1>

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #22

In the following code, is the text `Best School` red?

*css:*

```
h1 {
    color: green;
}

span.my_title {
    color: red;
}

```

*html:*

```
<h1>
    <span class="my_title">Best School</span>
</h1>

```

-   [ ]

    Yes

-   [ ]

    No

#### Question #23

In the following code, is the text `Best School` red?

*css:*

```
h1 .my_title {
    color: green;
}

.my_title {
    color: red;
}

```

*html:*

```
<h1>
    <span class="my_title">Best School</span>
</h1>

```

-   [ ]

    Yes

-   [ ]

    No

Submit answers

Please make sure to validate all quiz questions before moving on to project tasks
---------------------------------------------------------------------------------

Copyright © 2022 ALX, All rights reserved.
