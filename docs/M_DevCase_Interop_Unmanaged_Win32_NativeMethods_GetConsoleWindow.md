# NativeMethods.GetConsoleWindow Method 
 

Retrieves the window handle used by the console associated with the calling process.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static IntPtr GetConsoleWindow()
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function GetConsoleWindow As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IntPtr

returnValue = NativeMethods.GetConsoleWindow()
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static IntPtr GetConsoleWindow()
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetConsoleWindow : unit -> IntPtr 

```


#### Return Value
Type: IntPtr<br />The return value is a handle to the window used by the console associated with the calling process or Zero if there is no such associated console.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms683175%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms683175%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />