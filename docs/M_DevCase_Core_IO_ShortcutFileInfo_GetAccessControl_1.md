# ShortcutFileInfo.GetAccessControl Method (AccessControlSections)
 

Gets a FileSecurity object that encapsulates the specified type of access control list (ACL) entries for the file described by the current <a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo</a> object.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public FileSecurity GetAccessControl(
	AccessControlSections includeSections
)
```

**VB**<br />
``` VB
Public Function GetAccessControl ( 
	includeSections As AccessControlSections
) As FileSecurity
```

**VB Usage**<br />
``` VB Usage
Dim instance As ShortcutFileInfo
Dim includeSections As AccessControlSections
Dim returnValue As FileSecurity

returnValue = instance.GetAccessControl(includeSections)
```

**C++**<br />
``` C++
public:
FileSecurity^ GetAccessControl(
	AccessControlSections includeSections
)
```

**F#**<br />
``` F#
member GetAccessControl : 
        includeSections : AccessControlSections -> FileSecurity 

```


#### Parameters
&nbsp;<dl><dt>includeSections</dt><dd>Type: System.Security.AccessControl.AccessControlSections<br />One of the AccessControlSections values that specifies which group of access control entries to retrieve.</dd></dl>

#### Return Value
Type: FileSecurity<br />A FileSecurity object that encapsulates the access control rules for the current shortcut file.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_ShortcutFileInfo">ShortcutFileInfo Class</a><br /><a href="Overload_DevCase_Core_IO_ShortcutFileInfo_GetAccessControl">GetAccessControl Overload</a><br /><a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />