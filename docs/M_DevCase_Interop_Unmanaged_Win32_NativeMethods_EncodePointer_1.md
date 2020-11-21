# NativeMethods.EncodePointer Method (UIntPtr)
 

Encodes the specified pointer. 

 Encoded pointers can be used to provide another layer of protection for pointer values.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static UIntPtr EncodePointer(
	UIntPtr ptr
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function EncodePointer ( 
	ptr As UIntPtr
) As UIntPtr
```

**VB Usage**<br />
``` VB Usage
Dim ptr As UIntPtr
Dim returnValue As UIntPtr

returnValue = NativeMethods.EncodePointer(ptr)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static UIntPtr EncodePointer(
	[InAttribute] UIntPtr ptr
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member EncodePointer : 
        ptr : UIntPtr -> UIntPtr 

```


#### Parameters
&nbsp;<dl><dt>ptr</dt><dd>Type: System.UIntPtr<br />The pointer to be encoded.</dd></dl>

#### Return Value
Type: UIntPtr<br />Returns the encoded pointer.

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/bb432254(v%3Dvs.85)" target="_blank">https://docs.microsoft.com/en-us/previous-versions/bb432254(v%3Dvs.85)</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_EncodePointer">EncodePointer Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />