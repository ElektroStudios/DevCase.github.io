# NativeMethods.SymSetOptions Method 
 

Sets the options mask of a symbol.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("DbgHelp.dll", SetLastError = true)]
public static int SymSetOptions(
	SymOptionFlags symOptions
)
```

**VB**<br />
``` VB
<DllImportAttribute("DbgHelp.dll", SetLastError := true>]
Public Shared Function SymSetOptions ( 
	symOptions As SymOptionFlags
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim symOptions As SymOptionFlags
Dim returnValue As Integer

returnValue = NativeMethods.SymSetOptions(symOptions)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"DbgHelp.dll", SetLastError = true)]
static int SymSetOptions(
	SymOptionFlags symOptions
)
```

**F#**<br />
``` F#
[<DllImportAttribute("DbgHelp.dll", SetLastError = true)>]
static member SymSetOptions : 
        symOptions : SymOptionFlags -> int 

```


#### Parameters
&nbsp;<dl><dt>symOptions</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SymOptionFlags">DevCase.Interop.Unmanaged.Win32.Enums.SymOptionFlags</a><br />The symbol options. 

 Zero is a valid value and indicates that all options are turned off.</dd></dl>

#### Return Value
Type: Int32<br />The function returns the current options mask.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms681366%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms681366%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />