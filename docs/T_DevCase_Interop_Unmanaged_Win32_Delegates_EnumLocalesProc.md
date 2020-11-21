# Delegates.EnumLocalesProc Delegate
 

An application-defined callback function that processes enumerated locale information provided by the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_EnumSystemLocales">EnumSystemLocales(Delegates.EnumLocalesProc, EnumSystemLocalesFlags)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate bool EnumLocalesProc(
	string localeString
)
```

**VB**<br />
``` VB
Public Delegate Function EnumLocalesProc ( 
	localeString As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim instance As New EnumLocalesProc(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate bool EnumLocalesProc(
	String^ localeString
)
```

**F#**<br />
``` F#
type EnumLocalesProc = 
    delegate of 
        localeString : string -> bool
```


#### Parameters
&nbsp;<dl><dt>localeString</dt><dd>Type: System.String<br />Pointer to a buffer containing a null-terminated locale identifier string.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) to continue enumeration or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/desktop/legacy/dd317822(v=vs.85)" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/desktop/legacy/dd317822(v=vs.85)</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />