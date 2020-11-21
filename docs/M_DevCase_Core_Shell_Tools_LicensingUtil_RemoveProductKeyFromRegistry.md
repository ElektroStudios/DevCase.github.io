# LicensingUtil.RemoveProductKeyFromRegistry Method 
 

Removes the Windows product key from registry (to prevent unauthorized diffusion) of the current operating system. 

 It does not uninstall the product key.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void RemoveProductKeyFromRegistry()
```

**VB**<br />
``` VB
Public Shared Sub RemoveProductKeyFromRegistry
```

**VB Usage**<br />
``` VB Usage

LicensingUtil.RemoveProductKeyFromRegistry()
```

**C++**<br />
``` C++
public:
static void RemoveProductKeyFromRegistry()
```

**F#**<br />
``` F#
static member RemoveProductKeyFromRegistry : unit -> unit 

```


## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>PlatformNotSupportedException</td><td>Windows 7 or newer is required to use this feature.</td></tr><tr><td>Exception</td><td>Unknown error occurred during the product key removal attempt.</td></tr></table>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/cc534586(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/cc534586(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_LicensingUtil">LicensingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />