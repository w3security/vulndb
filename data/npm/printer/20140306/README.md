## Overview
printer does not sanitize command arguments properly in the ```printDirect()``` function. If untrusted client input is passed in, command injection is possible.

_Source: [Node Security Project](https://nodesecurity.io/advisories/27)_

## Remediation
Upgrade to version > 0.0.1 which is available on github at https://github.com/tojocky/node-printer

## References
- https://nodesecurity.io/advisories/27
- https://github.com/tojocky/node-printer
- https://github.com/tojocky/node-printer/commit/e001e38738c17219a1d9dd8c31f7d82b9c0013c7

Special thanks to [Wes Cruver](https://github.com/chieffancypants) for providing a pull request!
