# ShortcutFileInfo.Open Method (FileMode, FileAccess)
 

Opens the shortcut file in the specified mode with read, write, or read/write access.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FileStream Open(
	FileMode mode,
	FileAccess access
)
```

**VB**<br />
``` VB
Public Function Open ( 
	mode As FileMode,
	access As FileAccess
) As FileStream
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
Dim mode As FileMode
Dim access As FileAccess
Dim returnValue As FileStream

returnValue = instance.Open(mode, access)
```

**C++**<br />
``` C++
public:
FileStream^ Open(
	FileMode mode, 
	FileAccess access
)
```

**F#**<br />
``` F#
member Open : 
        mode : FileMode * 
        access : FileAccess -> FileStream 

```


#### Parameters
&nbsp;<dl><dt>mode</dt><dd>Type: System.IO.FileMode<br />A FileMode constant specifying the mode (for example, Open or Append) in which to open the shortcut file.</dd><dt>access</dt><dd>Type: System.IO.FileAccess<br />A FileAccess constant specifying whether to open the shortcut file with Read, Write, or ReadWrite file access.</dd></dl>

#### Return Value
Type: FileStream<br />The shortcut file opened in the specified mode and access, and unshared.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="Overload_DevCase_Core_IO_ShortcutFileInfo_Open">Open Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />