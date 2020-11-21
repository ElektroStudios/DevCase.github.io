# ShortcutFileInfo.OpenRead Method 
 

Creates a read-only FileStream.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FileStream OpenRead()
```

**VB**<br />
``` VB
Public Function OpenRead As FileStream
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
Dim returnValue As FileStream

returnValue = instance.OpenRead()
```

**C++**<br />
``` C++
public:
FileStream^ OpenRead()
```

**F#**<br />
``` F#
member OpenRead : unit -> FileStream 

```


#### Return Value
Type: FileStream<br />A read-only unshared FileStream object for the existing shortcut file.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />