# Issues
Kinds of irritating issues

## WSL
#### Issue: Can't use `npm install <package>` 
Reason: [Symlink issue]( https://github.com/microsoft/WSL/issues/3 )

Solution: 

- Exit `VS Code`, use WSL terminal to install packages
- Or add ` --no-bin-links ` tail when installing, like `npm install <package> --no-bin-links `



## NPM

#### Action: Run `npm install`  from a package.json

Error: `npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.4: wanted {"os":"darwin","arch":"any"} (current: {"os":"linux","arch":"x64"})`

Reason: Unknown

Solution: Use `npm i -f`
