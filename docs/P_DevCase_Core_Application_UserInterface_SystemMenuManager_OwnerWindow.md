# SystemMenuManager.OwnerWindow Property 
 

Gets the window that owns this <a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager</a> instance.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual IWin32Window OwnerWindow { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property OwnerWindow As IWin32Window
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As SystemMenuManager
Dim value As IWin32Window

value = instance.OwnerWindow

```

**C++**<br />
``` C++
public:
virtual property IWin32Window^ OwnerWindow {
	IWin32Window^ get ();
}
```

**F#**<br />
``` F#
abstract OwnerWindow : IWin32Window with get
override OwnerWindow : IWin32Window with get
```


#### Property Value
Type: IWin32Window<br />The window.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_SystemMenuManager">SystemMenuManager Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />