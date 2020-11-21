# NativeMethods.GlobalFindAtom Method 
 

Searches the global atom table for the specified character string and retrieves the global atom associated with that string.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static ushort GlobalFindAtom(
	string str
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GlobalFindAtom ( 
	str As String
) As UShort
```

**VB Usage**<br />
``` VB Usage
Dim str As String
Dim returnValue As UShort

returnValue = NativeMethods.GlobalFindAtom(str)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned short GlobalFindAtom(
	[InAttribute] String^ str
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GlobalFindAtom : 
        str : string -> uint16 

```


#### Parameters
&nbsp;<dl><dt>str</dt><dd>Type: System.String<br />The null-terminated character string for which to search.</dd></dl>

#### Return Value
Type: UInt16<br />If the function succeeds, the return value is the global atom associated with the given string. 

 If the function fails, the return value is zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms649062(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms649062(v=vs.85).aspx</a>

 About Atom Tables: <a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms649053(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms649053(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />