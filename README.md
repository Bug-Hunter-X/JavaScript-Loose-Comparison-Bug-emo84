# JavaScript Loose Comparison Bug

This repository demonstrates a common error in JavaScript related to loose comparison (==) and type coercion.  Loose comparison doesn't check for type equality before comparison. This can lead to unexpected results and make debugging challenging.

The `bug.js` file contains the problematic code. The `bugSolution.js` demonstrates how to resolve this using strict equality (===).