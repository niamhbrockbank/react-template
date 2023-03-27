# Simplified Create React App template

Extra features added:

-   Add CI with GitHub Actions
-   Add custom eslint config
-   Prettier
-   TypeScript
-   Removed unneccessary logo images
-   Removed unnecessary web-vitals
-   Added an example extra module and unit test (greet.ts)
-   Added more scripts to package.json

-   Add Cypress and e2e testing template
-   Add SASS
-   `pre-commit` checks with GitGuardian, to skip these checks use the `-n` parameter as follows:

```
git commit -m "commit message" -n
```


```
    "test": "react-scripts test --watchAll=false",
    "test:watch": "react-scripts test",
    "format": "prettier --write src",
    "format:check": "prettier --check src",
    "lint": "eslint src",
    "type-check": "tsc --noEmit"
```