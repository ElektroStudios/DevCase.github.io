# ShortcutFileInfo.CopyTo Method 
 

Copies an existing shortcut file to a new file, allowing the overwriting of an existing file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ShortcutFileInfo CopyTo(
	string destFileName,
	bool overwrite
)
```

**VB**<br />
``` VB
Public Function CopyTo ( 
	destFileName As String,
	overwrite As Boolean
) As ShortcutFileInfo
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
Dim destFileName As String
Dim overwrite As Boolean
Dim returnValue As ShortcutFileInfo

returnValue = instance.CopyTo(destFileName, 
	overwrite)
```

**C++**<br />
``` C++
public:
ShortcutFileInfo^ CopyTo(
	String^ destFileName, 
	bool overwrite
)
```

**F#**<br />
``` F#
member CopyTo : 
        destFileName : string * 
        overwrite : bool -> ShortcutFileInfo 

```


#### Parameters
&nbsp;<dl><dt>destFileName</dt><dd>Type: System.String<br />The name of the new file to copy to.</dd><dt>overwrite</dt><dd>Type: System.Boolean<br />`true` (`True` in Visual Basic) to allow an existing file to be overwritten; otherwise, `false` (`False` in Visual Basic).</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a><br />A new shortcut file, or an overwrite of an existing file if overwrite is true. 

 If the file exists and overwrite is false, an IOException is thrown.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />