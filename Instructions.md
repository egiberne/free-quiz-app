# Learn Accessibility by Building a Quiz


## Step 1 | Specifies the language of the element's content
Welcome to the first part of the Accessibility Quiz. As you are becoming a seasoned HTML and CSS developer, we have started you off with the basic boilerplate.

Start this accessibility journey by ***providing a `lang` attribute to your `html` element***. This will assist screen readers in identifying the language of the page.

## Step 2 | Specifies the character encoding
You may be familiar with the meta element already; it is used to specify information about the page, such as the title, description, keywords, and author.

Give your page a meta element with an ***appropriate charset value***.

The charset attribute specifies the character encoding of the page, and, nowadays, *UTF-8* is the only encoding supported by most browsers.

## Step 3 | Specifies the user's visible area of a web page to make the website look good on all devices
Continuing with the meta elements, a viewport definition tells the browser how to render the page. Including one betters visual accessibility on mobile, and improves SEO, search engine optimization.

***Add a viewport definition with a content attribute detailing the width and initial-scale of the page***.


## Step 33
If you click on the radio inputs, you might notice both inputs within the same **true/false** fieldset can be selected at the same time.

Group the relevant inputs together such that only one input from a pair can be selected at a time.


## Step 34
To prevent unnecessary repetition, target the before pseudo-element of the p element, and give it a content property of *"Question #"*.

## Step 35
The final section of this quiz will contain a dropdown, and a text box.

Begin by nesting a div with a class of formrow, and nest four div elements inside of it, alternating their class attributes with question-block and answer.

## Step 36 
Within the div.question-block elements, nest one label element, and add a CSS related question to the label text.

## Step 37
Within the first `<div class="answer">` element, nest one required select element with three option elements.

Give the first option element a value of "", and the text Select an option. Give the second option element a value of yes, and the text Yes. Give the third option element a value of no, and the text No.

## Step 38
Link the first `label` element to the `select` element, and give the `select` element a `name` attribute.

## Step 39
Nest one `textarea` element within the second `<div class="answer">` element, and set the number of rows and columns it has.

Then, give the `textarea` **placeholder** text describing an example answer.

## Step 40
As with the other `input` and `label` elements, link the `textarea` to its corresponding `label` element, and give it a `name` attribute.

## Step 41
Do not forget to give your `form` a submit button with the text `Send`.

## Step 42
Two final s  ntic HTML elements for this project are the `footer` and `address` elements. The `footer` element is a container for a collection of content that is related to the page, and the `address` element is a container for contact information for the author of the page.

After the `main` element, add one `footer` element, and nest one `address` element within it.

# Step 43
Within the address element, add the following:

### Example Code ###
```html
freeQuizExam <br/>
Toronto<br/>
Ontario <br/>
CA
```

The `br` tags will allow each part of the address to be on its own line and are useful for presenting `address` elements properly.

# Step 44
The `address` element does not have to contain a physical geographical location. It can be used to provide a link to the subject.

Wrap a link around the text *freeQuizExam*, and set its location to `https://freeQuizExam.org`.

# Step 45
Back to styling the page. Select the list elements within the navigation bar, and give them the following styles:

### Example Code ###
```css
color: #dfdfe2;
margin: 0 0.2rem;
padding: 0.2rem;
display: block;
```

# Step 46
On the topic of visual accessibility, contrast between elements is a key factor. For example, the contrast between the text and the background of a heading should be at least **4.5:1**.

Change the font color of all the anchor elements within the list elements to something with a contrast ratio of at least **7:1**.

# Step 47
To make the navigation buttons look more like typical buttons, ***remove the underline from the anchor tags***.

Then, create a new selector targeting the navigation list elements so that ***when the cursor hovers over them, the background color and text color are switched, and the cursor becomes a pointer***.


## Step 48 | Using Flexbox
Tidy up the `header`, by using *Flexbox* to put *space between* the children, and vertically *center* them.

Then, fix the `header` to the *top* of the *viewport*.

## Step 49 | Specifies H1 element for small screen
When the screen width is small, the `h1` does not wrap its text content how it should. Align the text for the `h1` element in the *center*.

Then, give the `main` padding such that the **Student Info** section `header` can be fully seen.

## Step 50 | Specifies `ul` element for small screen
On small screens, the unordered list in the navigation bar overflows the right side of the screen.

Fix this by using Flexbox to *wrap* the `ul `content. Then, set the following CSS properties to correctly *align* the text:

### Example Code
```css
align-items: center;
padding-inline-start: 0;
margin-block: 0;
height: 100%;
```

## Step 51 | Specifies the size of the `section` element
Set the `width` of the `section` elements to **80%** of their parent container. Then, use margins to *center* the `section` elements, adding **10px** to the *bottom* *margin*.

Also, ensure the `section` elements cannot be larger than **600px** in `width`.


## Step 52 | Specifies marging of `h2` element
Replace the *top* `margin` of the `h2` elements with **60px** of *top* `padding`.


## Step 53 | Specifies the padding of claass `info`
Add `padding` to the top and left of the `.info` elements, and set the other values to **0**.


## Step 54 | Specifies the style of the `form` element
Give the `.formrow` elements top `margin`, and left and right `padding`. The other padding values should be **0**.

Then, ***increase the `font-size` for all input elements***.


## Step 55 | Specifies the `input` element within `info` class
To make the first `section` look more `inline`, target only the input elements within `.info` elements, and set their` width` to **50%**, and `left-align` their text.

## Step 56 | Specifies the `label` element into `info` class
Target all `label` elements within `.info` elements, and set their `width` to **10%**, and make it so they do not take up less than **55px**.


## Step 57 | Specifies display and alignment for `input` and `label` elements
To align the `input` boxes with each other, create a new ruleset that targets all `input` and `label` elements within an `.info` element and set the `display` property to `inline-block`.

Also, align the `label` element's text to the `right`.



## Step 58 | Specifies the `.question-block `elements
To neaten the `.question-block` elements, set the following CSS properties:

### Example Code 

```css
text-align: left;
display: block;
width: 100%;
margin-top: 20px;
padding-top: 5px;
```


## Step 59 | Specifies `p` elements
Make the **paragraph elements** appear as a **higher priority**, with the following CSS properties:

<details>
<summary> Snippet </summary>

### Example Code

```css
margin-top: 5px;
padding-left: 15px;
font-size: 20px;
```
</details>

## Step 60
It is useful to see the default border around the fieldset elements, during development. However, it might not be the style you want.

Remove the border and bottom padding on the .question elements.









