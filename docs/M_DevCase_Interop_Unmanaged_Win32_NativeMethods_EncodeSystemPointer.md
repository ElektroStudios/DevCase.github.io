# NativeMethods.EncodeSystemPointer Method (IntPtr)
 

Encodes the specified pointer with a system-specific value. 

 Encoded pointers can be used to provide another layer of protection for pointer values.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static IntPtr EncodeSystemPointer(
	IntPtr ptr
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function EncodeSystemPointer ( 
	ptr As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim ptr As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.EncodeSystemPointer(ptr)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static IntPtr EncodeSystemPointer(
	[InAttribute] IntPtr ptr
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member EncodeSystemPointer : 
        ptr : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>ptr</dt><dd>Type: System.IntPtr<br />The system pointer to be encoded.</dd></dl>

#### Return Value
Type: IntPtr<br />Returns the encoded pointer.

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/bb432255%28v%3dvs.85%29" target="_blank">https://docs.microsoft.com/en-us/previous-versions/bb432255%28v%3dvs.85%29</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_EncodeSystemPointer">EncodeSystemPointer Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />