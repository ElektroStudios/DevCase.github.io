# ShortcutFileInfo.GetAccessControl Method 
 

Gets a FileSecurity object that encapsulates the access control list (ACL) entries for the file described by the current <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a> object.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FileSecurity GetAccessControl()
```

**VB**<br />
``` VB
Public Function GetAccessControl As FileSecurity
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
Dim returnValue As FileSecurity

returnValue = instance.GetAccessControl()
```

**C++**<br />
``` C++
public:
FileSecurity^ GetAccessControl()
```

**F#**<br />
``` F#
member GetAccessControl : unit -> FileSecurity 

```


#### Return Value
Type: FileSecurity<br />A FileSecurity object that encapsulates the access control rules for the current shortcut file.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="Overload_DevCase_Core_IO_ShortcutFileInfo_GetAccessControl">GetAccessControl Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />