# RegistryUtil.IsRegistryFile Method 
 

Determines whether a file is a valid Registry script file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsRegistryFile(
	string filepath
)
```

**VB**<br />
``` VB
Public Shared Function IsRegistryFile ( 
	filepath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim returnValue As Boolean

returnValue = RegistryUtil.IsRegistryFile(filepath)
```

**C++**<br />
``` C++
public:
static bool IsRegistryFile(
	String^ filepath
)
```

**F#**<br />
``` F#
static member IsRegistryFile : 
        filepath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The .reg file path.</dd></dl>

#### Return Value
Type: Boolean<br />\[Missing <returns> documentation for "M:DevCase.Core.Shell.Tools.RegistryUtil.IsRegistryFile(System.String)"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isRegFile As Boolean = IsRegistryFile("C:\File.reg")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />