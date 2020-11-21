# NativeMethods.IsValidCodePage Method 
 

Determines if a specified code page is valid.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", ExactSpelling = true)]
public static bool IsValidCodePage(
	uint codePage
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", ExactSpelling := true>]
Public Shared Function IsValidCodePage ( 
	codePage As UInteger
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim codePage As UInteger
Dim returnValue As Boolean

returnValue = NativeMethods.IsValidCodePage(codePage)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", ExactSpelling = true)]
static bool IsValidCodePage(
	unsigned int codePage
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", ExactSpelling = true)>]
static member IsValidCodePage : 
        codePage : uint32 -> bool 

```


#### Parameters
&nbsp;<dl><dt>codePage</dt><dd>Type: System.UInt32<br />Code page identifier for the code page to check.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) value if the code page is valid, or `false` (`False` in Visual Basic) if the code page is invalid.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-isvalidcodepage" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-isvalidcodepage</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />