# Door Mud
***

You can get this door from here: http://dmud.thebbs.org/. And Checkout the [DoorMud docs](http://dmud.thebbs.org/sysdocs.htm) too.
## Known Issues

Issue | OS 
--- | ---
32-bit version of DMUD does not run | Windows7 x86 32-bit

## 16-Bit Setup

* DMUD097.ZIP is the file you want, not the 32-bit version.
* Extract the files to \wwiv\doors\dmud\
* Edit \wwiv\doors\dmud\runmud.bat. There are two lines you need to un-comment and pun in the correct the paths.
* From the command line in \wwiv\doors\dmud run CONFIG.EXE
* You can CLEAR the line about the drop file location. That will be passed in when the door is launched. You can leave the other settings as-is for now unless you know what you're doing.
* Now setup a new entry in Chain Edit
```
A) Description  : Door MUD
B) Filename     : c:\wwiv\doors\dmud\runmud.bat -n %N -d c:\wwiv\temp%N
C) SL           : 10
D) AR           : None.
E) ANSI         : Optional
F) DOS Interrupt: NOT Used
G) Win32 FOSSIL : Yes
J) Local only   : No
K) Multi user   : Yes
L) Registered by: AVAILABLE
M) Usage        : 64
N) Age limit    : 0 - 255
```

* That is it.
