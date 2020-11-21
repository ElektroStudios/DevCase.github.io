# VmRunProgramFlags Enumeration
 

Specifies the behavior of a program that is executed by VMWare's vmrun.exe application.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum VmRunProgramFlags
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration VmRunProgramFlags
```

**VB Usage**<br />
``` VB Usage
Dim instance As VmRunProgramFlags
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class VmRunProgramFlags
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type VmRunProgramFlags
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.ThirdParty.VmWare.VmRunProgramFlags.None">**None**</td><td>1</td><td>Run the program using the default behavior.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.VmWare.VmRunProgramFlags.NoWait">**NoWait**</td><td>2</td><td>Returns a prompt immediately after the program starts in the guest operating system, rather than waiting for it to finish. 

 This option is useful for interactive programs.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.VmWare.VmRunProgramFlags.ActiveWindow">**ActiveWindow**</td><td>4</td><td>Ensures that the program window is visible, not minimized, in the guest operating system. 

 This option has no effect on Linux.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.VmWare.VmRunProgramFlags.Interactive">**Interactive**</td><td>8</td><td>Forces interactive guest login. 

 This option is useful for Windows VISTA guests to make the program visible in he console window.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_VmWare">DevCase.ThirdParty.VmWare Namespace</a><br />