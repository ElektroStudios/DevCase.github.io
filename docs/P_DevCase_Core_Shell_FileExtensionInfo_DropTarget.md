# FileExtensionInfo.DropTarget Property 
 

For a verb invoked through COM and the `IDropTarget` interface, you can use this flag to retrieve the `IDropTarget` object's CLSID. 

 This CLSID is registered in the DropTarget subkey. The verb is specified in the `pwszExtra` parameter in the call to `IQueryAssociations::GetString`.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell">DevCase.Core.Shell</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string DropTarget { get; set; }
```

**VB**<br />
``` VB
Public Property DropTarget As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As FileExtensionInfo
Dim value As String

value = instance.DropTarget

instance.DropTarget = value
```

**C++**<br />
``` C++
public:
property String^ DropTarget {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member DropTarget : string with get, set

```


#### Property Value
Type: String<br />The CLSID of the associated IDropTarget object.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_FileExtensionInfo">FileExtensionInfo Class</a><br /><a href="N_DevCase_Core_Shell">DevCase.Core.Shell Namespace</a><br />