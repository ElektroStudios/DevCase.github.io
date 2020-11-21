# IPropertyStore.GetCount Method 
 

Gets the number of properties attached to the file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetCount(
	out uint refPropertyCount
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetCount ( 
	<OutAttribute> ByRef refPropertyCount As UInteger
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IPropertyStore
Dim refPropertyCount As UInteger
Dim returnValue As HResult

returnValue = instance.GetCount(refPropertyCount)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetCount(
	[OutAttribute] unsigned int% refPropertyCount
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetCount : 
        refPropertyCount : uint32 byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refPropertyCount</dt><dd>Type: System.UInt32<br />When this method returns, contains the property count.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IPropertyStore">IPropertyStore Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />