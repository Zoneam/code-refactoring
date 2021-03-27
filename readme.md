# Code Refactoring

---

    Refactoring existing code improving it without changing what it does.

## Web accessibility

    We have to fix web accessibility to ensure that people with disabilities can access a website using assistive technologies like video captions, screen readers, and braille keyboards.

---

### We have to make sure that

    GIVEN a webpage meets accessibility standards
    WHEN I view the source code
    THEN I find semantic HTML elements
    WHEN I view the structure of the HTML elements
    THEN I find that the elements follow a logical structure independent of styling and positioning
    WHEN I view the image elements
    THEN I find accessible alt attributes
    WHEN I view the heading attributes
    THEN they fall in sequential order
    WHEN I view the title element
    THEN I find a concise, descriptive title

---

## My improvments explained

### Head

        * Added website meaningful title
        * Switched title and stylesheet

---

### Body

#### Header

     Changed header class to header tag
     Changed seo class to seoSpan to make more meaningful
     Changed div to nav which is semantic element for navigation bar
     Added class navItems to nav bar items to make it shorter in css and give it a meaning

