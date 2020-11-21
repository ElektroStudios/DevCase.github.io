# DwmBlurBehind.TransitionOnMaximized Property 
 

Gets or sets a value indicating whether the window's colorization should transition to match the maximized windows.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public bool TransitionOnMaximized { get; set; }
```

**VB**<br />
``` VB
Public Property TransitionOnMaximized As Boolean
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DwmBlurBehind
Dim value As Boolean

value = instance.TransitionOnMaximized

instance.TransitionOnMaximized = value
```

**C++**<br />
``` C++
public:
property bool TransitionOnMaximized {
	bool get ();
	void set (bool value);
}
```

**F#**<br />
``` F#
member TransitionOnMaximized : bool with get, set

```


#### Property Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the window's colorization should transition to match the maximized windows; otherwise, `false` (`False` in Visual Basic).

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DwmBlurBehind">DwmBlurBehind Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />