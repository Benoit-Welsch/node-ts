# node-ts

A Template for nodejs with ts

## Available script

```json
    {
        "dev":"nodemon src/index.ts",
        "test": "mocha --require ts-node/register src/**/*.test.ts",
        "lint": "gts lint",
        "clean": "gts clean",
        "compile": "tsc",
        "fix": "gts fix",
        "prepare": "pnpm.cmd run compile",
        "pretest": "pnpm.cmd run compile",
        "posttest": "pnpm.cmd run lint"
    },
```
