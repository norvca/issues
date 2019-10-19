# Issues
Kinds of irritating issues

## WSL
#### Issue: Can't use `npm install <package>` 
Reason: [Symlink issue]( https://github.com/microsoft/WSL/issues/3 )

Solution: 

- Exit `VS Code`, use WSL terminal to install packages
- Or add ` --no-bin-links ` tail when installing, like `npm install <package> --no-bin-links `
