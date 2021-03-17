# Day 2 - HTML / CSS

## Daily Journal

Today was focused on CSS fundamentals.  We began the course with the Bento CSS challenge from Udemy before beginning a breakdown of basic HTML body tags.  Using this lesson as a base, we mocked up a resume using CSS Flexbox to modify the layout appropriately until Lunch.  After lunch, we focused on our Daily Challenge, which was similar in concept to the Resume mockup, but without immediate direction from the instructor.  After a few hours of design, I was able to make an approximate mockup of the template image.  Once concluded, I began another Udemy course on Bootstrap, which is clearly superior to raw CSS in every conceivable way!

### Read Building Blocks Of Web Development > *CSS*

1. What is a Pseudo-Class and what are some of the most common ones you think you will use
        A special class that is used to modify a special state of an element, like "hover" or "focus."  I personally have used "hover" quite heavily to modify buttons and cards when the cursor hovers over them.

2. What is Specificity and how might you use it to your benefit?
        Specificity defines which CSS property values are the most important.  Values with higher specificity will be prioritized over values with lower specificity, which can be useful to override base CSS values, in the <body> for example, with later elements that need to be styled differently.  Specificity allows those <body> styles to persist even if other styles are in conflict with it.

3. What problems do you think you could run into if you over-utilized the !important feature?
        !important raises the specificity of a value above all regular specificity values, which can cause conflict if your !important values overlap with base styles whose styles should not be altered.