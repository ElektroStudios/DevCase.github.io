# NativeMethods.GetRawInputData Method 
 

Retrieves the raw input from the specified device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll")]
public static uint GetRawInputData(
	IntPtr hRawInput,
	GetRawInputDataCommand uiCommand,
	IntPtr pData,
	ref uint refSize,
	uint cbSizeHeader
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll">]
Public Shared Function GetRawInputData ( 
	hRawInput As IntPtr,
	uiCommand As GetRawInputDataCommand,
	pData As IntPtr,
	ByRef refSize As UInteger,
	cbSizeHeader As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim hRawInput As IntPtr
Dim uiCommand As GetRawInputDataCommand
Dim pData As IntPtr
Dim refSize As UInteger
Dim cbSizeHeader As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.GetRawInputData(hRawInput, 
	uiCommand, pData, refSize, cbSizeHeader)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll")]
static unsigned int GetRawInputData(
	IntPtr hRawInput, 
	GetRawInputDataCommand uiCommand, 
	IntPtr pData, 
	unsigned int% refSize, 
	unsigned int cbSizeHeader
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll")>]
static member GetRawInputData : 
        hRawInput : IntPtr * 
        uiCommand : GetRawInputDataCommand * 
        pData : IntPtr * 
        refSize : uint32 byref * 
        cbSizeHeader : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>hRawInput</dt><dd>Type: System.IntPtr<br />A handle to the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInput">RawInput</a> structure. 

 This comes from the `lParam` in <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_WindowMessages">WM_Input</a>.</dd><dt>uiCommand</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_GetRawInputDataCommand">DevCase.Interop.Unmanaged.Win32.Enums.GetRawInputDataCommand</a><br />The command flag.</dd><dt>pData</dt><dd>Type: System.IntPtr<br />A pointer to the data that comes from the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInput">RawInput</a> structure. 

 This depends on the value of *uiCommand*. 

 If *pData* is Zero, the required size of the buffer is returned in *refSize*.</dd><dt>refSize</dt><dd>Type: System.UInt32<br />The size, in bytes, of the data in *pData*.</dd><dt>cbSizeHeader</dt><dd>Type: System.UInt32<br />The size, in bytes, of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputHeader">RawInputHeader</a> structure.</dd></dl>

#### Return Value
Type: UInt32<br />If *pData* is Zero and the function is successful, the return value is 0. 

 If *pData* is not Zero and the function is successful, the return value is the number of bytes copied into *pData*. 

 If there is an error, the return value is `-1`.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms645596%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms645596%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />