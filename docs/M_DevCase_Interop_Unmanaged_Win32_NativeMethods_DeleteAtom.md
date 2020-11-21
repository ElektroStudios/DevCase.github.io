# NativeMethods.DeleteAtom Method 
 

Decrements the reference count of a local string atom. 

 If the atom's reference count is reduced to zero, DeleteAtom(UInt16) removes the string associated with the atom from the local atom table.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)]
public static ushort DeleteAtom(
	ushort atom
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function DeleteAtom ( 
	atom As UShort
) As UShort
```

**VB Usage**<br />
``` VB Usage
Dim atom As UShort
Dim returnValue As UShort

returnValue = NativeMethods.DeleteAtom(atom)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true, SetLastError = true)]
static unsigned short DeleteAtom(
	unsigned short atom
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true, SetLastError = true)>]
static member DeleteAtom : 
        atom : uint16 -> uint16 

```


#### Parameters
&nbsp;<dl><dt>atom</dt><dd>Type: System.UInt16<br />The atom to be deleted.</dd></dl>

#### Return Value
Type: UInt16<br />If the function succeeds, the return value is zero. 

 If the function fails, the return value is the value specified in *atom* parameter.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-deleteatom" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-deleteatom</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />