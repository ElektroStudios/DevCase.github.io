# Delegates.EnumCodePagesProc Delegate
 

An application-defined callback function that processes enumerated code page information provided by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumSystemCodePages">EnumSystemCodePages(Delegates.EnumCodePagesProc, EnumSystemCodePagesFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate bool EnumCodePagesProc(
	string codePageString
)
```

**VB**<br />
``` VB
Public Delegate Function EnumCodePagesProc ( 
	codePageString As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As New EnumCodePagesProc(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate bool EnumCodePagesProc(
	String^ codePageString
)
```

**F#**<br />
``` F#
type EnumCodePagesProc = 
    delegate of 
        codePageString : string -> bool
```


#### Parameters
&nbsp;<dl><dt>codePageString</dt><dd>Type: System.String<br />Pointer to a buffer containing a null-terminated code page identifier string.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) to continue enumeration or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/desktop/legacy/dd317809(v%3Dvs.85)" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/desktop/legacy/dd317809(v%3Dvs.85)</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />