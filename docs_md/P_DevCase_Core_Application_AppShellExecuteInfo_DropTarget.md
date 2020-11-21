# AppShellExecuteInfo.DropTarget Property 
 

Gets or sets the CLSID of an object (usually a local server rather than an in-process server) that implements `IDropTarget` interface. 

 By default, when the drop target is an executable file, and no DropTarget value is provided, the Shell converts the list of dropped files into a command-line parameter and passes it to `ShellExecuteEx` through lpParameters.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public Guid DropTarget { get; set; }
```

**VB**<br />
``` VB
Public Property DropTarget As Guid
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As AppShellExecuteInfo
Dim value As Guid

value = instance.DropTarget

instance.DropTarget = value
```

**C++**<br />
``` C++
public:
property Guid DropTarget {
	Guid get ();
	void set (Guid value);
}
```

**F#**<br />
``` F#
member DropTarget : Guid with get, set

```


#### Property Value
Type: Guid<br />The CLSID of an object (usually a local server rather than an in-process server) that implements `IDropTarget` interface.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_AppShellExecuteInfo">AppShellExecuteInfo Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />