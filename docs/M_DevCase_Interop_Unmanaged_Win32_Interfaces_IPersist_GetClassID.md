# IPersist.GetClassID Method 
 

Retrieves the class identifier (CLSID) of the object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
void GetClassID(
	ref Guid refClassID
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Sub GetClassID ( 
	ByRef refClassID As Guid
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IPersist
Dim refClassID As Guid

instance.GetClassID(refClassID)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
void GetClassID(
	Guid% refClassID
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetClassID : 
        refClassID : Guid byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>refClassID</dt><dd>Type: System.Guid<br />A pointer to the location that receives the CLSID on return. 

 The CLSID is a globally unique identifier (GUID) that uniquely represents an object class that defines the code that can manipulate the object's data.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPersist">IPersist Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />