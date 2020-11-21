# DevMode.FormName Field
 

A zero-terminated character array that specifies the name of the form to use; for example, "`Letter`" or "`Legal`". A complete set of names can be retrieved by using the `EnumForms` function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string FormName
```

**VB**<br />
``` VB
Public FormName As String
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevMode
Dim value As String

value = instance.FormName

instance.FormName = value
```

**C++**<br />
``` C++
public:
String^ FormName
```

**F#**<br />
``` F#
val mutable FormName: string
```


#### Field Value
Type: String

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevMode">DevMode Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />