# HTML Screening Questions

**1. What is HTML?** 

A: HTML stands for Hyper Text Markup Language. It is a language of World Wide Web. It is a standard text formatting language which is used to create and display pages on the Web

**2. Do all HTML tags have end tag?**

A: No. There are some HTML tags that don't need a closing tag. Eg: <image> tag, <input> tag, <br> tag etc...

**3. What is semantic HTML?**

A: Semantic HTML is a coding style. It is the use of HTML markup to reinforce the semantics or meaning of the content. For example: In semantic HTML <b> </b> tag is not used for bold statement as well as <i> </i> tag is used for italic. Instead of these we use <strong></strong> and <em></em> tags.

**4. What is the use of span tag? Give one example.**

A: The span tag is used for following things:
	a) For adding color on text
	b) Adding background on text
	c) Highlight any color text etc.
	d) To display specific text in different view by applying CSS to span

**5. Which video formats are supported by HTML5?**

A: HTML 5 supports three types of video format:
	a) mp4
	b) webm
	c) ogg

**6. What are the new <input> types for form validation in HTML5?**

A: The new input types for form validation are email, url, number, tel and date.

**7. What are all the web storage API's available in HTML5.**

A: Local Storage and Session Storage.

**8. What is the default display CSS property of a span tag ?**

A: Inline.

**9. How do we identify the webpage is HTML5 ?**

A: By seeing at the DOCTYPE html Declaration at the top of the html page.

**10. What are all the non-sementic tags available in HTML5 ?**

A: div, p, span

## CSS Screening Questions

**1. How can you integrate CSS on a web page? / Different types of methods to integrate CSS ?**

A: There are three methods to integrate CSS on web pages:

	a) Inline method
	b) Embedded/Internal method
	c) Linked/Imported/External method

**2. What is the difference between class selectors and id selectors?**

A: An overall block is given to class selector while id selectors take only a single element differing from other elements.

**3. What is the difference between inline, embedded and external style sheets?**

A: Below are the differences:

	a) Inline: Inline Style Sheet is used to style only a small piece of code.
	b) Embedded: Embedded style sheets are put between the <head>...</head> tags.
	c) External: This is used to apply the style to all the pages within your website by changing just one style sheet.

**4. What is the CSS Box model and what are its elements?**

A: The CSS box model is used to define the design and layout of elements of CSS.

The elements are:
	
	a) Margin
	b) Border
	c) Padding
	d) Content

**5. What is the purpose of the z-index and how is it used?**

A: Below are the usage and the purpose of z-index: 

	a) The z-index helps specify the stack order of positioned elements that may overlap one another. 

	b) The z-index default value is zero, and can take on either a positive or negative number. 
	
	c) An element with a higher z-index is always stacked above than a lower index. 
	
	Z-Index can take the following values:

	a) Auto: Sets the stack order equal to its parents.
	b) Number: Orders the stack order.
	c) Initial: Sets this property to its default value (0).
	d) Inherit: Inherits this property from its parent element.

**6. Explain the difference between visibility: hidden and display: none?**

A: Differences are below:

	-- visibility: hidden simply hides the element but it will occupy space and affect the layout of the document.
	-- display: none also hides the element but will not occupy space. It will not affect the layout of the document.

**7. What is the hierarchy sides of padding/margin getting the values applied to a box model ?**

A: The order of padding/margin values applied from Top - right - bottom - left

**8. What is the default CSS property of Position ?**

A: Static

**9. What is the default CSS property of a span tag ?**

A: Inline

**10. What is keyframes in CSS 3 ?**

A: To create animations we use keyframes.

## SCSS Screening Questions

**1. What is mixins and how we make use of mixins ?**

A:  In object-oriented programming languages, a Mixin is a class that contains methods for use by other classes without having to be the parent class of those other classes. Mixins encourage code reuse and can be used to avoid the inheritance ambiguity that multiple inheritance can cause (the "diamond problem"), or to work around lack of support for multiple inheritance in a language. A mixin can also be viewed as an interface with implemented methods.

**2. Explain how to define a variable in Sass?**

A: Variables in Sass begin with a ($) sign and variable assignment is done with a colon(:).

**3. What are all the Key features for SASS/SCSS ?**

	a) Full CSS3-compatible
	b) Language extensions such as nesting, variables, and mixins
	c) Many useful functions for manipulating colors and other values
	d) Advanced features like control directives for libraries
	e) Well-formatted, customizable output

**4. Explain what is the difference between Sass and SCSS?**

A: The difference between Sass and SCSS are below: 

	a) Sass is a CSS pre-processor with syntax advancements and an extension of CSS3
	b) Sass has two syntax
	c) The first syntax is “SCSS” and it uses the .scss extension
	d) The other syntax is indented syntax or just “Sass” and it uses the .sass extension
	e) While Sass has loose syntax with white space and no semicolons, the SCSS resembles more to CSS
	f) Any CSS valid document can be converted to Sass by simply changing the extension from.CSS to.SCSS.

**5. Explain what is the use of the @IMPORT function in Sass?**

A: The @IMPORT function in Sass:

	a) Extends the CSS import rule by enabling import of SCSS and Sass files
	b) All imported files are merged into a single outputted CSS file
	c) Can virtually mix and match any file and be certain of all your styles
	d) @IMPORT takes a filename to import

**6. What is @include directive?**

A: It is used to include the mixin in the document and styles defined by the mixin can be included into the current rule.


### JavaScript Basic Questions

**1. What is JavaScript?**

A: JavaScript is a scripting language. It is different from Java language. It is object-based, lightweight and cross platform. It is widely used for client side validation.

**2. What is a “closure” in JavaScript? Provide an example**

A: A closure is a function defined inside another function (called the parent function), and has access to variables that are declared and defined in the parent function scope. The closure has access to variables in three scopes:

	a) Variables declared in their own scope
	b) Variables declared in a parent function scope
	c) Variables declared in the global namespace

**3. What is the difference between JavaScript and jscript?**

A: Netscape provided the JavaScript language. Microsoft changed the name and called it JScript to avoid the trademark issue.In other words, you can say JScript is same as JavaScript, but it is provided by Microsoft.

**4. What is the difference between == and ===?**

A: The == operator checks equality only whereas === checks equality and data type i.e. value must be of same type.

**5. How to create objects in JavaScript?**

A: There are 3 ways to create object in JavaScript:

	a) By object literal
	b) By creating instance of Object
	c) By Object Constructor
	d) Let's see a simple code to create object using object literal.

**6. Difference between Client side JavaScript and Server side JavaScript?**

A:  Client side JavaScript comprises the basic language and predefined objects which are relevant to running java script in a browser. 
The client side JavaScript is embedded directly by in the HTML pages. This script is interpreted by the browser at run time. 

Server side JavaScript also resembles like client side java script. It has relevant java script which is to run in a server. The server side JavaScript are deployed only after compilation.

**7. Are Java and JavaScript same?**

A: No, Java and JavaScript are the two different languages. Java is a robust, secured and object-oriented programming language whereas JavaScript is a client side scripting language with some limitations.

#### Angular Screening Questions

**1. What is a template reference variable, and how would you use it?**

A: A variable (defined using a #) in a component template, which can be referenced in other parts of the template. For example, a template variable for a form can then be referenced by other elements of the form.

**2. What is ng-template?**

A: It's an Angular element for rendering HTML when using structural directives. The ng-template itself does not render to anything but a commment directly.

**3. What are different kinds of directives supported in Angular 2?**

A: Structural, component, and attribute directives.

**4. What is the difference between a component and a template?**

A: A component is a directive with a template (representing a view).

**5. What is the purpose of exports in an NgModule?**

A: Provide components, directives, pipes to other modules for their usage.

**6. Can we import a module twice?**

A: Yes, and the latest import will be what is used.

**7. When will ngOnInit be called?**

A: Called once, after the first ngOnChanges.

**8. What is the difference between onNgInit() and constructor() of a component?**

A: A directive’s data-bound input properties are not set until after construction, so that’s one difference.

