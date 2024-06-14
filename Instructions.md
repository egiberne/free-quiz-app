# Learn Accessibility by Building a Quiz

## Step 1 
Welcome to the first part of the Accessibility Quiz. As you are becoming a seasoned HTML and CSS developer, we have started you off with the basic boilerplate.

Start this accessibility journey by providing a `lang` attribute to your `html` element. This will assist screen readers in identifying the language of the page.

## Step 2
You may be familiar with the meta element already; it is used to specify information about the page, such as the title, description, keywords, and author.

Give your page a meta element with an appropriate charset value.

The charset attribute specifies the character encoding of the page, and, nowadays, UTF-8 is the only encoding supported by most browsers.

## Step 3
Continuing with the meta elements, a viewport definition tells the browser how to render the page. Including one betters visual accessibility on mobile, and improves SEO (search engine optimization).

Add a viewport definition with a content attribute detailing the width and initial-scale of the page.


## Step 33
If you click on the radio inputs, you might notice both inputs within the same true/false fieldset can be selected at the same time.

Group the relevant inputs together such that only one input from a pair can be selected at a time.


## Step 34
To prevent unnecessary repetition, target the before pseudo-element of the p element, and give it a content property of "Question #".

## Step 35
The final section of this quiz will contain a dropdown, and a text box.

Begin by nesting a div with a class of formrow, and nest four div elements inside of it, alternating their class attributes with question-block and answer.

## Step 36 
Within the div.question-block elements, nest one label element, and add a CSS related question to the label text.

## Step 37
Within the first div.answer element, nest one required select element with three option elements.

Give the first option element a value of "", and the text Select an option. Give the second option element a value of yes, and the text Yes. Give the third option element a value of no, and the text No.

## Step 38
Link the first label element to the select element, and give the select element a name attribute.

## Step 39
Nest one `textarea` element within the second `<div class="answer">` element, and set the number of rows and columns it has.

Then, give the `textarea` **placeholder** text describing an example answer.

## Step 40
As with the other `input` and `label` elements, link the `textarea` to its corresponding `label` element, and give it a `name` attribute.