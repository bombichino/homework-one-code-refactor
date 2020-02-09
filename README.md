# HTML CSS GIT Code Refactor and Accessibility Tags

We were tasked with refactoring the HTML and CSS of the existing Horiseon SEO website to fall within acceptable accessibility guidelines.

## Chief Execution

In order to achieve this:

- I replaced the non-semantic HTML tags with semantic HTML tags, as well as the use of an aria tag for e-reader functionality when dealing with emoji.
- I attached alt text to all images.
- I reorganized the HTML in the index.html file to be more easily readible and fall within guidelines.
- I added a descriptive title to the page.
- I "cleaned up" the css stylesheet for readability, grouping like elements. Many elements were created as individual classes, so I grouped like elements into single classes to dispense similar style information, as well as transferred some classes to individual ID tags when individual elements required tweaking.
- I ensured that the background color and text color differentiation and contrast met accessibility standards.

To ensure accessibility standards were met, I ran an accessibility audit using Google's developer tools. NB - I noticed they must be run with the website taking the full width of the browswer - when collapsed, some elements did not pass the audit as they were transformed - the text over background contrast being the issue. This could later be resolved by making the website responsive to size/mobile view.

## Links to live work:

The link to the live site is: https://bombichino.github.io/homework-one-code-refactor/

The link to the GitHub repository is: https://github.com/bombichino/homework-one-code-refactor