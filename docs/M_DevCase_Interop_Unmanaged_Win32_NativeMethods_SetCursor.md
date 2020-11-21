# NativeMethods.SetCursor Method 
 

Sets the cursor shape.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static IntPtr SetCursor(
	IntPtr hCursor
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetCursor ( 
	hCursor As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hCursor As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.SetCursor(hCursor)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static IntPtr SetCursor(
	IntPtr hCursor
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetCursor : 
        hCursor : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hCursor</dt><dd>Type: System.IntPtr<br />A handle to the cursor. 

 The cursor must have been created by the CreateCursor function or loaded by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadCursor">LoadCursor(IntPtr, String)</a> or <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadImage">LoadImage(IntPtr, String, LoadImageType, Int32, Int32, LoadImageFlags)</a> function. 

 If this parameter is Zero, the cursor is removed from the screen.</dd></dl>

#### Return Value
Type: IntPtr<br />The return value is the handle to the previous cursor, if there was one. 

 If there was no previous cursor, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setcursor" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-setcursor</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />