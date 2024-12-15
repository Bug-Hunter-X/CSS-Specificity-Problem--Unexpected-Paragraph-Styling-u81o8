# CSS Specificity Bug

This repository demonstrates a common issue in CSS: unintended styling due to a lack of specificity in selectors. The `bug.css` file contains the buggy code, while `bugSolution.css` provides the corrected version.

**Problem:**
The original CSS styles all paragraphs (`<p>`) on the page, even those outside the intended `div.container`, resulting in unexpected styling.

**Solution:**
The solution involves increasing the specificity of the selector to target only paragraphs within the `div.container`. This is achieved by using a more specific selector, ensuring that only the intended paragraphs are styled.