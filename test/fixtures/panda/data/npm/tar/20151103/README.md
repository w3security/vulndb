## Overview
The [`tar`](https://www.npmjs.com/package/tar) module does not properly normalize symbolic links pointing to targets outside the extraction root. As a result, packages may hold symbolic links to parent and sibling directories and overwrite those files when the package is extracted.

## Recommendation
Update to version 2.0.0 or greater. 
If a direct dependency update is not possible, use [`snyk wizard`](https://snyk.io/docs/using-snyk#wizard) to patch this vulnerability.

## References
- https://github.com/npm/node-tar/commit/5e6356e0ca256cba659ff24d0befbfe753a04cb6
- https://github.com/npm/npm/releases/tag/v2.7.5
