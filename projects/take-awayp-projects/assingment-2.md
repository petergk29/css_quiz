

#  Take-Home Assignment: Create a Styled Recipe Page

##  Assignment Title:

**“My Favorite Recipe – Styled With CSS”**

---

##  Instructions for Students

Create a recipe webpage and style it using everything we learned about CSS.

You must use:

*  External CSS
*  Internal CSS
*  Inline CSS (only once)
*  At least 3 different selectors
*  CSS comments
*  Proper CSS syntax (no errors)

---

#  Project Structure

```
recipe-page/
│
├── index.html
└── styles.css
```

---

#  Part 1: HTML Requirements (index.html)

Your page must include:

1. A main heading (`h1`) – Recipe Name
2. A subheading (`h2`) – “Ingredients”
3. A subheading (`h2`) – “Instructions”
4. An unordered list (`ul`) with at least 4 ingredients
5. An ordered list (`ol`) with at least 4 steps
6. One `div` container that wraps part of the content
7. At least:

   * One element with an **id**
   * One element with a **class**
   * One element with **two classes**
8. A proper link to your external CSS file inside `<head>`

---

#  Part 2: CSS Requirements (styles.css)

Your stylesheet must include:

### 1️⃣ Universal Selector

Add a small margin or padding to all elements.

### 2️⃣ Element Selector

Style all `p` OR all `li` elements.

### 3️⃣ ID Selector

Style one unique section differently.

### 4️⃣ Class Selector

Style multiple elements using the same class.

### 5️⃣ Grouping Selector

Style `h1, h2` together.

---

#  Part 3: CSS Application Rules

You must demonstrate all three ways of adding CSS:

###  External CSS

Most of your styling must be inside `styles.css`.

###  Internal CSS

Inside `<style>` in the `<head>`:

* Change the color of ONE heading only.

###  Inline CSS

Use inline styling on ONE element only (for example, one paragraph or one list item).

 Only ONE inline style allowed.

---

#  Part 4: Comments

You must include:

* At least **3 CSS comments**
* At least **1 HTML comment**

Example:

```css
/* This styles the ingredients section */
```

---

#  Part 5: Cascading & Specificity Demonstration

You must show cascading order by:

* Styling a paragraph using a class
* Then overriding it using an id or inline style

This proves you understand:

* Inline > Internal > External
* ID > Class > Element

---

#  Common Errors to Avoid

Make sure you:

* End every declaration with a semicolon ;
* Close all curly braces { }
* Do NOT write property names incorrectly
* Do NOT write values like `15 px`
* Use proper indentation

---

#  Bonus (Optional – Extra Credit)

Choose any 2:

* Add a hover effect to a button or link
* Add a background color or background image
* Create a styled card using padding + border + border-radius
* Center content using CSS

---

#  Grading Rubric (100 Points)

| Requirement                       | Points  |
| --------------------------------- | ------- |
| Correct HTML Structure            | 10      |
| External CSS Implemented Properly | 15      |
| Selectors Used Correctly          | 20      |
| Internal + Inline CSS Included    | 15      |
| Cascading Demonstrated Correctly  | 15      |
| Comments Included                 | 10      |
| No Syntax Errors                  | 10      |
| Clean Formatting & Organization   | 5       |
| **Total**                         | **100** |

---

# Submission Instructions

* Submit `index.html` and `styles.css`
* Open in browser and test before submitting
* Make sure all styles are working properly
* Double-check for syntax errors
* push to git

---

