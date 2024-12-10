# Responsive Issues with Tailwind's Fractional Widths in Flexbox

This repository demonstrates a common issue encountered when using Tailwind CSS's fractional width classes (like `w-1/2`) within a flexbox container. The problem arises when trying to achieve a responsive layout where one element takes a fixed fraction of the width, while the other adapts to the remaining space.

The `bug.html` file showcases the problem: the second div does not resize responsively as expected. The `solution.html` file demonstrates the solution using a different approach to achieve the desired responsive behavior.  The key is to use `flex-1` to allow the second div to expand and fill the remaining space.