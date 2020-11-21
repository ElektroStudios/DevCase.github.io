# NativeMethods.DwmSetWindowAttribute Method (IntPtr, DwmWindowAttribute, IntPtr, UInt32)
 

Sets the value of non-client rendering attributes for a window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DwmApi.dll")]
public static int DwmSetWindowAttribute(
	IntPtr hWnd,
	DwmWindowAttribute attributeToSet,
	IntPtr attributeValue,
	uint attributeSize
)
```

**VB**<br />
``` VB
<DllImportAttribute("DwmApi.dll">]
Public Shared Function DwmSetWindowAttribute ( 
	hWnd As IntPtr,
	attributeToSet As DwmWindowAttribute,
	attributeValue As IntPtr,
	attributeSize As UInteger
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim attributeToSet As DwmWindowAttribute
Dim attributeValue As IntPtr
Dim attributeSize As UInteger
Dim returnValue As Integer

returnValue = NativeMethods.DwmSetWindowAttribute(hWnd, 
	attributeToSet, attributeValue, 
	attributeSize)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DwmApi.dll")]
static int DwmSetWindowAttribute(
	IntPtr hWnd, 
	DwmWindowAttribute attributeToSet, 
	IntPtr attributeValue, 
	unsigned int attributeSize
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DwmApi.dll")>]
static member DwmSetWindowAttribute : 
        hWnd : IntPtr * 
        attributeToSet : DwmWindowAttribute * 
        attributeValue : IntPtr * 
        attributeSize : uint32 -> int 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />The handle to the window that will receive the attributes.</dd><dt>attributeToSet</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DwmWindowAttribute">DevCase.Interop.Unmanaged.Win32.Enums.DwmWindowAttribute</a><br />A single <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DwmWindowAttribute">DwmWindowAttribute</a> flag to apply to the window. 

 This parameter specifies the attribute and the *attributeValue* parameter points to the value of that attribute.</dd><dt>attributeValue</dt><dd>Type: System.IntPtr<br />A pointer to the value of the attribute specified in the *attributeToSet* parameter. 

 Note that different <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_DwmWindowAttribute">DwmWindowAttribute</a> flags require different value types.</dd><dt>attributeSize</dt><dd>Type: System.UInt32<br />The size, in bytes, of the value type pointed To by the *attributeValue* parameter.</dd></dl>

#### Return Value
Type: Int32<br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa969524%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa969524%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DwmSetWindowAttribute">DwmSetWindowAttribute Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />