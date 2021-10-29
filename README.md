Notice: Supply Chain Packaging 
==================

don't

```jsonc
"ethers": "^4.0.47",
"ethersv5": "npm:ethers@^5.0.32" // wrong
```

do:

```diff
"ethers": "^4.0.47",
-"ethersv5": "npm:ethers@^5.0.32"
+"ethersV5": "github:ethers-io/ethers.js#v5.5.1" // better 
+"ethersV5": "github:ethers-io/ethers.js" // good
```

This package is just the ABI packaging from ethersjs@^5 

