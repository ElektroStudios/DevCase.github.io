# IShellFolder.BindToStorage Method 
 

Requests a pointer to an object's storage interface.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
Object BindToStorage(
	PIDL pidl,
	[OptionalAttribute] IBindCtx bindContext,
	ref Guid refIid
)
```

**VB**<br />
``` VB
Function BindToStorage ( 
	pidl As PIDL,
	<OptionalAttribute> bindContext As IBindCtx,
	ByRef refIid As Guid
) As Object
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellFolder
Dim pidl As PIDL
Dim bindContext As IBindCtx
Dim refIid As Guid
Dim returnValue As Object

returnValue = instance.BindToStorage(pidl, 
	bindContext, refIid)
```

**C++**<br />
``` C++
Object^ BindToStorage(
	[InAttribute] PIDL^ pidl, 
	[OptionalAttribute] [InAttribute] IBindCtx^ bindContext, 
	Guid% refIid
)
```

**F#**<br />
``` F#
abstract BindToStorage : 
        pidl : PIDL * 
        [<OptionalAttribute>] bindContext : IBindCtx * 
        refIid : Guid byref -> Object 

```


#### Parameters
&nbsp;<dl><dt>pidl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />The address of an ITEMIDLIST structure that identifies the subfolder relative to its parent folder. 

 The structure must contain exactly one SHITEMID structure followed by a terminating zero.</dd><dt>bindContext (Optional)</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IBindCtx<br />The optional address of an IBindCtx interface on a bind context object to be used during this operation. 

 If this parameter is not used, set it to NULL. 

 Because support for *bindContext* is optional for folder object implementations, some folders may not support the use of bind contexts.</dd><dt>refIid</dt><dd>Type: System.Guid<br />The IID of the requested storage interface. 

 To retrieve an IStream, IStorage, or IPropertySetStorage interface pointer, set *refIid* to IID_IStream, IID_IStorage, or IID_IPropertySetStorage, respectively.</dd></dl>

#### Return Value
Type: Object<br />The address that receives the interface pointer specified by *refIid*. 

 If an error occurs, a NULL pointer is returned in this address.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />