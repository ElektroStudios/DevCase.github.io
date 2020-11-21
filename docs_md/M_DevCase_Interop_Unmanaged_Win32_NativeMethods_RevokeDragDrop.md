# NativeMethods.RevokeDragDrop Method 
 

Revokes the registration of the specified application window as a potential target for OLE drag-and-drop operations.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll")]
public static HResult RevokeDragDrop(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll">]
Public Shared Function RevokeDragDrop ( 
	hWnd As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim returnValue As HResult

returnValue = NativeMethods.RevokeDragDrop(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll")]
static HResult RevokeDragDrop(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll")>]
static member RevokeDragDrop : 
        hWnd : IntPtr -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />Handle to a window previously registered as a target for an OLE drag-and-drop operation.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> if an error occurs.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/ole2/nf-ole2-revokedragdrop" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/ole2/nf-ole2-revokedragdrop</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />