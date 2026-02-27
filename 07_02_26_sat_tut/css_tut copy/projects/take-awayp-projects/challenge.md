

* Multimedia (video, audio, iframe)
* Advanced form features
* More complex tables
* Responsive design basics
* Stronger CSS specificity requirements
* Cleaner layout expectations
* Accessibility requirements

This is appropriate as a **final exam project**.

---

# Final Exam Project: Advanced Multi-Page Business Website

## Assignment Title:

**“Professional Company Website – Full Web Development Project”**

---

# Required Folder Structure

```
company-website/
│
├── index.html
├── services.html
├── gallery.html
├── schedule.html
├── contact.html
├── media/
│   ├── images/
│   ├── video/
│   └── audio/
└── styles.css
```

All pages must link correctly using relative paths.

---

# Global Requirements (All Pages)

Each page must include:

* `<!DOCTYPE html>`
* `<html lang="en">`
* `<head>` with:

  * meta charset
  * viewport
  * unique title
  * linked external CSS
* `<body>`
* `<header>`
* `<nav>`
* `<main>`
* `<footer>`

Navigation must:

* Appear on every page
* Highlight the active page
* Contain at least 5 internal links
* Contain 1 external link (`target="_blank"`)

---

# Page 1: Home (index.html)

Must include:

* Hero section with heading and intro text
* At least 4 paragraphs
* One featured image with `alt`
* One embedded video using `<video>`
* One `<aside>` section
* One `div` container
* One `span` used for emphasis
* One element with an id
* Two different classes
* One element with two classes
* At least one HTML comment

Video must include:

* controls attribute
* fallback text

---

# Page 2: Services (services.html)

Must include:

* At least 3 service sections
* Unordered list
* Ordered list
* Description paragraphs
* A pricing comparison table (minimum 4 rows, 3 columns)

Table must include:

* `<caption>`
* `<thead>`
* `<tbody>`
* `<tfoot>`

---

# Page 3: Gallery (gallery.html)

Must include:

* Minimum 6 images
* Proper alt text
* Organized using div containers
* One embedded YouTube video using `<iframe>`
* One audio file using `<audio>` with controls

Images must be styled consistently using classes.

---

# Page 4: Schedule (schedule.html)

Must include:

* Advanced table with:

  * `rowspan`
  * `colspan`
* At least 5 rows
* Proper headings
* Clear structure

---

# Page 5: Contact (contact.html)

Must include a fully structured form.

Required form elements:

* Text input
* Email input
* Phone input
* Password input
* Date input
* Number input
* Radio buttons
* Checkboxes
* Dropdown menu
* Textarea
* File upload input
* Submit button
* Reset button

Required attributes:

* `required`
* `placeholder`
* `min` / `max` (for number input)
* `pattern` (for validation)
* Proper `<label for="">` connections

---

# CSS Requirements (styles.css)

Your stylesheet must include:

1. Universal selector
2. Element selector
3. Class selector
4. ID selector
5. Grouping selector
6. Descendant selector
7. Child selector (`>`)
8. Attribute selector
9. Pseudo-class (`:hover`)
10. Pseudo-class (`:focus`)
11. At least one `nth-child()` selector

---

# Layout & Design Requirements

Your website must demonstrate:

* Consistent layout across pages
* Styled navigation bar
* Responsive design using:

  * At least one media query
* Centered content container
* Styled buttons
* Styled tables
* Styled form container
* Hover effects
* Focus styles for accessibility
* Background color or gradient
* Box model usage (margin, padding, border)

---

# CSS Application Rules

External CSS
All main styling must be in styles.css.

Internal CSS
On ONE page only, modify one heading using `<style>`.

Inline CSS
Used ONCE only in entire project.

---

# Cascading & Specificity Requirement

You must demonstrate:

* An element styled with a class
* The same element overridden using an id
* Another example overridden with inline style

Must clearly show:

Inline > Internal > External
ID > Class > Element

---

# Accessibility Requirements

* All images must have meaningful alt text
* Form inputs must have associated labels
* Sufficient color contrast
* Use semantic HTML correctly

---

# Comments Requirement

* Minimum 8 CSS comments
* Minimum 5 HTML comments across pages

---

# Technical Accuracy Requirements

* No broken links
* No missing files
* No CSS syntax errors
* Proper indentation
* Clean readable code
* Proper nesting

---

# Grading Rubric (100 Points)

| Requirement                       | Points  |
| --------------------------------- | ------- |
| Multi-page structure & navigation | 10      |
| Semantic HTML & structure         | 10      |
| Multimedia implementation         | 10      |
| Tables (basic + advanced)         | 10      |
| Form completeness & validation    | 15      |
| CSS selectors variety             | 10      |
| Responsive design                 | 10      |
| Cascading & specificity           | 5       |
| Design & visual consistency       | 10      |
| Accessibility                     | 5       |
| Comments & clean code             | 5       |
| **Total**                         | **100** |

---

This version tests:

* Complete HTML knowledge
* Advanced tables
* Full form mastery
* Multimedia embedding
* CSS specificity understanding
* Responsive design basics
* Real-world project organization

