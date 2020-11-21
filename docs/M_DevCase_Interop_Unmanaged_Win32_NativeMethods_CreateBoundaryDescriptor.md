# NativeMethods.CreateBoundaryDescriptor Method 
 

Creates a boundary descriptor.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static IntPtr CreateBoundaryDescriptor(
	string name,
	uint flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function CreateBoundaryDescriptor ( 
	name As String,
	flags As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim flags As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateBoundaryDescriptor(name, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static IntPtr CreateBoundaryDescriptor(
	[InAttribute] String^ name, 
	unsigned int flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member CreateBoundaryDescriptor : 
        name : string * 
        flags : uint32 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the boundary descriptor.</dd><dt>flags</dt><dd>Type: System.UInt32<br />This parameter is reserved for future use.</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the boundary descriptor. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-createboundarydescriptora" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-createboundarydescriptora</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />