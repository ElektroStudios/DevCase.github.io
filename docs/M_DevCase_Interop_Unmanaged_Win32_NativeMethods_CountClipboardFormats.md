# NativeMethods.CountClipboardFormats Method 
 

Retrieves the number of different data formats currently on the clipboard.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static int CountClipboardFormats()
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function CountClipboardFormats As Integer
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As Integer

returnValue = NativeMethods.CountClipboardFormats()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static int CountClipboardFormats()
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member CountClipboardFormats : unit -> int 

```


#### Return Value
Type: Int32<br />If the function succeeds, the return value is the number of different data formats currently on the clipboard. 

 If the function fails, the return value is zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms649036%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms649036%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />