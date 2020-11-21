# IShellFolder.GetUIObjectOf Method 
 

Gets an object that can be used to carry out actions on the specified file objects or folders.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
Object GetUIObjectOf(
	IntPtr hwndOwner,
	uint pidlCount,
	IntPtr[] pidls,
	ref Guid refIid,
	IntPtr reserved = null
)
```

**VB**<br />
``` VB
Function GetUIObjectOf ( 
	hwndOwner As IntPtr,
	pidlCount As UInteger,
	pidls As IntPtr(),
	ByRef refIid As Guid,
	Optional reserved As IntPtr = Nothing
) As Object
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellFolder
Dim hwndOwner As IntPtr
Dim pidlCount As UInteger
Dim pidls As IntPtr()
Dim refIid As Guid
Dim reserved As IntPtr
Dim returnValue As Object

returnValue = instance.GetUIObjectOf(hwndOwner, 
	pidlCount, pidls, refIid, reserved)
```

**C++**<br />
``` C++
Object^ GetUIObjectOf(
	IntPtr hwndOwner, 
	unsigned int pidlCount, 
	[InAttribute] array<IntPtr>^ pidls, 
	Guid% refIid, 
	IntPtr reserved = nullptr
)
```

**F#**<br />
``` F#
abstract GetUIObjectOf : 
        hwndOwner : IntPtr * 
        pidlCount : uint32 * 
        pidls : IntPtr[] * 
        refIid : Guid byref * 
        ?reserved : IntPtr 
(* Defaults:
        let _reserved = defaultArg reserved null
*)
-> Object 

```


#### Parameters
&nbsp;<dl><dt>hwndOwner</dt><dd>Type: System.IntPtr<br />A handle to the owner window that the client should specify if it displays a dialog box or message box.</dd><dt>pidlCount</dt><dd>Type: System.UInt32<br />The number of file objects or subfolders specified in the *pidls* parameter.</dd><dt>pidls</dt><dd>Type: System.IntPtr[]<br />The address of an array of pointers to ITEMIDLIST structures, each of which uniquely identifies a file object or subfolder relative to the parent folder. 

 Each item identifier list must contain exactly one SHITEMID structure followed by a terminating zero.</dd><dt>refIid</dt><dd>Type: System.Guid<br />A reference to the IID of the interface to retrieve. 

 This can be any valid interface identifier that can be created for an item.</dd><dt>reserved (Optional)</dt><dd>Type: System.IntPtr<br />Reserved. Must be Zero.</dd></dl>

#### Return Value
Type: Object<br />When this method returns successfully, contains the interface pointer requested in *refIid*.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />