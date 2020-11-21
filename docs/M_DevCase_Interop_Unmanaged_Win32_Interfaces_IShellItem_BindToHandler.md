# IShellItem.BindToHandler Method 
 

Binds to a handler for an item as specified by the handler ID value (BHID).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
Object BindToHandler(
	IBindCtx pbc,
	ref Guid refBHID,
	ref Guid refIID
)
```

**VB**<br />
``` VB
Function BindToHandler ( 
	pbc As IBindCtx,
	ByRef refBHID As Guid,
	ByRef refIID As Guid
) As Object
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellItem
Dim pbc As IBindCtx
Dim refBHID As Guid
Dim refIID As Guid
Dim returnValue As Object

returnValue = instance.BindToHandler(pbc, 
	refBHID, refIID)
```

**C++**<br />
``` C++
Object^ BindToHandler(
	IBindCtx^ pbc, 
	Guid% refBHID, 
	Guid% refIID
)
```

**F#**<br />
``` F#
abstract BindToHandler : 
        pbc : IBindCtx * 
        refBHID : Guid byref * 
        refIID : Guid byref -> Object 

```


#### Parameters
&nbsp;<dl><dt>pbc</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IBindCtx<br />A pointer to an IBindCtx interface on a bind context object. Used to pass optional parameters to the handler. 

 The contents of the bind context are handler-specific. For example, when binding to BHID_Stream, the STGM flags in the bind context indicate the mode of access desired (read or read/write).</dd><dt>refBHID</dt><dd>Type: System.Guid<br />Reference to a GUID that specifies which handler will be created.</dd><dt>refIID</dt><dd>Type: System.Guid<br />IID of the object type to retrieve.</dd></dl>

#### Return Value
Type: Object<br />When this method returns, contains a pointer of type riid that is returned by the handler specified by *refBHID*.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellItem">IShellItem Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />