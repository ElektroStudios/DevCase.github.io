# NativeMethods.SetLastError Method (Win32ErrorCode)
 

Sets the last-error code for the calling thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static void SetLastError(
	Win32ErrorCode errorCode
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Sub SetLastError ( 
	errorCode As Win32ErrorCode
)
```

**VB Usage**<br />
``` VB Usage
Dim errorCode As Win32ErrorCodeNativeMethods.SetLastError(errorCode)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static void SetLastError(
	Win32ErrorCode errorCode
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member SetLastError : 
        errorCode : Win32ErrorCode -> unit 

```


#### Parameters
&nbsp;<dl><dt>errorCode</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">DevCase.Interop.Unmanaged.Win32.Enums.Win32ErrorCode</a><br />The last-error code for the thread.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms680627%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms680627%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetLastError">SetLastError Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />