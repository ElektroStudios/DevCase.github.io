# NativeMethods.DeleteObject Method (IntPtr)
 

Deletes a logical pen, brush, font, bitmap, region, or palette, freeing all system resources associated with the object. 

 After the object is deleted, the specified handle is no longer valid. 

 Do not delete a drawing object (pen or brush) while it is still selected into a DC. 

 When a pattern brush is deleted, the bitmap associated with the brush is not deleted. The bitmap must be deleted independently.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static bool DeleteObject(
	IntPtr hObject
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function DeleteObject ( 
	hObject As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hObject As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.DeleteObject(hObject)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static bool DeleteObject(
	IntPtr hObject
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member DeleteObject : 
        hObject : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hObject</dt><dd>Type: System.IntPtr<br />A handle to a logical pen, brush, font, bitmap, region, or palette.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the specified handle is not valid or is currently selected into a DC, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633540%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633540%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeleteObject">DeleteObject Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />