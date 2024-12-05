# Writing a Function in JavaScript

![who is jamess harrison](/assets/james-harrison-unsplash.jpg)

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1. Basic syntax
```javascript
const functionName = (params) => {
  // code to be executed
}
```
1. __const__: const should be used whenever a function expression is assigned to a variable.
2. __The function name__: The name you choose for the function.
3. __Parameters__: Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
4. __The arrow syntax__: Indicates that this will be a function.
5. __The body__: The statements that make up the function itself. Surrounded by curly braces.

***Example***:

```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```

>Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 

## 2. Calling a function

To execute the function, you *call* or *invoke* it by using its name followed by parentheses.

***Example***:

```javascript
greet('Alice'); // Outputs: Hello, Alice!
```

## 3. Return values

Functions can process data input and output a value using the *return* keyword.

***Example***: 

```javascript
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
```

For more information on functions and how they are used in JS, check out the MDN docs.
[click me](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

### Using External Url
![Computer with Code](https://plus.unsplash.com/premium_photo-1661963874418-df1110ee39c1?q=80&w=786&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

## Using same directory as the Markdown
![Computer with Code2](/assets/code2.avif)

<!--
1. USING HEADER - just add # <TEXT_YOU_WANT TO CAPITALIZE>

# h1
## h2
### h3
#### h4
##### h5
###### h6

2. USING TEXT STYLES Bold, Italics, or Both

• Embolden text by wrapping it in with two ** or __

• Italicize text by wrapping it with * or _

• Combine italic and bold by adding a third * or _

3. TO CREATE A BULLETED LIST, you can use asterisks (*), plus (+), or minus (-) followed by a space. These symbols act as bullet points

* Item 1
* Item 2
  * Subitem 2.1
  * Subitem 2.2
    * Subitem 2.2.1

This will render as:

• Item 1
• Item 2
    • Subitem 2.1
    • Subitem 2.2
       • Subitem 2.2.1

3.1 For numbered lists, use numbers followed by a period and a space:

1. First item
2. Second item
   1. Subitem 2.1
   2. Subitem 2.2
This will produce:

1. First item
2. Second item
    i.Subitem 2.1
    ii.Subitem 2.2

💡 Markdown handles the numbering automatically, so you can use 1. for every item, and the numbers will still increment correctly. Try it.

4. CODE SNIPPETS are invaluable in technical documentation, allowing readers to view, understand, and copy code directly from the Markdown.

For short, inline code references, wrap the word or code with backticks (`).

To present multi-line code snippets or blocks, use three backticks ` consecutively as an opening and closing syntax. To enhance readability, you can also specify the programming language right after the first three backticks, enabling markdown syntax highlighting.

```javascript
const printItem = (item) => {
  console.log(item);
}
```

5. ADDING LINKS
You can create an inline link by wrapping the link text in brackets [My URL], followed by the URL in parentheses (www.myurl.com)
[Google](https://www.google.com)

This is [a reference][example]

[example]: http://www.example.com/

Produces this formatting:

This is a reference. -------&> reference is now a link

6. BLOCKQUOTES 
are handy for highlighting important asides in text, often representing citations, referenced content, or emphasizing statements in your Markdown documents.

To create a blockquote, start the line with the > character followed by a space.

This syntax:


> This is a blockquote.


You can also nest blockquotes by using additional > characters.

This syntax:


> First level of blockquote.
    >> Nested blockquote.
        >>> Another nested blockquote.

Blockquotes can contain other Markdown formatted elements, like headers, lists, or even other blockquotes. Try it out.


7. Adding images
Using images can elevate your documentation, tutorials, and project write-ups. Embedding images is straightforward in Markdown (and the best way to include screenshots in a project).
The syntax to embed an image is like creating a hyperlink in Markdown, but it’s prefixed with an exclamation mark !.

This syntax:
![some alt text](www.url_to_an_image.com/image)

-->
