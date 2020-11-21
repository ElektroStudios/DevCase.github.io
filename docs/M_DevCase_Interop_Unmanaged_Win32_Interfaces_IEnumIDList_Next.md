# IEnumIDList.Next Method 
 

Retrieves the specified number of item identifiers in the enumeration sequence and advances the current position by the number of items retrieved.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult Next(
	uint count,
	ref IntPtr refPidls,
	ref uint refFetched
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function Next ( 
	count As UInteger,
	ByRef refPidls As IntPtr,
	ByRef refFetched As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IEnumIDList
Dim count As UInteger
Dim refPidls As IntPtr
Dim refFetched As UInteger
Dim returnValue As HResult

returnValue = instance.Next(count, refPidls, 
	refFetched)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult Next(
	unsigned int count, 
	IntPtr% refPidls, 
	unsigned int% refFetched
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract Next : 
        count : uint32 * 
        refPidls : IntPtr byref * 
        refFetched : uint32 byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>count</dt><dd>Type: System.UInt32<br />The number of elements in the array referenced by the rgelt parameter.</dd><dt>refPidls</dt><dd>Type: System.IntPtr<br />The address of a pointer to an array of ITEMIDLIST pointers that receive the item identifiers. 

 The implementation must allocate these item identifiers using CoTaskMemAlloc. 

 The calling application is responsible for freeing the item identifiers using CoTaskMemFree.</dd><dt>refFetched</dt><dd>Type: System.UInt32<br />A pointer to a value that receives a count of the item identifiers actually returned in *refPidls*. 

 The count can be smaller than the value specified in the *count* parameter. 

 This parameter can be NULL on entry only if *count* = 1, because in that case the method can only retrieve one (<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>) or zero (<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_FALSE</a>) items.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if the method successfully retrieved the requested *count* elements. 

 This method only returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> if the full count of requested items are successfully retrieved. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_FALSE</a> indicates that more items were requested than remained in the enumeration. 

 The value pointed to by the *refPidls* parameter specifies the actual number of items retrieved. Note that the value will be 0 if there are no more items to retrieve.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IEnumIDList">IEnumIDList Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />