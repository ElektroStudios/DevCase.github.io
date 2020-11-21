# NativeMethods.CompareObjectHandles Method 
 

Compares two object handles to determine if they refer to the same underlying kernel object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", ExactSpelling = true)]
public static bool CompareObjectHandles(
	IntPtr hFirst,
	IntPtr hSecond
)
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", ExactSpelling := true>]
Public Shared Function CompareObjectHandles ( 
	hFirst As IntPtr,
	hSecond As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hFirst As IntPtr
Dim hSecond As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.CompareObjectHandles(hFirst, 
	hSecond)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", ExactSpelling = true)]
static bool CompareObjectHandles(
	IntPtr hFirst, 
	IntPtr hSecond
)
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", ExactSpelling = true)>]
static member CompareObjectHandles : 
        hFirst : IntPtr * 
        hSecond : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hFirst</dt><dd>Type: System.IntPtr<br />The first object handle to compare.</dd><dt>hSecond</dt><dd>Type: System.IntPtr<br />The second object handle to compare.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the objects compared refer to the same underlying kernel object; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/handleapi/nf-handleapi-compareobjecthandles" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/handleapi/nf-handleapi-compareobjecthandles</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />