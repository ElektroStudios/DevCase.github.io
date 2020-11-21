# NativeMethods.GetKeyboardLayoutName Method (StringBuilder)
 

Retrieves the name of the active input locale identifier (formerly called the keyboard layout) for the system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Unicode, SetLastError = true)]
public static bool GetKeyboardLayoutName(
	StringBuilder klid
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Unicode, SetLastError := true>]
Public Shared Function GetKeyboardLayoutName ( 
	<OutAttribute> klid As StringBuilder
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim klid As StringBuilder
Dim returnValue As Boolean

returnValue = NativeMethods.GetKeyboardLayoutName(klid)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Unicode, SetLastError = true)]
static bool GetKeyboardLayoutName(
	[OutAttribute] StringBuilder^ klid
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Unicode, SetLastError = true)>]
static member GetKeyboardLayoutName : 
        klid : StringBuilder byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>klid</dt><dd>Type: System.Text.StringBuilder<br />The buffer (of at least `KL_NAMELENGTH` characters in length) that receives the name of the input locale identifier, including the terminating null character. 

 This will be a copy of the string provided to the `LoadKeyboardLayout` function, unless layout substitution took place.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms646298%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms646298%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetKeyboardLayoutName">GetKeyboardLayoutName Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />