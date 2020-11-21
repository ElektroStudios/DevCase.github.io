# DwmPreviewManager.Handle Property 
 

Gets the handle for the window that owns this <a href="T_DevCase_Core_Application_UserInterface_DwmPreviewManager">DwmPreviewManager</a> instance.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual IntPtr Handle { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Handle As IntPtr
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As DwmPreviewManager
Dim value As IntPtr

value = instance.Handle

```

**C++**<br />
``` C++
public:
virtual property IntPtr Handle {
	IntPtr get ();
}
```

**F#**<br />
``` F#
abstract Handle : IntPtr with get
override Handle : IntPtr with get
```


#### Property Value
Type: IntPtr<br />The handle.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_DwmPreviewManager">DwmPreviewManager Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />