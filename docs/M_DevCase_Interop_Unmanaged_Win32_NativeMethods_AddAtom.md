# NativeMethods.AddAtom Method 
 

Adds a character string to the local atom table and returns a unique value (an atom) identifying the string.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static ushort AddAtom(
	string value
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function AddAtom ( 
	value As String
) As UShort
```

**VB Usage**<br />
``` VB Usage
Dim value As String
Dim returnValue As UShort

returnValue = NativeMethods.AddAtom(value)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned short AddAtom(
	String^ value
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member AddAtom : 
        value : string -> uint16 

```


#### Parameters
&nbsp;<dl><dt>value</dt><dd>Type: System.String<br />The null-terminated string to be added. The string can have a maximum size of 255 bytes. 

 Strings differing only in case are considered identical. The case of the first string added is preserved and returned by the GetAtomName function.</dd></dl>

#### Return Value
Type: UInt16<br />If the function succeeds, the return value is the newly created atom. 

 If the function fails, the return value is zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-addatomw" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winbase/nf-winbase-addatomw</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />