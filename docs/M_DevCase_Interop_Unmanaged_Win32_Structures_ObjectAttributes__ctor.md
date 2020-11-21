# ObjectAttributes Constructor 
 

Initializes a new instance of the <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">ObjectAttributes</a> struct.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public ObjectAttributes(
	string name,
	ObjectHandleAttributes attributes
)
```

**VB**<br />
``` VB
Public Sub New ( 
	name As String,
	attributes As ObjectHandleAttributes
)
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim attributes As ObjectHandleAttributes

Dim instance As New ObjectAttributes(name, attributes)
```

**C++**<br />
``` C++
public:
ObjectAttributes(
	String^ name, 
	ObjectHandleAttributes attributes
)
```

**F#**<br />
``` F#
new : 
        name : string * 
        attributes : ObjectHandleAttributes -> ObjectAttributes
```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The name of the object for which a handle is to be opened.</dd><dt>attributes</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ObjectHandleAttributes">DevCase.Interop.Unmanaged.Win32.Enums.ObjectHandleAttributes</a><br />Flags that specifies object handle attributes.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_ObjectAttributes">ObjectAttributes Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />