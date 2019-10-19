# Issues
Kinds of irritating issues

### NPM
- Issue: Error when excute `npm run lint`

  Reason: Shows when script exits with a code that is not `0`

  Solution: 

  ```json
  // Package.json
  {
    "scripts": {
      "lint": "eslint src || exit 0"
    }
  }
  ```
