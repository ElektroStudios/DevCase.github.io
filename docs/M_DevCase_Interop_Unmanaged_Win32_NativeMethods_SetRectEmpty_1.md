# NativeMethods.SetRectEmpty Method (Rectangle)
 

Creates an empty Rectangle in which all coordinates are set to zero.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static bool SetRectEmpty(
	out Rectangle refRect
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function SetRectEmpty ( 
	<OutAttribute> ByRef refRect As Rectangle
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refRect As Rectangle
Dim returnValue As Boolean

returnValue = NativeMethods.SetRectEmpty(refRect)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static bool SetRectEmpty(
	[OutAttribute] Rectangle% refRect
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member SetRectEmpty : 
        refRect : Rectangle byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refRect</dt><dd>Type: System.Drawing.Rectangle<br />A pointer to the Rectangle structure that contains the rectangle to be set.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd145086(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd145086(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetRectEmpty">SetRectEmpty Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />