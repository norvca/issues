# Issues
Kinds of irritating issues

## WSL
#### Issue: Can't use `npm install <package>` 
Reason: [Symlink issue]( https://github.com/microsoft/WSL/issues/3 )

Solution: 

- Exit `VS Code`, use WSL terminal to install packages



## NPM

#### Action: Run `npm install`  from a package.json

Error: `npm WARN notsup SKIPPING OPTIONAL DEPENDENCY: Unsupported platform for fsevents@1.2.4: wanted {"os":"darwin","arch":"any"} (current: {"os":"linux","arch":"x64"})`

Reason: Unknown

Solution: Close terminal in VS Code, Use `npm i -f` in WSL terminal directly.



## Docker
#### Issue: Conflict between Docker and Vmware  in windows

#### Solution:
Switch to VMware workstation
```bash
# Need to restart computer
bcdedit /set hypervisorlaunchtype off
```

Switch to Docker
```bash
# Need to restart computer
bcdedit /set hypervisorlaunchtype auto
```
