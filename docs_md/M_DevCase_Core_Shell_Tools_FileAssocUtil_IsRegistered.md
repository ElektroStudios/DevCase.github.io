# FileAssocUtil.IsRegistered Method 
 

Determines whether the specified file extension is registered in the current system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool IsRegistered(
	string extensionName
)
```

**VB**<br />
``` VB
Public Shared Function IsRegistered ( 
	extensionName As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim extensionName As String
Dim returnValue As Boolean

returnValue = FileAssocUtil.IsRegistered(extensionName)
```

**C++**<br />
``` C++
public:
static bool IsRegistered(
	String^ extensionName
)
```

**F#**<br />
``` F#
static member IsRegistered : 
        extensionName : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>extensionName</dt><dd>Type: System.String<br />The extension name (eg: .txt).</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the file extension is registered, otherwise, `false` (`False` in Visual Basic).

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>extensionName</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim isRegistered As Boolean = FileAssoc.IsRegistered(".ext")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_FileAssocUtil">FileAssocUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />