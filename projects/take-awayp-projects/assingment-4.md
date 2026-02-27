

 **multi-page final project** that includes:

* Multiple HTML pages
* Navigation between pages
* Forms
* Tables
* Full semantic structure
* Shared external CSS
* Cascading and specificity

---

#  Project: Multi-Page Business Website

## Assignment Title:

**“Launch a Small Business Website”**

Students will build a 4-page website for a fictional business.

---

# Required Project Structure

```
business-website/
│
├── index.html
├── services.html
├── schedule.html
├── contact.html
└── styles.css
```

All pages must connect properly using relative links.

---

# General Requirements (All Pages)

Each page must include:

* `<!DOCTYPE html>`
* `<html lang="en">`
* `<head>` with:

  * meta charset
  * viewport
  * title (unique per page)
  * link to external stylesheet
* `<body>`
* `<header>`
* `<nav>`
* `<main>`
* `<footer>`

Navigation must:

* Appear on every page
* Link to all 4 pages
* Use relative file paths
* Include at least one external link with `target="_blank"`

---

# Page 1: Home (index.html)

Must include:

* Main heading (business name)
* Hero section (intro paragraph)
* At least 3 paragraphs
* One image with `alt`
* One `div`
* One `span`
* One element with an id
* One element with a class
* One element with two classes
* At least 1 HTML comment

---

# Page 2: Services (services.html)

Must include:

* At least 2 `h2` headings
* One unordered list
* One ordered list
* One article section
* Clear content structure
* At least 1 HTML comment

---

# Page 3: Schedule or Pricing (schedule.html)

Must include a properly structured table:

Required tags:

* `<table>`
* `<caption>`
* `<thead>`
* `<tbody>`
* `<tr>`
* `<th>`
* `<td>`

Table must have:

* Minimum 3 rows
* Minimum 3 columns
* Clear headings

---

# Page 4: Contact (contact.html)

Must include a complete form with:

Form attributes:

* `action`
* `method`

Form elements:

* Text input
* Email input
* Phone OR number input
* Radio buttons
* Checkboxes
* Dropdown (`select`)
* Textarea
* Submit button
* Reset button
* Labels properly connected using `for`
* At least 2 required fields

---

# CSS Requirements (styles.css)

All pages must share the same external stylesheet.

Your CSS must include:

1. Universal selector
2. Element selector
3. ID selector
4. Class selector
5. Grouping selector
6. Descendant selector
7. Attribute selector (example: `input[type="email"]`)
8. Pseudo-class (`:hover`)

---

# CSS Application Rules

You must demonstrate:

External CSS
Most styles must be in styles.css.

Internal CSS
On ONE page only, use a `<style>` tag to modify one heading.

Inline CSS
Use inline styling on ONE element only in the entire project.

---

# Cascading & Specificity Demonstration

You must:

* Style an element using a class in external CSS
* Override it using an id or inline style

This must clearly show:

Inline > Internal > External
ID > Class > Element

---

# Design Requirements

Your website must include:

* Background color
* Styled navigation bar
* Styled buttons
* Styled table (borders + spacing)
* Styled form container
* Hover effects on navigation or buttons
* Consistent layout across pages

---

# Comments Requirement

* At least 6 CSS comments
* At least 3 HTML comments (across pages)

---

# Common Mistakes to Avoid

* Broken links between pages
* Incorrect relative paths
* Missing closing tags
* Missing semicolons
* Not linking CSS on all pages
* Not connecting labels to inputs

---

# Grading Rubric (100 Points)

| Requirement                    | Points  |
| ------------------------------ | ------- |
| Multi-page structure & linking | 15      |
| Semantic HTML structure        | 15      |
| Table implementation           | 10      |
| Form implementation            | 15      |
| External CSS usage             | 15      |
| Required selectors             | 10      |
| Internal + Inline CSS          | 5       |
| Cascading demonstration        | 5       |
| Design & consistency           | 5       |
| Comments & clean code          | 5       |
| **Total**                      | **100** |

---

This version:

* Tests deeper understanding
* Feels like a real-world project
* Assesses organization skills
* Encourages planning

