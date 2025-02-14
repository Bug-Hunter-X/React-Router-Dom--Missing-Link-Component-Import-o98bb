# React Router Dom: Missing Link Component Import

This repository demonstrates a common error in React Router Dom: forgetting to import the `Link` component.  The `Link` component is essential for navigating between routes within your application.  Without it, attempting to use `<Link>` will result in a runtime error or unexpected behavior.

## Bug
The `bug.js` file contains the buggy code.  Notice that the `Link` component is used without being imported.  This results in a runtime error.

## Solution
The `bugSolution.js` file provides the corrected code.  The `Link` component is correctly imported from `react-router-dom`, allowing for proper navigation.