# ScrollInfo.TrackPos Field
 

The immediate position of a scroll box that the user is dragging. 

 An application can retrieve this value while processing the `SB_THUMBTRACK` request code. 

 An application cannot set the immediate scroll position; the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetScrollInfo">SetScrollInfo(IntPtr, ScrollBarOrientation, ScrollInfo, Boolean)</a> function ignores this member.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int TrackPos
```

**VB**<br />
``` VB
Public TrackPos As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As ScrollInfo
Dim value As Integer

value = instance.TrackPos

instance.TrackPos = value
```

**C++**<br />
``` C++
public:
int TrackPos
```

**F#**<br />
``` F#
val mutable TrackPos: int
```


#### Field Value
Type: Int32

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ScrollInfo">ScrollInfo Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />