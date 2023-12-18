# Learn Accessibility by Building a Quiz

Accessibility is making your webpage easy for all people to use – even people with disabilities.

In this course, you'll build a quiz webpage. You'll learn accessibility tools such as keyboard shortcuts, ARIA attributes, and design best practices.

Project with 68 steps

# Accessibility
1. Lang="en" in <html>
2. Charset in <meta charset="UTF-8">
3. a viewport definition tells the browser how to render the page. Including one betters visual accessibility on mobile, and improves SEO (search engine optimization). in <meta name="viewport" content="width=device-width, initial-scale=1.0">
4. Another important meta element for accessibility and SEO is the description definition. The value of the content attribute is used by search engines to provide a description of your page. in <meta name="description" content="Lear html accessibility quiz">
5. Given title: <title>Accessibility: Building a Quiz</title>
6. Given The <header> element (be used to introduce the page, as well as provide a navigation menu:  <img>, <h1>, and <nav> element) and the <main> element (that will contain the core content of your page).
7. Create a <section> in <form> to semantically separate the content.
8. Add attribute role: To increase the page accessibility, the role attribute can be used to indicate the purpose behind an element on the page to assistive technologies. The role attribute is a part of the Web Accessibility Initiative (WAI), and accepts preset values.
9. Every region role requires a label, which helps screen reader users understand the purpose of the region. One method for adding a label is to add a heading element inside the region and then reference it with the aria-labelledby attribute.h2 element with an id matching the corresponding aria-labelledby
10. **Typeface** plays an important role in the accessibility of a page. Some fonts are easier to read than others, and this is especially true on low-resolution screens. *Verdana*, and *sans-serif* family.
11. **Navigation within the page**, give each anchor element an href corresponding to the id of some elements.