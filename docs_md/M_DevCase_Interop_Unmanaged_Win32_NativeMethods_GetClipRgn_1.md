# NativeMethods.GetClipRgn Method (SafeHandle, IntPtr)
 

Retrieves a handle identifying the current application-defined clipping region for the specified device context.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", SetLastError = true)]
public static int GetClipRgn(
	SafeHandle hdc,
	ref IntPtr refRegion
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", SetLastError := true>]
Public Shared Function GetClipRgn ( 
	hdc As SafeHandle,
	ByRef refRegion As IntPtr
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hdc As SafeHandle
Dim refRegion As IntPtr
Dim returnValue As Integer

returnValue = NativeMethods.GetClipRgn(hdc, 
	refRegion)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", SetLastError = true)]
static int GetClipRgn(
	SafeHandle^ hdc, 
	IntPtr% refRegion
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", SetLastError = true)>]
static member GetClipRgn : 
        hdc : SafeHandle * 
        refRegion : IntPtr byref -> int 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />A handle to the device context (DC).</dd><dt>refRegion</dt><dd>Type: System.IntPtr<br />A handle to an existing region before the function is called. 

 After the function returns, this parameter is a handle to a copy of the current clipping region.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds and there is no clipping region for the given device context, the return value is `0`. 

 If the function succeeds and there is a clipping region for the given device context, the return value is `1`. 

 If an error occurs, the return value is `-1`.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/dd144866%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/dd144866%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetClipRgn">GetClipRgn Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />