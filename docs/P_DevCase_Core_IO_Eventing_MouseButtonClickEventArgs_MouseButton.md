# MouseButtonClickEventArgs.MouseButton Property 
 

Gets the mouse button.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public RawMouseButtons MouseButton { get; }
```

**VB**<br />
``` VB
Public ReadOnly Property MouseButton As RawMouseButtons
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As MouseButtonClickEventArgs
Dim value As RawMouseButtons

value = instance.MouseButton

```

**C++**<br />
``` C++
public:
property RawMouseButtons MouseButton {
	RawMouseButtons get ();
}
```

**F#**<br />
``` F#
member MouseButton : RawMouseButtons with get

```


#### Property Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_RawMouseButtons">RawMouseButtons</a><br />The mouse button.

## See Also


#### Reference
<a href="T_DevCase_Core_IO_Eventing_MouseButtonClickEventArgs">MouseButtonClickEventArgs Class</a><br /><a href="N_DevCase_Core_IO_Eventing">DevCase.Core.IO.Eventing Namespace</a><br />