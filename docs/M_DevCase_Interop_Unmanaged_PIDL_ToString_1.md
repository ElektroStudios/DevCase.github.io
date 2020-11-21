# PIDL.ToString Method (ShellItemGetDisplayName)
 

Returns a String that represents this <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a> according to the format provided by *displayNameFormat*.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string ToString(
	ShellItemGetDisplayName displayNameFormat
)
```

**VB**<br />
``` VB
Public Function ToString ( 
	displayNameFormat As ShellItemGetDisplayName
) As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As PIDL
Dim displayNameFormat As ShellItemGetDisplayName
Dim returnValue As String

returnValue = instance.ToString(displayNameFormat)
```

**C++**<br />
``` C++
public:
String^ ToString(
	ShellItemGetDisplayName displayNameFormat
)
```

**F#**<br />
``` F#
member ToString : 
        displayNameFormat : ShellItemGetDisplayName -> string 

```


#### Parameters
&nbsp;<dl><dt>displayNameFormat</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemGetDisplayName">DevCase.Interop.Unmanaged.Win32.Enums.ShellItemGetDisplayName</a><br />The desired display name format.</dd></dl>

#### Return Value
Type: String<br />A String that represents this instance.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_PIDL_ToString">ToString Overload</a><br /><a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />