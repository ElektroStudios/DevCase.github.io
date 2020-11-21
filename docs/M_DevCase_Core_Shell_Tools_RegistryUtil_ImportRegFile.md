# RegistryUtil.ImportRegFile Method 
 

Imports a registry file into the current registry Hive.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static bool ImportRegFile(
	string regFilePath
)
```

**VB**<br />
``` VB
Public Shared Function ImportRegFile ( 
	regFilePath As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim regFilePath As String
Dim returnValue As Boolean

returnValue = RegistryUtil.ImportRegFile(regFilePath)
```

**C++**<br />
``` C++
public:
static bool ImportRegFile(
	String^ regFilePath
)
```

**F#**<br />
``` F#
static member ImportRegFile : 
        regFilePath : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>regFilePath</dt><dd>Type: System.String<br />The registry filepath.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if operation succeeds, `false` (`False` in Visual Basic) otherwise.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>regFilePath</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_RegistryUtil">RegistryUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />