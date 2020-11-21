# NativeMethods.CreateCompatibleDC Method (SafeHandle)
 

Creates a memory device context (DC) compatible with the specified device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static IntPtr CreateCompatibleDC(
	SafeHandle hdc
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function CreateCompatibleDC ( 
	hdc As SafeHandle
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hdc As SafeHandle
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateCompatibleDC(hdc)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static IntPtr CreateCompatibleDC(
	SafeHandle^ hdc
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member CreateCompatibleDC : 
        hdc : SafeHandle -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to an existing device context (DC). 

 If this handle is Zero, the function creates a memory device context (DC) compatible with the application's current screen.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is the handle to a memory device context (DC). 

 If the function fails, the return value is Zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd183489%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd183489%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateCompatibleDC">CreateCompatibleDC Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />