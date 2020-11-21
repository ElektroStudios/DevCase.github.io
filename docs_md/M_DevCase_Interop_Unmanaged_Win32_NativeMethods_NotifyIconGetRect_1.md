# NativeMethods.NotifyIconGetRect Method (NotifyIconIdentifier, Rectangle)
 

Gets the screen coordinates of the bounding rectangle of a notification icon.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", EntryPoint = "Shell_NotifyIconGetRect", 
	SetLastError = true)]
public static int NotifyIconGetRect(
	in NotifyIconIdentifier refIdentifier,
	out Rectangle refIconLocation
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", EntryPoint := "Shell_NotifyIconGetRect", 
	SetLastError := true>]
Public Shared Function NotifyIconGetRect ( 
	ByRef refIdentifier As NotifyIconIdentifier,
	<OutAttribute> ByRef refIconLocation As Rectangle
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim refIdentifier As NotifyIconIdentifier
Dim refIconLocation As Rectangle
Dim returnValue As Integer

returnValue = NativeMethods.NotifyIconGetRect(refIdentifier, 
	refIconLocation)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", EntryPoint = L"Shell_NotifyIconGetRect", 
	SetLastError = true)]
static int NotifyIconGetRect(
	[InAttribute] NotifyIconIdentifier% refIdentifier, 
	[OutAttribute] Rectangle% refIconLocation
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", EntryPoint = "Shell_NotifyIconGetRect", 
	SetLastError = true)>]
static member NotifyIconGetRect : 
        refIdentifier : NotifyIconIdentifier byref * 
        refIconLocation : Rectangle byref -> int 

```


#### Parameters
&nbsp;<dl><dt>refIdentifier</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NotifyIconIdentifier">DevCase.Interop.Unmanaged.Win32.Structures.NotifyIconIdentifier</a><br />Pointer to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NotifyIconIdentifier">NotifyIconIdentifier</a> structure that identifies the icon.</dd><dt>refIconLocation</dt><dd>Type: System.Drawing.Rectangle<br />Pointer to a Rectangle structure that, when this function returns successfully, receives the coordinates of the icon.</dd></dl>

#### Return Value
Type: Int32<br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd378426%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd378426%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_NotifyIconGetRect">NotifyIconGetRect Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />