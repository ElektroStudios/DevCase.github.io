# NativeMethods.InitAtomTable Method 
 

Initializes the local atom table and sets the number of hash buckets to the specified size.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static bool InitAtomTable(
	uint size
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function InitAtomTable ( 
	size As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim size As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.InitAtomTable(size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static bool InitAtomTable(
	unsigned int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member InitAtomTable : 
        size : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>size</dt><dd>Type: System.UInt32<br />The number of hash buckets to use for the atom table. If this parameter is zero, the default number of hash buckets are created. 

 To achieve better performance, specify a prime number in *size*.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-initatomtable" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-initatomtable</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />