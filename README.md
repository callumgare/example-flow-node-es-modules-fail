```bash
npx flow-remove-types index.js
```
Will fail when package.json contains `"type": "module"` but succeeds when it's removed.