# NativeMethods.ShowCursor Method 
 

Displays or hides the cursor.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static int ShowCursor(
	bool show
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function ShowCursor ( 
	show As Boolean
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim show As Boolean
Dim returnValue As Integer

returnValue = NativeMethods.ShowCursor(show)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static int ShowCursor(
	bool show
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member ShowCursor : 
        show : bool -> int 

```


#### Parameters
&nbsp;<dl><dt>show</dt><dd>Type: System.Boolean<br />If `true` (`True` in Visual Basic), the display count is incremented by one. 

 If `false` (`False` in Visual Basic), the display count is decremented by one.</dd></dl>

#### Return Value
Type: Int32<br />The return value specifies the new display count.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648396%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648396%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />