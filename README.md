# CSS calc() Calculation Errors with Mixed Units

This repository demonstrates an uncommon bug related to the CSS `calc()` function.  When using `calc()` with a mix of percentages and fixed units (like pixels or ems), unexpected calculation results can occur. The browser may fail to compute the correct width or height, leading to layout problems.

The `bug.css` file shows the problematic code.  `bugSolution.css` offers a potential solution, though the best approach may depend on the specific context.  It's often better to avoid complex `calc()` expressions to prevent such issues.

This is an example of a relatively subtle CSS bug that can be difficult to track down.  Thorough testing and careful consideration of unit usage within `calc()` are crucial.