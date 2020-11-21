# NativeMethods.EnumSystemCodePages Method 
 

Enumerates the code pages that are either installed on or supported by an operating system.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool EnumSystemCodePages(
	Delegates.EnumCodePagesProc codePageEnumProc,
	EnumSystemCodePagesFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function EnumSystemCodePages ( 
	codePageEnumProc As Delegates.EnumCodePagesProc,
	flags As EnumSystemCodePagesFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim codePageEnumProc As Delegates.EnumCodePagesProc
Dim flags As EnumSystemCodePagesFlags
Dim returnValue As Boolean

returnValue = NativeMethods.EnumSystemCodePages(codePageEnumProc, 
	flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool EnumSystemCodePages(
	Delegates.EnumCodePagesProc^ codePageEnumProc, 
	EnumSystemCodePagesFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member EnumSystemCodePages : 
        codePageEnumProc : Delegates.EnumCodePagesProc * 
        flags : EnumSystemCodePagesFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>codePageEnumProc</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumCodePagesProc">DevCase.Interop.Unmanaged.Win32.Delegates.EnumCodePagesProc</a><br />Pointer to an application-defined callback function. 

 The EnumSystemCodePages(Delegates.EnumCodePagesProc, EnumSystemCodePagesFlags) function enumerates code pages by making repeated calls to this callback function. 

 For more information, see <a href="T_DevCase_Interop_Unmanaged_Win32_Delegates_EnumCodePagesProc">Delegates.EnumCodePagesProc</a>.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_EnumSystemCodePagesFlags">DevCase.Interop.Unmanaged.Win32.Enums.EnumSystemCodePagesFlags</a><br />Flag specifying the code pages to enumerate.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-enumsystemcodepagesa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-enumsystemcodepagesa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />