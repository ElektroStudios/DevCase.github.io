# NativeMethods.GlobalAddAtom Method 
 

Adds a character string to the global atom table and returns a unique value (an atom) identifying the string.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static ushort GlobalAddAtom(
	string str
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GlobalAddAtom ( 
	str As String
) As UShort
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim returnValue As UShort

returnValue = NativeMethods.GlobalAddAtom(str)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned short GlobalAddAtom(
	String^ str
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GlobalAddAtom : 
        str : string -> uint16 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The null-terminated string to be added. The string can have a maximum size of 255 bytes. 

 Strings that differ only in case are considered identical. 

 The case of the first string of this name added to the table is preserved and returned by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_GlobalGetAtomName">GlobalGetAtomName(UInt16, StringBuilder, Int32)</a> function.</dd></dl>

#### Return Value
Type: UInt16<br />If the function succeeds, the return value is the newly created atom. 

 If the function fails, the return value is zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms649060%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms649060%28v=vs.85%29.aspx</a>

 About Atom Tables: <a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms649053(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms649053(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />