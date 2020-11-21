# IShellFolder.CreateViewObject Method 
 

Requests an object that can be used to obtain information from or interact with a folder object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
Object CreateViewObject(
	IntPtr hwndOwner,
	ref Guid refIid
)
```

**VB**<br />
``` VB
Function CreateViewObject ( 
	hwndOwner As IntPtr,
	ByRef refIid As Guid
) As Object
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellFolder
Dim hwndOwner As IntPtr
Dim refIid As Guid
Dim returnValue As Object

returnValue = instance.CreateViewObject(hwndOwner, 
	refIid)
```

**C++**<br />
``` C++
Object^ CreateViewObject(
	IntPtr hwndOwner, 
	Guid% refIid
)
```

**F#**<br />
``` F#
abstract CreateViewObject : 
        hwndOwner : IntPtr * 
        refIid : Guid byref -> Object 

```


#### Parameters
&nbsp;<dl><dt>hwndOwner</dt><dd>Type: System.IntPtr<br />A handle to the owner window. 

 If you have implemented a custom folder view object, your folder view window should be created as a child of *hwndOwner*.</dd><dt>refIid</dt><dd>Type: System.Guid<br />A reference to the IID of the interface to retrieve through ppv, typically IID_IShellView.</dd></dl>

#### Return Value
Type: Object<br />When this method returns successfully, contains the interface pointer requested in *refIid*. This is typically IShellView.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />