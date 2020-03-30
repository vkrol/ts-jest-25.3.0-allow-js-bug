# ts-jest-25.3.0-allow-js-bug
https://github.com/kulshekhar/ts-jest/issues/1471
## Steps
1. Run `npm install` or `yarn`
2. Run `npm run test` or `yarn test`
```
 FAIL  lib/__tests__/index.test.ts
  ● Test suite failed to run

    error TS5055: Cannot write file '/Users/vkrol/Projects/ts-jest-25.3.0-allow-js-bug/jest.config.js' because it would overwrite input file.
    error TS5055: Cannot write file '/Users/vkrol/Projects/ts-jest-25.3.0-allow-js-bug/lib/index.js' because it would overwrite input file.

Test Suites: 1 failed, 1 total
Tests:       0 total
Snapshots:   0 total
Time:        2.658s
Ran all test suites.
```
