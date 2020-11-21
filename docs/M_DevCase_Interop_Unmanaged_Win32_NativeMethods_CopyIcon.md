# NativeMethods.CopyIcon Method 
 

Copies the specified icon from another module to the current module.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr CopyIcon(
	IntPtr hIcon
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function CopyIcon ( 
	hIcon As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hIcon As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.CopyIcon(hIcon)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr CopyIcon(
	IntPtr hIcon
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member CopyIcon : 
        hIcon : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hIcon</dt><dd>Type: System.IntPtr<br />A handle to the icon to be copied.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the duplicate icon. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648058%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648058%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />