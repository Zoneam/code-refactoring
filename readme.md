# Code Refactoring

---

---

    Refactoring existing code, improving it without changing what it does.

## Web accessibility

    We have to fix web accessibility to ensure that people
    with disabilities can access a website using assistive
    technologies like video captions, screen readers, and
    braille keyboards.

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

**_ My improvements _**

### Head

        * Added website meaningful title
        * Switched title and stylesheet

### Body

#### Header

     [x] Changed header class to header tag
     [x] Changed seo class to seoSpan to make more meaningful
     [x] Changed div to nav which is semantic element for navigation bar
     [x] Added class navItems to nav bar items to make it shorter in css and give it a meaning
     [x] Added flexbox for header to make it more responsive
     [x] Changed ul for nav bar to flex so I can arange them as shown in example

#### Hero Image

     [x] Removed div for hero image and added figcaption tag so we can have alt text,
     removed hero class from css

#### Content

     [x] Changed content class to content element
     [x] Added alt text for content images
     [x] Changed content divs to section elements, removed classes and ids because they share same parameters

#### Side Panel

     [x] Changed div class benefits to aside element
     [x] Removed benefit-lead, benefit-brand benefit-cost classes added sideContent class since they
     share same parameters
     [x] Made sidebar color little darker so text is more accessibility campartable

#### Footer

     [x] Changed footer class to footer element
     [x] Added media query to make website more responsive
     [x] Rearanged CSS content to follow a logical structure

---

![Refactored website capture](./Website_Refactoring.png)
