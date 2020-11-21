# NativeMethods.GlobalGetAtomName Method 
 

Retrieves a copy of the character string associated with the specified global atom.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint GlobalGetAtomName(
	ushort atom,
	StringBuilder buffer,
	int size
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GlobalGetAtomName ( 
	atom As UShort,
	buffer As StringBuilder,
	size As Integer
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim atom As UShort
Dim buffer As StringBuilder
Dim size As Integer
Dim returnValue As UInteger

returnValue = NativeMethods.GlobalGetAtomName(atom, 
	buffer, size)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int GlobalGetAtomName(
	unsigned short atom, 
	StringBuilder^ buffer, 
	int size
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GlobalGetAtomName : 
        atom : uint16 * 
        buffer : StringBuilder * 
        size : int -> uint32 

```


#### Parameters
&nbsp;<dl><dt>atom</dt><dd>Type: System.UInt16<br />The global atom associated with the character string to be retrieved.</dd><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />The buffer for the character string.</dd><dt>size</dt><dd>Type: System.Int32<br />The size, in characters, of the buffer.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, the return value is the length of the string copied to the buffer, in characters, not including the terminating null character. 

 If the function fails, the return value is zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms649063(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms649063(v=vs.85).aspx</a>

 About Atom Tables: <a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms649053(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms649053(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />