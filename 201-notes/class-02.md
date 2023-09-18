# Class 02 - Basics of HTML, CSS & JS

## HTML

Q: Why is it important to use semantic elements in our HTML?

A: Semantic elements are important because they help people who use screen readers to navigate a web page by providing landmarks. Elements such as the _h1_ tag are also used by search engines to determine what a web page is about.

Q: How many levels of headings are there in HTML?

A: There are six levels of heading tag with _h1_ being the most important and _h6 _ being the least.

Q: What are some uses for the _sup_ and _sub_ elements?

A: _sup_ and _sub_ format text higher or lower on a line than regular text respectively and are used to properly format things such as dates or chemical formulae.

Q: When using the _abbr_ element, what attribute must be added to provide the full expansion of the term?

A: The title attribute is used to provide the full expansion of the term. For example:

        <abbr title="HyperText Markup Language">HTML</abbr>

## CSS

Q: What are ways we can apply CSS to our HTML?

A: Three common ways of applying CSS to an HTML document are:

- An external stylesheet
- Inline CSS using the style attribute
- Using the style tag within the _head_ of the document

Q: Why should we avoid using inline styles?

A: They detract from the readability of code and are a less economic use of CSS due to the fact that they can only apply style rules to one particular element at a time.

Review the block of code below and answer the following questions:

        h2 {
          color: black;
          padding: 5px;
          }

Q: What is representing the selector?

A: 'h2'

Q: Which components are the CSS declarations?

A: 'color: black' and 'padding: 5px'

Q: Which components are considered properties?

A: 'color' and 'padding'

## JS

Q: What data type is a sequence of text enclosed in single quote marks?

A: A string

Q: List 4 types of JavaScript operators.

A: Assignment operators, comparison operators, arithmetic operators, string operators

Q: Describe a real world problem you could solve with a function.

A: A real world problem that could be solved with a JS function is having to work out how much money to give as a tip:

        function tipCalculator(amount){
          return amount \* 0.2;
        }

### Making Decisions In Your Code – Conditionals.

Q: An if statement checks a \_\_ and if it evaluates to \_\_, then the code block will execute.

A: An if statement check a _condition_ and if it evaluates to _true_ then the code will execute.

Q: What is the use of an else if?

A: An _else if_ statement is used to test more than one condition and only execute the code with the curly braces after conditions that equal true.

Q: List 3 different types of comparison operators.

A: _==_ (equal to), _>_ (greater than), _!=_ (not equal to)

Q: What is the difference between the logical operator && and ||?

A: _&&_ (AND) means all specified comparisons must be true for a condition to return _true_ whereas with _||_ (OR) any of the specified comparisons can be true for a condition to return _true_.
