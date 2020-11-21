# IPropertyStore.GetAt Method 
 

Gets a property key from an item's array of properties.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetAt(
	uint propertyIndex,
	out PropertyKey refPropertyKey
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetAt ( 
	propertyIndex As UInteger,
	<OutAttribute> ByRef refPropertyKey As PropertyKey
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IPropertyStore
Dim propertyIndex As UInteger
Dim refPropertyKey As PropertyKey
Dim returnValue As HResult

returnValue = instance.GetAt(propertyIndex, 
	refPropertyKey)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetAt(
	[InAttribute] unsigned int propertyIndex, 
	[OutAttribute] PropertyKey% refPropertyKey
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetAt : 
        propertyIndex : uint32 * 
        refPropertyKey : PropertyKey byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>propertyIndex</dt><dd>Type: System.UInt32<br />The index of the property key in the array of <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PropertyKey">PropertyKey</a> structures. This is a zero-based index.</dd><dt>refPropertyKey</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PropertyKey">DevCase.Interop.Unmanaged.Win32.Structures.PropertyKey</a><br />When this method returns, contains a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_PropertyKey">PropertyKey</a> structure that receives the unique identifier for a property.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPropertyStore">IPropertyStore Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />