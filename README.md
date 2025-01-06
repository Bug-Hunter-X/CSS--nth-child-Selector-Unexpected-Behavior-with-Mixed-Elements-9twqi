# CSS :nth-child Selector Issue
This repository demonstrates a subtle bug related to the CSS `:nth-child` selector when used with lists containing mixed element types.
The `bug.css` file shows the incorrect implementation, while `bugSolution.css` provides a corrected approach.
The problem arises when attempting to style every other list item within a list containing not only list items but also other HTML elements. The `:nth-child` selector counts all elements, leading to unexpected visual results.
The solution uses a more robust approach to target only list items or uses a different selector for a more consistent result.