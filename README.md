# Next.js 15 - Missing Return Statement Bug

This repository demonstrates a common error in Next.js 15 applications: a missing `return` statement in a page component.  This leads to a runtime error.

## Bug

The `pages/about.js` file is missing a `return` statement in its functional component. This will cause Next.js to throw an error when the `/about` route is accessed.

## Solution

The solution involves adding a `return` statement to the `About` component to return the JSX to be rendered.

## How to reproduce

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to `/about` in your browser. You will see the error.
5. Refer to `aboutSolution.js` for the solution.