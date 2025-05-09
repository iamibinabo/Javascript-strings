
# Slide 1: Introduction to Strings

JavaScript Strings

A string is a sequence of characters used to represent text.

```javascript
let greeting = "Hello, world!";
```

Strings are primitive data types in JavaScript.  
They can be defined using:

- "double quotes"  
- 'single quotes'  
- `backticks` (template literals)

---

# Slide 2: Creating Strings

Creating Strings

```javascript
let single = 'Hello';
let double = "World";
let backtick = `Hey there!`;
```

Use backticks for template literals.  
Mixing quotes inside each other:

```javascript
let mix = "It's a nice day";
```

---

# Slide 3: Escape Characters

Escape Characters

Use backslashes (\) for special characters inside strings.

```javascript
let quote = "He said, \"Hello!\"";
let newline = "First line\nSecond line";
```

- \n – new line  
- \t – tab  
- \\ – backslash

---

# Slide 4: Common String Methods

Useful String Methods

```javascript
let text = "  JavaScript is fun!  ";
```

| Method                   | Description                |
| ------------------------ | -------------------------- |
| `text.length`            | Total characters           |
| `text.trim()`            | Removes whitespace         |
| `text.toLowerCase()`     | Converts to lowercase      |
| `text.toUpperCase()`     | Converts to uppercase      |
| `text.includes("fun")`   | Checks if "fun" exists     |
| `text.indexOf("Script")` | Finds position of "Script" |

---

# Slide 5: More String Methods

More String Methods

```javascript
let str = "JavaScript";
```

| Method                        | Example                     | Result                   |
| ----------------------------- | --------------------------- | ------------------------ |
| `str.slice(0, 4)`             | Returns "Java"              | "Java"                   |
| `str.substring(4)`            | From position 4 onward      | "Script"                 |
| `str.replace("Java", "Type")` | Replaces "Java" with "Type" | "TypeScript"             |
| `str.repeat(2)`               | Repeats the string twice    | "JavaScriptJavaScript"   |

---

# Slide 6: Template Literals

Template Literals

Template literals (`) allow:

- Variable interpolation  
- Multi-line strings

```javascript
let name = "Sam";
let mood = "excited";
let message = `Hi ${name}, you're looking ${mood} today!`;
```

Cleaner and more readable than string concatenation.

---

# Slide 7: String Immutability

String Immutability

Strings in JavaScript are immutable

```javascript
let word = "hello";
word[0] = "H";  // This won't work
```

To "change" a string, create a new one:

```javascript
word = "H" + word.slice(1);  // "Hello"
```

---

# Slide 8: String Conversion

String Conversion

Convert other data types to strings using:

```javascript
String(123);      // "123"
(456).toString(); // "456"
```

Useful for:

- Concatenating numbers with strings  
- Preparing data for display
