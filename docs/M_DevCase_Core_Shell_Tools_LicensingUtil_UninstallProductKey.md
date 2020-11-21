# LicensingUtil.UninstallProductKey Method 
 

Uninstall the Windows product key of the current operating system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void UninstallProductKey()
```

**VB**<br />
``` VB
Public Shared Sub UninstallProductKey
```

**VB Usage**<br />
``` VB Usage

LicensingUtil.UninstallProductKey()
```

**C++**<br />
``` C++
public:
static void UninstallProductKey()
```

**F#**<br />
``` F#
static member UninstallProductKey : unit -> unit 

```


## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>PlatformNotSupportedException</td><td>Windows 7 or newer is required to use this feature.</td></tr><tr><td>Exception</td><td>Unknown error occurred during the product key uninstallation attempt.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/cc534599(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/cc534599(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_LicensingUtil">LicensingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />