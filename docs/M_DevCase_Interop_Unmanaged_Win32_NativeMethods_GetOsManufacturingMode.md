# NativeMethods.GetOsManufacturingMode Method 
 

Determine whether the device is in Manufacturing Mode or not.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll")]
public static bool GetOsManufacturingMode(
	out bool refEnabled
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll">]
Public Shared Function GetOsManufacturingMode ( 
	<OutAttribute> ByRef refEnabled As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim refEnabled As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.GetOsManufacturingMode(refEnabled)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll")]
static bool GetOsManufacturingMode(
	[OutAttribute] bool% refEnabled
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll")>]
static member GetOsManufacturingMode : 
        refEnabled : bool byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>refEnabled</dt><dd>Type: System.Boolean<br />if set to `true` (`True` in Visual Basic) the device is in Manufacturing Mode.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is a nonzero `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/apiindex/umbrella-lib-onecore" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/apiindex/umbrella-lib-onecore</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />