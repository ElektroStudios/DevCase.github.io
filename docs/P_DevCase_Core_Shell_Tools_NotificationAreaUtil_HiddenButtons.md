# NotificationAreaUtil.HiddenButtons Property 
 

Gets the buttons of the hidden section of the notification area window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<NativeToolBarButton> HiddenButtons { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property HiddenButtons As ReadOnlyCollection(Of NativeToolBarButton)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As ReadOnlyCollection(Of NativeToolBarButton)

value = NotificationAreaUtil.HiddenButtons

```

**C++**<br />
``` C++
public:
static property ReadOnlyCollection<NativeToolBarButton>^ HiddenButtons {
	ReadOnlyCollection<NativeToolBarButton>^ get ();
}
```

**F#**<br />
``` F#
static member HiddenButtons : ReadOnlyCollection<NativeToolBarButton> with get

```


#### Property Value
Type: ReadOnlyCollection(<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeToolBarButton">NativeToolBarButton</a>)<br />The buttons of the hidden section of the notification area window.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_NotificationAreaUtil">NotificationAreaUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />