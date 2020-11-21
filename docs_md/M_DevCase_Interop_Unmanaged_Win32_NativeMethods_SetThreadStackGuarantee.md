# NativeMethods.SetThreadStackGuarantee Method 
 

Sets the minimum size of the stack associated with the calling thread or fiber that will be available during any stack overflow exceptions. 

 This is useful for handling stack overflow exceptions; the application can safely use the specified number of bytes during exception handling.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static bool SetThreadStackGuarantee(
	ref uint refStackSizeInBytes
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetThreadStackGuarantee ( 
	ByRef refStackSizeInBytes As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refStackSizeInBytes As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.SetThreadStackGuarantee(refStackSizeInBytes)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static bool SetThreadStackGuarantee(
	unsigned int% refStackSizeInBytes
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member SetThreadStackGuarantee : 
        refStackSizeInBytes : uint32 byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refStackSizeInBytes</dt><dd>Type: System.UInt32<br />The size of the stack, in bytes. On return, this value is set to the size of the previous stack, in bytes. 

 If this parameter is 0 (zero), the function succeeds and the parameter contains the size of the current stack. 

 If the specified size is less than the current size, the function succeeds but ignores this request. Therefore, you cannot use this function to reduce the size of the stack. 

 This value cannot be larger than the reserved stack size.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-setthreadstackguarantee" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/processthreadsapi/nf-processthreadsapi-setthreadstackguarantee</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />