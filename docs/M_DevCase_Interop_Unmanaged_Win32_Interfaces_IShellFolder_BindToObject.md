# IShellFolder.BindToObject Method 
 

Retrieves a handler, typically the Shell folder object that implements <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder</a> for a particular item. 

 Optional parameters that control the construction of the handler are passed in the bind context.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
Object BindToObject(
	PIDL pidl,
	[OptionalAttribute] IBindCtx pbc,
	ref Guid refIid
)
```

**VB**<br />
``` VB
Function BindToObject ( 
	pidl As PIDL,
	<OptionalAttribute> pbc As IBindCtx,
	ByRef refIid As Guid
) As Object
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellFolder
Dim pidl As PIDL
Dim pbc As IBindCtx
Dim refIid As Guid
Dim returnValue As Object

returnValue = instance.BindToObject(pidl, 
	pbc, refIid)
```

**C++**<br />
``` C++
Object^ BindToObject(
	[InAttribute] PIDL^ pidl, 
	[OptionalAttribute] [InAttribute] IBindCtx^ pbc, 
	Guid% refIid
)
```

**F#**<br />
``` F#
abstract BindToObject : 
        pidl : PIDL * 
        [<OptionalAttribute>] pbc : IBindCtx * 
        refIid : Guid byref -> Object 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />The address of an ITEMIDLIST structure (PIDL) that identifies the subfolder. 

 This value can refer to an item at any level below the parent folder in the namespace hierarchy. 

 The structure contains one or more SHITEMID structures, followed by a terminating NULL.</dd><dt>pbc (Optional)</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IBindCtx<br />A pointer to an IBindCtx interface on a bind context object that can be used to pass parameters to the construction of the handler. 

 If this parameter is not used, set it to NULL. 

 Because support for this parameter is optional for folder object implementations, some folders may not support the use of bind contexts. 

 Information that can be provided in the bind context includes a BIND_OPTS structure that includes a `grfMode` member that indicates the access mode when binding to a stream handler. Other parameters can be set and discovered using IBindCtx::RegisterObjectParam and IBindCtx::GetObjectParam.</dd><dt>refIid</dt><dd>Type: System.Guid<br />The identifier of the interface to return. This may be IID_IShellFolder, IID_IStream, or any other interface that identifies a particular handler.</dd></dl>

#### Return Value
Type: Object<br />When this method returns, contains the address of a pointer to the requested interface. 

 If an error occurs, a NULL pointer is returned at this address.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />