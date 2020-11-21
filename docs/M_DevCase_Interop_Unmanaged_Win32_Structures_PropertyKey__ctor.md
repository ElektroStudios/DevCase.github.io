# PropertyKey Constructor 
 

Crreates a new instance of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PropertyKey">PropertyKey</a> structure.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public PropertyKey(
	Guid formatId,
	int propertyId
)
```

**VB**<br />
``` VB
Public Sub New ( 
	formatId As Guid,
	propertyId As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim formatId As Guid
Dim propertyId As Integer

Dim instance As New PropertyKey(formatId, 
	propertyId)
```

**C++**<br />
``` C++
public:
PropertyKey(
	Guid formatId, 
	int propertyId
)
```

**F#**<br />
``` F#
new : 
        formatId : Guid * 
        propertyId : int -> PropertyKey
```


#### Parameters
&nbsp;<dl><dt>formatId</dt><dd>Type: System.Guid<br />A unique GUID for the property.</dd><dt>propertyId</dt><dd>Type: System.Int32<br />A property identifier (PID).</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PropertyKey">PropertyKey Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />