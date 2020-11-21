# NativeMethods.FindAtom Method 
 

Searches the local atom table for the specified character string and retrieves the atom associated with that string.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static ushort FindAtom(
	string value
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function FindAtom ( 
	value As String
) As UShort
```

**VB Usage**<br />
``` VB Usage
Dim value As String
Dim returnValue As UShort

returnValue = NativeMethods.FindAtom(value)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned short FindAtom(
	String^ value
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member FindAtom : 
        value : string -> uint16 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.String<br />The character string for which to search.</dd></dl>

#### Return Value
Type: UInt16<br />If the function succeeds, the return value is the atom associated with the given string. 

 If the function fails, the return value is zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-findatoma" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-findatoma</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />