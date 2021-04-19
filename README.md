# issue-import-meta-babel-jest

 Jest testing a Node ES module that uses import.meta encounters `SyntaxError: Cannot use 'import.meta' outside a module`.

This shows the issue using babel-jest, but [a similar issue occurs using ts-jest](https://github.com/skapauan/issue-import-meta-ts-jest).


 ## Scripts

 `npm test` encounters the error.

 `npm start` (tsc and run the output) does not.
  