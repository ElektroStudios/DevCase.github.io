# NativeMethods.DefRawInputProc Method 
 

Calls the default raw input procedure to provide default processing for any raw input messages that an application does not process. 

 This function ensures that every message is processed. 

DefRawInputProc(RawInput[], Int32, UInt32) is called with the same parameters received by the window procedure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true)]
public static IntPtr DefRawInputProc(
	RawInput[] rawInput,
	int numInput,
	uint sizeHeader
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true>]
Public Shared Function DefRawInputProc ( 
	rawInput As RawInput(),
	numInput As Integer,
	sizeHeader As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim rawInput As RawInput()
Dim numInput As Integer
Dim sizeHeader As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.DefRawInputProc(rawInput, 
	numInput, sizeHeader)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true)]
static IntPtr DefRawInputProc(
	array<RawInput>^ rawInput, 
	int numInput, 
	unsigned int sizeHeader
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true)>]
static member DefRawInputProc : 
        rawInput : RawInput[] * 
        numInput : int * 
        sizeHeader : uint32 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>rawInput</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInput">DevCase.Interop.Unmanaged.Win32.Structures.RawInput</a>[]<br />An array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInput">RawInput</a> structures.</dd><dt>numInput</dt><dd>Type: System.Int32<br />The number of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInput">RawInput</a> structures pointed to by *rawInput*.</dd><dt>sizeHeader</dt><dd>Type: System.UInt32<br />The size, in bytes, of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_RawInputHeader">RawInputHeader</a> structure.</dd></dl>

#### Return Value
Type: IntPtr<br />If successful, the function returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise it returns an error value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-defrawinputproc" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-defrawinputproc</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />