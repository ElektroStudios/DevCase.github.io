# ShortcutFileInfo.MoveTo Method 
 

Moves the shortcut file to a new location, providing the option to specify a new file name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public void MoveTo(
	string destFileName
)
```

**VB**<br />
``` VB
Public Sub MoveTo ( 
	destFileName As String
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
Dim destFileName As String

instance.MoveTo(destFileName)
```

**C++**<br />
``` C++
public:
void MoveTo(
	String^ destFileName
)
```

**F#**<br />
``` F#
member MoveTo : 
        destFileName : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>destFileName</dt><dd>Type: System.String<br />The path to move the shortcut file to, which can specify a different file name.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />