# IShellFolder.GetAttributesOf Method 
 

Gets the attributes of one or more file or folder objects contained in the object represented by <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
void GetAttributesOf(
	uint idl,
	IntPtr[] apidl,
	ref ShellItemAttributesMask refInOut
)
```

**VB**<br />
``` VB
Sub GetAttributesOf ( 
	idl As UInteger,
	apidl As IntPtr(),
	ByRef refInOut As ShellItemAttributesMask
)
```

**VB Usage**<br />
``` VB Usage
Dim instance As IShellFolder
Dim idl As UInteger
Dim apidl As IntPtr()
Dim refInOut As ShellItemAttributesMask

instance.GetAttributesOf(idl, apidl, refInOut)
```

**C++**<br />
``` C++
void GetAttributesOf(
	unsigned int idl, 
	[InAttribute] array<IntPtr>^ apidl, 
	ShellItemAttributesMask% refInOut
)
```

**F#**<br />
``` F#
abstract GetAttributesOf : 
        idl : uint32 * 
        apidl : IntPtr[] * 
        refInOut : ShellItemAttributesMask byref -> unit 

```


#### Parameters
&nbsp;<dl><dt>idl</dt><dd>Type: System.UInt32<br />The number of items from which to retrieve attributes.</dd><dt>apidl</dt><dd>Type: System.IntPtr[]<br />The address of an array of pointers to ITEMIDLIST structures, each of which uniquely identifies an item relative to the parent folder. 

 Each ITEMIDLIST structure must contain exactly one SHITEMID structure followed by a terminating zero.</dd><dt>refInOut</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemAttributesMask">DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask</a><br />Pointer to a value that, on entry, contains the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemAttributesMask">ShellItemAttributesMask</a> attributes that the calling application is requesting. 

 On exit, this value contains the requested attributes that are common to all of the specified items.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IShellFolder">IShellFolder Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />