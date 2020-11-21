# NativeMethods.GetRawInputBuffer Method 
 

Performs a buffered read of the raw input data.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static int GetRawInputBuffer(
	IntPtr data,
	ref uint refSize,
	uint sizeHeader
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function GetRawInputBuffer ( 
	data As IntPtr,
	ByRef refSize As UInteger,
	sizeHeader As UInteger
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim data As IntPtr
Dim refSize As UInteger
Dim sizeHeader As UInteger
Dim returnValue As Integer

returnValue = NativeMethods.GetRawInputBuffer(data, 
	refSize, sizeHeader)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static int GetRawInputBuffer(
	IntPtr data, 
	unsigned int% refSize, 
	unsigned int sizeHeader
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member GetRawInputBuffer : 
        data : IntPtr * 
        refSize : uint32 byref * 
        sizeHeader : uint32 -> int 

```


#### Parameters
&nbsp;<dl><dt>data</dt><dd>Type: System.IntPtr<br />A pointer to a buffer of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInput">RawInput</a> structures that contain the raw input data. 

 If NULL, the minimum required buffer, in bytes, is returned in *refSize*.</dd><dt>refSize</dt><dd>Type: System.UInt32<br />The size, in bytes, of a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInput">RawInput</a> structure.</dd><dt>sizeHeader</dt><dd>Type: System.UInt32<br />The size, in bytes, of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputHeader">RawInputHeader</a> structure.</dd></dl>

#### Return Value
Type: Int32<br />If *data* is NULL and the function is successful, the return value is zero. 

 If *data* is not NULL and the function is successful, the return value is the number of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInput">RawInput</a> structures written to *data*. 

 If an error occurs, the return value is -1.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getrawinputbuffer" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-getrawinputbuffer</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />