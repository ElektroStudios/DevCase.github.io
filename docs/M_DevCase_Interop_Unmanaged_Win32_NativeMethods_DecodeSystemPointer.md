# NativeMethods.DecodeSystemPointer Method (IntPtr)
 

Decodes a pointer that was previously encoded with <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EncodeSystemPointer">EncodeSystemPointer(IntPtr)</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static IntPtr DecodeSystemPointer(
	IntPtr ptr
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function DecodeSystemPointer ( 
	ptr As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim ptr As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.DecodeSystemPointer(ptr)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static IntPtr DecodeSystemPointer(
	[InAttribute] IntPtr ptr
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member DecodeSystemPointer : 
        ptr : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>ptr</dt><dd>Type: System.IntPtr<br />The pointer to be decoded.</dd></dl>

#### Return Value
Type: IntPtr<br />Returns the decoded pointer.

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/bb432243%28v%3dvs.85%29" target="_blank">https://docs.microsoft.com/en-us/previous-versions/bb432243%28v%3dvs.85%29</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DecodeSystemPointer">DecodeSystemPointer Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />