# NativeMethods.DwmGetWindowAttribute Method (SafeHandle, DwmWindowAttribute, NativeRectangle, Int32)
 

Retrieves the current value of a specified attribute applied to a window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll")]
public static int DwmGetWindowAttribute(
	SafeHandle hWnd,
	DwmWindowAttribute attribute,
	ref NativeRectangle refAttribute,
	int sizeAttribute
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll">]
Public Shared Function DwmGetWindowAttribute ( 
	hWnd As SafeHandle,
	attribute As DwmWindowAttribute,
	ByRef refAttribute As NativeRectangle,
	sizeAttribute As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As SafeHandle
Dim attribute As DwmWindowAttribute
Dim refAttribute As NativeRectangle
Dim sizeAttribute As Integer
Dim returnValue As Integer

returnValue = NativeMethods.DwmGetWindowAttribute(hWnd, 
	attribute, refAttribute, sizeAttribute)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll")]
static int DwmGetWindowAttribute(
	SafeHandle^ hWnd, 
	DwmWindowAttribute attribute, 
	NativeRectangle% refAttribute, 
	int sizeAttribute
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll")>]
static member DwmGetWindowAttribute : 
        hWnd : SafeHandle * 
        attribute : DwmWindowAttribute * 
        refAttribute : NativeRectangle byref * 
        sizeAttribute : int -> int 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.Runtime.InteropServices.SafeHandle<br />The handle to the window from which the attribute data is retrieved.</dd><dt>attribute</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DwmWindowAttribute">DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute</a><br />The attribute to retrieve</dd><dt>refAttribute</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeRectangle">DevCase.Interop.Unmanaged.Win32.Structures.NativeRectangle</a><br />A pointer to a value that, when this function returns successfully, receives the current value of the attribute. 

 The type of the retrieved value depends on the value of the *attribute* parameter.</dd><dt>sizeAttribute</dt><dd>Type: System.Int32<br />The size of the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DwmWindowAttribute">DwmWindowAttribute</a> value being retrieved. 

 The size is dependent on the type of the *refAttribute* parameter.</dd></dl>

#### Return Value
Type: Int32<br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an HRESULT error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa969515%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa969515%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DwmGetWindowAttribute">DwmGetWindowAttribute Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />