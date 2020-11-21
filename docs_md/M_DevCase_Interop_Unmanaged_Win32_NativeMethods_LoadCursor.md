# NativeMethods.LoadCursor Method 
 

Loads the specified cursor resource from the executable (.EXE) file associated with an application instance. 

 Note: This function has been superseded by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadImage">LoadImage(IntPtr, String, LoadImageType, Int32, Int32, LoadImageFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", BestFitMapping = false, ThrowOnUnmappableChar = true, 
	SetLastError = true)]
public static IntPtr LoadCursor(
	IntPtr hInstance,
	string cursorName
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", BestFitMapping := false, ThrowOnUnmappableChar := true, 
	SetLastError := true>]
Public Shared Function LoadCursor ( 
	hInstance As IntPtr,
	cursorName As String
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hInstance As IntPtr
Dim cursorName As String
Dim returnValue As IntPtr

returnValue = NativeMethods.LoadCursor(hInstance, 
	cursorName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", BestFitMapping = false, ThrowOnUnmappableChar = true, 
	SetLastError = true)]
static IntPtr LoadCursor(
	IntPtr hInstance, 
	String^ cursorName
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", BestFitMapping = false, ThrowOnUnmappableChar = true, 
	SetLastError = true)>]
static member LoadCursor : 
        hInstance : IntPtr * 
        cursorName : string -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hInstance</dt><dd>Type: System.IntPtr<br />A handle to an instance of the module whose executable file contains the cursor to be loaded.</dd><dt>cursorName</dt><dd>Type: System.String<br />The name of the cursor resource to be loaded. 

 Alternatively, this parameter can consist of the resource identifier in the low-order word and zero in the high-order word. 

 To use one of the predefined cursors, the application must set the *hInstance* parameter to Zero and the *cursorName* parameter to the predefined cursor name (eg. "IDC_ARROW", "IDC_CROSS", "IDC_HAND", "IDC_HELP", "IDC_IBEAM", "IDC_WAIT", etc).</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle to the newly loaded cursor. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-loadcursora" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-loadcursora</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />