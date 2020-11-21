# NativeMethods.GlobalDeleteAtom Method 
 

Decrements the reference count of a global string atom. 

 If the atom's reference count reaches zero, GlobalDeleteAtom(UInt16) removes the string associated with the atom from the global atom table.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static ushort GlobalDeleteAtom(
	ushort atom
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function GlobalDeleteAtom ( 
	atom As UShort
) As UShort
```

**VB Usage**<br />
``` VB Usage
Dim atom As UShort
Dim returnValue As UShort

returnValue = NativeMethods.GlobalDeleteAtom(atom)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static unsigned short GlobalDeleteAtom(
	unsigned short atom
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member GlobalDeleteAtom : 
        atom : uint16 -> uint16 

```


#### Parameters
&nbsp;<dl><dt>atom</dt><dd>Type: System.UInt16<br />The atom and character string to be deleted.</dd></dl>

#### Return Value
Type: UInt16<br />The function always returns (ATOM) 0. 

 To determine whether the function has failed, call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SetLastError">SetLastError(Win32ErrorCode)</a> with <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a> before calling GlobalDeleteAtom(UInt16), then call GetLastWin32Error(). If the last error code is still <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_SUCCESS</a>, then GlobalDeleteAtom(UInt16) has succeeded. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms649061%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms649061%28v=vs.85%29.aspx</a>

 About Atom Tables: <a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms649053(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms649053(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />