# NativeMethods.LocalFree Method 
 

Frees the specified local memory object and invalidates its handle.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static IntPtr LocalFree(
	ref IntPtr refMemObj
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function LocalFree ( 
	ByRef refMemObj As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim refMemObj As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.LocalFree(refMemObj)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static IntPtr LocalFree(
	IntPtr% refMemObj
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member LocalFree : 
        refMemObj : IntPtr byref -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>refMemObj</dt><dd>Type: System.IntPtr<br />A handle to the local memory object. 

 This handle is returned by either the `LocalAlloc` or `LocalReAlloc` function. Note that it is not safe to free memory allocated with `GlobalAlloc`.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is Zero. 

 If the function fails, the return value is equal to a handle to the local memory object. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa366730%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa366730%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />